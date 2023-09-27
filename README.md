# React Native Tempalte

## Usage

* Create new project with cmd:
``` 
npx react-native@latest init ProjectName --template https://github.com/dangnguyen1004/React-Native-Template.git
```

* Rename the template with cmd:
```
npx react-native-rename@latest ProjectName
```

* Re-yarn project
```
yarn
```

* Start as React-Native project
```
yarn start
```

## Base dependencies
* typescript - For strongly types
* axios - For network calling.
* react-navigation - Application navigation.
* redux - Application state management.
* redux-persist - Persist redux state.
* redux-thunk - Enabling asynchronous dispatching of actions.

## Folder structure
This template follows a very simple project structure:

* assets: Asset folder to store all images, vectors, fonts, etc.
* src: This folder is the main container of all the code inside your application.
    * components: Folder to store any common component that you use through your app
    * constants: Folder to store any kind of constant that you have.
    * routes: Folder to store the navigators.
    * redux: This folder should have all your reducers and store
    * screens: Folder that contains all your application screens/features.
    * helper: Define helper functions in this folder.
    * utils: Folder to store any common function such as Analytics, Logger, DateTime, and etc.
* App.js: Main component that starts your whole app.
* index.js: Entry point of your application as per React-Native standards.

Modify the environment variables files in root folder (.env)

