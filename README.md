# Storybook UI Options Addon

The Options addon can be used to set configure the Storybook UI. This addon works with both [React Storybook](https://github.com/kadirahq/react-storybook) and [React Native Storybook](https://github.com/kadirahq/react-native-storybook).

## Getting Started

First, install the addon

```shell
npm install -D @kadira/storybook-addon-options
```

Add this line to your `addons.js` file (create this file inside your storybook config directory if needed).

```js
import '@kadira/storybook-addon-options/register';
```

Import and use the `setOptions` function in your config.json file.

```js
import { setOptions } from '@kadira/storybook-addon-options'

setOptions({
  // ...
});
```