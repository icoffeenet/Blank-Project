**Vite Create**
---
npm create vite . \
**Git Commit**
---
git init \
git add . \
git commit -m '{Comment}' \
**Clone Repo**
---
git clone {Site} . \
**Remove Remote**
---
git remote \
git remote remove {origin} \
**Install Ater Clone**
---
npm install \
**Deploy Project**
---
npm install --save-dev gh-pages \
package.json 
"scripts": { \
    // ...\
    "predeploy": "npm run build", \
    "deploy": "gh-pages -d dist" \
} \

vite.config.js \
base: "/my-project", \
npm run deploy \






npm create vite .

npm run dev
