# Tokens GUI

This example shows how to use jsonparser-cli to load tokens from style-dictionary into a GUI.

#### Running the example

First of all, set up the required dependencies running the command `npm install` in your local CLI environment (if you prefer to use _yarn_ update the commands accordingly).

At this point, if you want to start you can run `npm run build`. This command will run the Style Dictionary CLI with the **sd.config.js** as the configuration file and will generate the files in the `build` folder.

#### What to look at

The [`sd.config.js`](sd.config.js) file is the first thing to look at. It has a lot of comments how everything works. It shows how you can add a custom parser and set it to the yaml parser. You can also look in the [`tokens/`](tokens/) directory to see a yaml token file.