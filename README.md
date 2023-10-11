# Expo Router Example

Use [`expo-router`](https://expo.github.io/router) to build native navigation using files in the `app/` directory.

## 🚀 How to use

```sh
npx create-expo-app -e with-router
```

## 📝 Notes

- [Expo Router: Docs](https://expo.github.io/router)
- [Expo Router: Repo](https://github.com/expo/router)

# Implementation 

```
npx create-expo-app@latest -e with-router ./
npm install expo-font axios react-native-dotenv
npm install -g expo-cli
expo-cli start --tunnel
```

# Error Notes
Running into configuration problems with not finding .env?
@env could not be found
```
rm -rf node_modules/.cache/babel-loader/*
```
