# jasonette-snippets README

This extension adds some jazzy Jasonette Code Snippets into Visual Studio Code. Get stoked!

![Jasonette Snippets](images/jasonette-snippets-code.gif "Jasonette Snippets In Action")

## Features

A boatload of snippets! What else do I need to say?

> Checkout the GitHub repo if catch any mistakes or you feel like you can contribute some more snippets!

## Requirements 

None. Visual Studio Code and ten fingers.

Only JSON files are supported.

## Snippets List

| Prefix | Jasonette Snippet Content |
| ------ | ------------ |
| `jason` | `A new jasonette app base` |
| `href` | `Used to describe links between views` |
| `$require` | `The $require action imports remote JSON files in parallel` |
| `$lambda` | `Call another action by name` |
| `$reload` | `Refreshes the view completely by re-fetching content from the current URL` |
| `$render` | `Renders a template with data` |
| `$snapshot` | `Takes a snapshot of the currently visible screen` |
| `$href` | `An action version of href. Works the same way, but can be used when a component doesn't support href attribute directly` |
| `$close` | `Close a modal (works when the currently view is a modal)` |
| `$back` | `Transition one step back from the current view. If the current view is a modal, it closes the current view, otherwise it slides back to the previous view` |
| `$network.request` | `Make GET/POST/PUT/DELETE Action requests` |
| `$network.upload` | `Upload data to cloud providers. Currently supports S3` |
| `$session.set` | `$session.set takes care of token authentication to authenticate into any mobile API` |
| `$session.reset` | `This action lets you clear sessions for a specified domain. Can be used for both token authentication and web authentication via cookies` |
| `$set` | `Use $set and $get to set and get local variables.` |
| `$get` | `Use $set and $get to set and get local variables.` |
| `$cache.set` | `$cache.set action is used to store to cache` |
| `$cache.get` | `Directly access $cache variable from a template expression` |
| `$cache.reset` | `Use $cache.reset action to reset the cache associated with the current url` |
| `$global.set` | `$global.set action is used to write to global variables` |
| `$global.get` | `Read global variables using template expressions` |
| `$global.reset` | `Use $global.reset action to remove global variables by name` |
| `$util.banner` | `Displays a banner notification with title and description` |
| `$util.toast` | `Displays a toast notification with a simple text` |
| `$util.alert` | `Displays an alert` |
| `$util.share` | `Share a text, image, video, or a combination of them` |
| `$util.picker` | `Opens a multiple choice picker menu, with each item linking to an action or an href` |
| `$util.datepicker` | `Opens a datepicker and returns the value in unix time format` |
| `$util.addressbook` | `Fetches the addressbook to populate them into $jason` |
| `$media.camera` | `Capture a video or a photo using the device camera` |
| `$media.picker` | `Opens the device camera roll` |
| `$media.play` | `plays a video from remote url` |
| `$audio.play` | `Play audio from remote url` |
| `$audio.pause` | `Pauses an audio clip that's already playing from a remote url` |
| `$audio.stop` | `Stops an audio clip that's already playing from a remote url. If URL is specified, stops ONLY this url. Otherwise, stops all audios currently playing` |
| `$audio.seek` | `Seeks audio already playing from a remote url` |
| `$audio.position` | `Get the position of the specified audio clip` |
| `$audio.duration` | `Returns total duration of the specified audio clip in seconds` |
| `$audio.record` | `Records audio` |
| `$geo.get` | `Get user's geolocation using accuracy in meters` |
| `$timer.start` | `Start a timer using seconds as a countdown` |
| `$timer.stop` | `Stops a timer using the name of the timer` |
| `$convert.csv` | `Converts CSV to parsed JSON` |
| `$convert.rss` | `Convert RSS to JSON. Built on top of node-feedparser library` |
| `label` | `Static uneditable text element` |
| `image` | `Image loaded from either remote url or data-url` |
| `button` | `A basic component that responds to user tap` |
| `textfield` | `Single line input field` |
| `textarea` | `Multiline input field` |
| `slider` | `Horizontal slider input` |
| `html` | `A self-contained web environment that you can plug in, style, and manipulate just like the rest of the components` |
| `space` | `An empty space component mostly used for layout purposes` |
| `map` | `Map component` |
| `layout` | `A layout to store components in` |
| `nestedlayout` | `A layout to store components in` |
| `each` | `Iterates through the expression that comes after declaration` |
| `if` | `Single conditional statement` |
| `ifelse` | `Conditional statement including else` |
| `elseif` | `Conditional statement including else` |
| `this` | `This keyword` |
| `mixin` | `Mixin Helper` |

## Known Issues

TBD

## Release Notes

### 1.0.0

Initial release