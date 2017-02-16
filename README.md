# weather-app
This is my weather application following [Andrew Mead](http://www.mead.io/)'s Complete Node.js Developer Course on Udemy. This repo is used purely for learning exercises and the course content should not be interpreted as something I've created on my own.

The weather application uses the Google Maps and Dark Sky APIs to display current weather based on an address given in the command line.

## Commands
All of these commands can be passed using the command line interface. Navigate to the project directory and run `npm install` to install the dependencies.

### Search
This application has the ability to search for the current weather based on a location. Use `--address` or `-a` to set the location that you would like weather for. The command accepts partial address or zip code.
`node app.js -a="22201"`
`node app.js -a="1600 Pennsylvania Ave. Washington, DC"`

### Help
If you have questions about what commands are available or how each command works, use the `--help` command.
`node app.js --help`
`node app.js -a --help`
