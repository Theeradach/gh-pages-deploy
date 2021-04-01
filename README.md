# Getting Started with Create React App

 [Site Page](https://theeradach.github.io/gh-pages-deploy/).

## Deploy Step
- `npm run deploy`

## Step to Deploy to Github Pages ***  Note : Only 1st Time
- `npx create-react-app <project-name>`
- `cd <project-name>`

- create Github Respository named => `https://github.com/Theeradach/gh-pages-deploy`
- edit package.json file.
- add these following code to package.json

```
//...
"homepage": "http://<github-name>.github.io/<respository-name>"

"scripts": {
  //...
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"

}
```

- go to project dir && `git init`
- `git remote add origin https://github.com/Theeradach/gh-pages-deploy`
- `npm run deploy`