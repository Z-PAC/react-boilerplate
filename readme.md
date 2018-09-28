# React App Boilerplate

Default folder and config structure for React apps.<br/>
Includes:<br/>
	-Webpack configs<br/>
	-Authentication<br/>
	-Firebase configs<br/>
	-Jest & Enzyme<br/>
	-Redux<br/>
	-React Router<br/>
	-Babel plugin configs<br/>
	-CSS loaders<br/>
	-Heroku integration<br/>

# Commands
	"build:dev": "webpack",
	"build:prod": "webpack -p --env production",
	"dev-server": "webpack-dev-server",
	"test": "cross-env NODE_ENV=test jest --config=jest.config.json",
	"start": "node server/server.js",
	"heroku-postbuild": "npm run build:prod"
