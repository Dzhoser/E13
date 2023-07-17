# E13
E13 module

Commands
 npm init
 mkdir src
 cd src
 mkdir js
 cd ..
 npm install webpack webpack-cli webpack-dev-server path --save-dev
 npm install html-webpack-plugin
 npm run dev
 npm install --save-dev webpack-merge
 
 npm install -g json-server
 touch db.json
 json-server --watch db.json
 
 npm install husky --save-dev
 npm pkg set scripts.prepare="husky install"
 npm run prepare
 
 npx husky add .husky/pre-commit "npm run lint"        
 git add .husky/pre-commit
 npm install -g eslint
 npm init @eslint/config
 git commit -m "test commit"