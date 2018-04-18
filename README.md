This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

Is an extension to React tutorial from [Reactjs.org](https://reactjs.org/tutorial/tutorial.html) to add following features as suggested by the tutorial:

* Display the location for each move in the format (col, row) in the move history list.
* Bold the currently selected item in the move list.
* Rewrite Board to use two loops to make the squares instead of hardcoding them.
* Add a toggle button that lets you sort the moves in either ascending or descending order.
* When someone wins, highlight the three squares that caused the win.
* When no one wins, display a message about the result being a draw.

## Git Repository Structure

Each commit will implement one of the suggested features.

## Folder Structure

After creation, your project should look like this:

```
my-app/
  README.md
  node_modules/
  package.json
  public/
    index.html
    favicon.ico
  src/
    index.css
    index.js    
```

For the project to build, **these files must exist with exact filenames**:

* `public/index.html` is the page template;
* `src/index.js` is the JavaScript entry point.

You can delete or rename the other files.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.


### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](#deployment) for more information.


## Supported Browsers

By default, the generated project uses the latest version of React.

You can refer [to the React documentation](https://reactjs.org/docs/react-dom.html#browser-support) for more information about supported browsers.

