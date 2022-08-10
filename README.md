                    React App Without create-react-app


STEPS

    - Install Node.js

    - Create a package.json file using
            npm init 

    - Install webpack dependencies
            npm i --save-dev webpack webpack-cli webpack-dev-server

    - Install the Babel dependencies
            npm i --save-dev babel-loader @babel/preset-env @babel/core 
            @babel/plugin-transform-runtime 
            @babel/preset-react 
            babel-eslint 
            @babel/runtime
            @babel/cli

    - Install required Linters and path
            npm i --save-dev eslint eslint-config-airbnb-base 
            eslint-plugin-jest 
            eslint-config-prettier
            path

    - Install react and react-dom
            npm i react react-dom
    
    - Create folders public and src
            inside of it create files index.html, App.js, index.js

    - Create webpack.config.js file

    - Create .babelrc file

    - Update package.json file
            add the start and build scripts to it

    - Run 
            npm run build

    - Run 
            npm start
