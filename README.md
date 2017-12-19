# packageJson-for-create-react-app

This is an enhanced package.json file.

copy dependencies and scripts.


  "dependencies": {
    "babel-polyfill": "^6.26.0",
    "classnames": "^2.2.5",
    "eslint": "^4.12.0",
    "node-sass-chokidar": "^0.0.3",
    "npm-run-all": "^4.1.1",
    "react": "^16.0.0",
    "react-dom": "^16.0.0",
    "react-font-icon": "^1.0.0",
    "react-icons": "^2.2.7",
    "react-router-dom": "^4.2.2",
    "react-scripts": "1.0.14"
  },
  "scripts": {
    "build-css": "node-sass-chokidar src/ -o src/",
    "watch-css": "npm run build-css && node-sass-chokidar src/ -o src/ --watch --recursive",
    "start-js": "react-scripts start",
    "start": "npm-run-all -p watch-css start-js",
    "build": "npm run build-css && react-scripts build",
    "test": "react-scripts test --env=jsdom",
    "eject": "react-scripts eject"
  }
