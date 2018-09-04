# React Contact Manager

Contact Manager application using:

- React
- Context API
- JSON Placeholder

## Deploy to GitHub Pages

- Install the GitHub Pages dependency

```
npm i gh-pages
```

- Set a homepage in the package.json

```
"homepage": "https://github.com/deltorosalazar/react-contact-manager",
```

- Set up a new npm command to build and deploy the application

```
"scripts": {
    "deploy": "npm run build && gh-pages -d build",
    ....
  }
```

- Run the deploy command

```
npm run deploy
```
