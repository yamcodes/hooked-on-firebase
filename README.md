# Hooked on Firebase 🎣🔥

A set of reusable [React Hooks](https://reactjs.org/docs/hooks-intro.html) for [Firebase (v9 and up)](https://firebase.google.com/).

> [!NOTE]
> **This is fork of [react-firebase-hooks](https://github.com/CSFrequency/react-firebase-hooks) with 2 additions:**
>
> 1. The [React 18 fix PR](https://github.com/CSFrequency/react-firebase-hooks/pull/298)
> 2. The [`useSignInWithCustomToken` PR](https://github.com/CSFrequency/react-firebase-hooks/pull/304)

## Quickstart

> [!IMPORTANT]
> We assume that you’re using the [npm](https://npmjs.com) or [yarn](https://yarnpkg.com/) package managers with a module bundler like [Webpack](https://webpack.js.org/) or [Browserify](http://browserify.org/) to consume [CommonJS](http://webpack.github.io/docs/commonjs.html) modules.

<details open>
  <summary>npm</summary>
  
  ```sh
  npm install hooked-on-firebase
  ```
</details>
<details>
  <summary>Yarn</summary>
  
  ```sh
  yarn add hooked-on-firebase
  ```
</details>

## Why?

From [react-firebase-hooks](https://github.com/CSFrequency/react-firebase-hooks)'s original _Why?_:

> This library explores how React Hooks can work to make integration with Firebase even more straightforward than it already is. It takes inspiration for naming from RxFire and is based on an internal library that we had been using in a number of apps prior to the release of React Hooks. The implementation with hooks is 10x simpler than our previous implementation.

## Documentation

- [Authentication Hooks](/auth)
- [Cloud Firestore Hooks](/firestore)
- [Cloud Functions Hooks](/functions)
- [Cloud Messaging Hooks](/messaging)
- [Cloud Storage Hooks](/storage)
- [Realtime Database Hooks](/database)

## License

- See [LICENSE](/LICENSE)
