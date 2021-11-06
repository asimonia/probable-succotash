## Setup

1. You need to install three packages on your machine:
    - Node.js: The JavaScript runtime that you will use to run your frontend project.
    - npm: node package manager for Node.js applications
    - Python: A recent Python 3 interpreter to run the Flask backend
2. Run `npm install` in the project's root directory
3. Run the following commands in the api directory
```
$ python3 -m venv venv
$ source venv/bin/activate
(venv) $ pip install flask python-dotenv
```
4. Start the node start in development mode and run the Flask API backend with the scripts below.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### `npm run api`

Runs the Flask backend api.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run lint`

Ensures that any changes follow the guidelines provided in eslint.
