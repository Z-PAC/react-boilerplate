# React App Boilerplate

Default folder and config structure for React apps.
Includes:
	-Webpack configs
	-Authentication
	-Firebase configs
	-Jest & Enzyme
	-Redux
	-React Router
	-Babel plugin configs
	-CSS loaders

# Commands
	"build:dev": "webpack",
	"build:prod": "webpack -p --env production",
	"dev-server": "webpack-dev-server",
	"test": "cross-env NODE_ENV=test jest --config=jest.config.json",
	"start": "node server/server.js",
	"heroku-postbuild": "npm run build:prod"
