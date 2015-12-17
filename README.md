# Jekyll + Gulp starting point

A simple setup that includes Jekyll for blogging, with Gulp to handle Sass, AutoPrefixer, Browser Sync and TinyPNG-based image optimisation.

## Setup

Make sure you have NPM (Node) installed. Clone this repo, then navigate to the folder and run:

    npm install

You can then start the build and watch process using the default `gulp` command.

## TinyPNG

The web service TinyPNG is great for compressing assets. The gulpfile.js includes a task for processing images and it'll automatically run this if it can. To set it up, [register for an API key](https://tinypng.com/developers) and then replace the `[YOUR_API_KEY]` text with the key.

## Contributions

Please do tidy and improve this as you see fit. I've found it helpful when starting new Jekyll projects but it's not complete. It doesn't include JS minification for example. Any contributions are welcome, but please do try to keep in mind that this is a generic starting point.

## License

As with Jekyll, the MIT license applies.
