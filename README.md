# Django-React-App
A minimal setup for getting React working in Vite with HMR and some ESLint rules, backed by a Django server.

## What it does
This template provides a basic configuration to get you started with a React application, using Vite for development and ESLint for code linting. The Django backend handles API requests and serves the React application.

## Installation and Running
To get started, follow these steps:
1. Clone this repository: `git clone https://github.com/your-username/Django-React-App.git`
2. Install dependencies: `npm install` and `pip install -r requirements.txt`
3. Start the Django server: `python manage.py runserver`
4. Start the Vite development server: `npm run dev`

## Example Usage
You can test the setup by creating a new React component and adding it to the `App.js` file. For example, create a new file `HelloWorld.js` with the following code:
```javascript
import React from 'react';

const HelloWorld = () => {
  return <h1>Hello World!</h1>;
};

export default HelloWorld;
```
Then, add the component to `App.js`:
```javascript
import React from 'react';
import HelloWorld from './HelloWorld';

function App() {
  return (
    <div>
      <HelloWorld />
    </div>
  );
}

export default App;
```
This should render the "Hello World!" message in your browser when you visit `http://localhost:8000`.