# node/express app demo


Install nodejs to your machine [here](https://nodejs.org/en/download/) current tls release is 4.4.2
There are some caveats about installing on Linux, but it is pretty straightforward

we will be working a lot with the command line to interface with node, just fyi

Once you feel comfortable, feel free to create a pull request to this repo to add a feature

## Running the code

After cloning this repo, you will have to install dependencies. 
Simply run `npm install` in the `app-demo` folder and let the magic happen.

npm - node package manager. This is the node way to download site dependencies for the repo
more info on npm [here](https://docs.npmjs.com/) or if you need to do some troubleshooting

once the dependencies have installed, you can run the following to get the site to run locally for you `node server.js` OR you can also run `DEBUG=app-demo npm start` - this looks in `package.json` to see what command is to be run, the only difference being (in this case) running with some debuggin option

This is basically telling node to look in the server.js file to see how to run the local server for dev

Setup for basic express apps are relatively easy to get going with. If you are confused about how this was set up, ask me or look up some info on the interwebs.

You may want to look into something called `nodemon` installs with `npm install nodemon -g`
By default, node won't restart a server when you make a change to a js file. This will automatically poll for changes and restart the server in the event js has changed.