# configuring-webpack-examples
Repository with example configuration in diferent use cases

# Getting Started

First step is to create a folder, then inside we initialize `npm`:

```bash
npm init -y
```

![Init](docs/init.png)

```bash
npm i -D webpack webpack-cli
```

If you will only need one output JS file the only remaining thing to make is a folder called src/ and inside a file called index.js. Inside of this file you can put you code, call other files and import CSS. Now please open your file called [package.json](package.json) and in the section called "scripts" like this:

```json
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "webpack"
  },
```

All that code will be output into a new file inside dist/ folder just using this command `npm start`. You'll notice the new folder and a file called main.js will be produced.

![npm start](docs/npm-start.png)

This file have already minified and uglyfy code, ready for copy/paste in your HTML! 