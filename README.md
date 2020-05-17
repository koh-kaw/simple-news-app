# news-app-owl

A simple news app developed with React Native

# Env

- Node.js: v12.10.0
- react-native-cli: 2.0.1
- react-native: 0.61.4
- Expo: v35.0.0
- Expo CLI: v3.20.3

# expo-cli

- Install

```sh
$ npm install expo-cli --global

$ expo --version
3.20.3
```

- Login to Expo

```sh
$ expo login
? Username/Email Address: xxx
? Password: [hidden]

Success. You are now logged in as kawk.
```

- Start to Expo

```sh
$ cd news-app-owl
$ expo start
```

# Configure

- app.json

You need to insert the [NewsAPI](https://newsapi.org/) key into the `"extra"` in `app.json`.

```json
"extra": {
      "newsApiKey": "<API Key>"
```
