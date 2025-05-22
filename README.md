git init\
git add .
git commit -m '{Name}'
##################################################
git clone
##################################################
git remote
git remote remove {origin}
##################################################
npm install
##################################################
npm install --save-dev gh-pages
## package.json ##
"scripts": {    
    // ...
    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist"
}

## vite.config.js ##
base: "/my-project",
npm run deploy






npm create vite .

npm run dev
