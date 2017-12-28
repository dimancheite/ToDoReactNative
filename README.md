ToDo List with React Native
---------------------------

This is the sample ToDo list build with React Native. We use `json-server` as the backend for CRUD operation with ToDo item.

Local set up
------------

* Install `json-server` to handle CRUD operation. We will use it as backend.
```
npm install -g json-server
```

* Install project: `https://github.com/Nguonchhay/ToDoReactNative.git`

* Install dependencies
```
cd ToDoReactNative
npm install
```

__Note__: for environment set up, follow the [React Native getting start](https://facebook.github.io/react-native/docs/getting-started.html).

* Start server
```
cd ToDoReactNative
json-server server/db.json -p 5555
```

__Note__: you can use any ports you wish but make sure it is not used by another services.

* Run the app by plug the device or start the emulator
```
For android: react-native run-android
For ios:     react-native run-ios
```
