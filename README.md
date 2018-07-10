# React Chrome Extension

chrome extension boilerplate with ReactJs using inject page strategy.

## Features

- Used ReactJs to write chrome extension
- Injecting extension to host page as content script
- Utilized the Chrome messaging API
- Isolated extension CSS using Iframe
- Routing inside react extension

## Installation

```
git clone https://github.com/satendra02/react-chrome-extension.git
```
Go to `react-chrome-extension` directory run

```
yarn install
```
Now build the extension using
```
yarn build
```
You will see a `build` folder genrated inside `[PROJECT_HOME]`

## Adding React app extension to Chrome

In Chrome browser, go to chrome://extensions page and switch on developer mode. This enables the ability to locally install a Chrome extension.

Now click on the `LOAD UNPACKED` and browse to `[PROJECT_HOME]\build` ,This will install the React app as a Chrome extension.

When you go to any website and click on extension icon, injected page will toggle.
