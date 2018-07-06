
# Commands

## Installing dependencies

To install the project’s dependencies, run

```
npm install
```

You’re now ready to run and see your app!

## Run the app in development mode

To run the app locally, run

```
npm start -- --hostname 0.0.0.0 --port 4444
```

## Run the tests

Check out the [Application testing](https://polymer.github.io/pwa-starter-kit/application-testing) page for more information about the tests. For a quick way to run the tests, run

```
npm run test
```

## Available scripts

In the app’s root directory you can run:

- `npm start` to run the application in development mode
- `npm run test` to run the application’s unit and integration tests (see the see the [testing section](https://polymer.github.io/pwa-starter-kit/application-testing) for more details. To run just the unit or integration tests, both npm run test:unit and `npm run test:integration` are available.
- `npm run build` to build your application for production (see the [building and deploying](https://polymer.github.io/pwa-starter-kit/building-and-deploying) section for more details)
- `npm run serve:static` or `npm run serve:prpl-server` to serve the built application (see the [building and deploying](https://polymer.github.io/pwa-starter-kit/building-and-deploying) section for more details)

The complete list of scripts can be found in the `package.json` file.