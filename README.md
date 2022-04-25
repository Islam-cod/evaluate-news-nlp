# Project Overview

A simple web tool that allows users to run Natural Language Processing (NLP) on articles found on other websites to display sentiment analysis through meaningcloud API
This project is built using the starter code from Udacity.

## Technologies used

- HTML
- CSS
- JavaScript
- Node
- Express
- Webpack
- meaningcloud API
- Jest
- Workbox

## Installation

Make sure Node and npm are installed from the terminal.

```
node -v
npm -v
```

1. Move to the project folder

```
cd <project directory>
```

2. Clone the repo

```
git clone <repo>
```

3. Install npm

```
npm install
```

4. Install loaders and plugins

```
# Choose the necessary installation for your development mode
npm i -D @babel/core @babel/preset-env babel-loader
npm i -D style-loader node-sass css-loader sass-loader
npm i -D clean-webpack-plugin
npm i -D html-webpack-plugin
npm i -D mini-css-extract-plugin
npm i -D optimize-css-assets-webpack-plugin terser-webpack-plugin
```

5. Sign up for an API key at [meaningcloud.com](https://www.meaningcloud.com/developer/create-account)

6. Configure environment variables using dotenv package
   1. Install the dotenv package
   ```
   npm install dotenv
   ```
   2. Create a new `.env` file in the root of your project
   3. Fill the `.env` file with your API key like this:
   ```
   API_KEY=**************************
   ```
7. Start the project

|       Command        |    Action     |
| :------------------: | :-----------: |
| `npm run build-prod` | Build project |
|     `npm start`      |  Run project  |
