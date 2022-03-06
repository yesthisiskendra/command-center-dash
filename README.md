# README.MD

## HOW TO REMAKE:

1. `npx create-react-app command-center-dash`
2. `git remote add origin https://github.com/yesthisiskendra/command-center-dash.git && git branch -M main && git push -u origin main`
3. `npm i gh-pages --save-dev`
4. Add NOTE A to package.json
5.

#### NOTE A

Add this to the top of package.json, above 'name'
`"homepage": "https://yesthisiskendra.github.io/command-center-dash/",`

Add this to the scripts section

````
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build",
    ```
````
