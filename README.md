# Weather app

To download the project first run `git clone git@github.com:msaarmets/weather-app.git` and then `git submodule update --init --recursive` to register and pull the submodules.

### Server

1. To initialize the server `cd` to `server` and run `yarn initialize`
2. Add API key to .env file
3. To run tests use `yarn test`
4. To start the server run `yarn start`

### Client

1. Install the dependecies: `cd` to `client` and run `yarn install`
2. Start the app: `yarn start`

The default URL of API is `http://localhost:4000`. You can specify the URL in `src/config.ts`.
