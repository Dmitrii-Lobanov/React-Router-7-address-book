# Description
We'll be building a small, but feature-rich address book app that lets you keep track of your contacts. There's no database or other "production ready" things, so we can stay focused on the features React Router gives you.
The project is based on a [React Router 7 tutorial](https://reactrouter.com/tutorials/address-book#address-book).

## Development

From your terminal:

```sh
npm run dev
```

This starts your app in development mode, rebuilding assets on file changes.

## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```

Now you'll need to pick a host to deploy it to.

### DIY

If you're familiar with deploying node applications, the built-in React Router app server is production-ready.

Make sure to deploy the output of `react-router build`

- `build/server`
- `build/client`
