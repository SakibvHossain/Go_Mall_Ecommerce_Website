### Greating an Angular Project:  
*  Angular provides a command-line tool to generate a project
*  Generates the starter files to help you bootstrap your project  
Command Line Interface [View](http://cli.angular.io/).

### Angular CLI:  
`npm install -g @angular/cli@14.0.7`

### To create project
`npm new <your-project-name>`
`npm new Go-Mall-Ecommerce`

### Running the application
`ng serve` By default application will listen on port `4200` which means `http://localhost:4200`
`ng serve open` it does the same as above also it opens a web browser

### But you don't want to run application on port 4200
`ng serve --port 5200` now your application will listen on port 5200 which means `http://localhost:5200` 
`ng serve --port 5200 --open` it does the same as above but also it opens a web browser.

### Understand project files
`angular.json` is an angular workspace configuration List of execution targets.  
`node_modules` is Local repo of node modules.  
`package.json` is project meta data. List of node dependencies.  
`app` which contains app components, templates etc.  
`assets` which contains image,etc.  
`environments` is Profils for environment: dev, test, prod etc.  
`index.html` is the main launch page of your application.  
`polyfills.ts` adds supports for different browser versions.  
`test.ts` unit test cases.  
`tsconfig.json` typesript compiler configs.  

  
### ✖ Package install failed, see above. The Schematic workflow failed. See above.
If your have the same issue while building the project. Then your Node.js isn't install perfectly. That's for you got the error. to fix this issue you need to run the following command: `npm install` after this you're required file will be installed. Then just run the application `ng serve`.


### It's a lots of pain better work with docker to run others project with there own things :D
