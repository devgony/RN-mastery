# 1. INTRODUCTION

## install node & watchman

```
brew install node
brew install watchman
```

## install JDK

```
brew install --cask adoptopenjdk/openjdk/adoptopenjdk8
```

## install Android studio

https://developer.android.com/studio/index.html

```
Preference > System Settings > Android SDK > check Android 10.0 (Q) > Apply
```

## test RN

```
npx react-native init AwesomeProject
npx react-native run-android / run-ios
or npm run start | android | ios
```

## #1.4 CLI vs Ignite vs CRNA (12:47)

### ignite

- ignite > support full package

```sh
npx ignite-cli new PizzaApp
```

### CRNA (CreateReactNativeApp)

- collabo between facebook and expo

1. get access native files we need
2. able to work with expo
3. no supported structure like ignite

# 2. GENERAL CONCEPTS

## #2.0 Introduction (04:53)

### IMDB - movie app

```sh
npx create-react-native-app
> noovies
> Default new app
```
