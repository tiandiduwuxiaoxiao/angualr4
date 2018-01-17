# Install Jquery
Notice:check the version of jquery via below command:
  ```
  npm view jquery dist-tags
  ```

1.install jquery via npm with below a few steps:

First: Install jQuery, the actual library
  ```
  npm install jquery --save
  ```

Second: Install jQuery TypeScript autocomplete
  ```
  npm install @types/jquery --save-dev
  ```

Finally: Go to the ./angular-cli.json file at the root of your Angular CLI project folder, 
and find the scripts: [] property, add this inside it:
  ```
  "../node_modules/jquery/dist/jquery.min.js"
  ```
