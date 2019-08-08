# cobi-react-scripts

This package is a fork of react-scripts included in [Create React App](https://github.com/facebook/create-react-app).<br>
Please refer to its documentation:

- [Getting Started](https://facebook.github.io/create-react-app/docs/getting-started) – How to create a new app.
- [User Guide](https://facebook.github.io/create-react-app/) – How to develop apps bootstrapped with Create React App.

# Usage

```sh
create-react-app --scripts-version cobi-react-scripts
```

# Customizations

Specify the following options in your package.json:

- **reactSrcDir** folder in which your react sources are located, relative to the project's base folder
  _Note:_ This option will interfer with the usage of react-dev-utils, which will still search in 'src'
- **reactBuildDir** folder in which your react build files will be stored, relative to the project's base folder
