# MyAngularLearning

### Angular

#### To develop an Angular Project we need the below stuff
1. node
	- This can be downloaded here https://nodejs.org/en/download/
	- Use this command to make sure the node has been installed ## node --version
2. npm
	- This has been included with node. so we no need separate installation
  - Use this command to make sure npm has been installed ## npm --version
3. Angular CLI
  - use this command  ## npm install -g @angular/cli
  - To check the version use this command ## ng v <Project Name>
4. Once we installed all these three we are ready to create a new project in Angular
5. Use this command to create a new angular app ## ng new <project name>
6. This will ask a few questions about do you need routing and which file extension you are going to use for CSS. Provide your choice and press enter.
	- This will install required npm packages and dependencies that angular requires
7. Navigate to the folder which we created now
8. Use this command to edit/add the files using Visual Studio code ## code. (. means current folder)
9. To run the angular app use this command ## ng serve
10. Once the system is set up the local web server will display the URL to access our application like "http://localhost:4200/"
11. use this URL
#### Folder structure

1. e2e - This is where we will add our end-to-end test. Since from Angular 12 version this has been deprecated.
2. node_modules - This is where we store all third-party libraries that support our application. When we build the application this has been converted to a bundle and deployed along with the application. 
3. src - This is where we have our actual source codes. 
	- Inside this folder, we have an "app" folder which has a set of files. every application needs at least one module and component
	- assets - where we store static assets for our application like images, icons or text file
	- environments - This is where we have configuration for each environment
	## Files
	1. Index.html - This is the file being used to render all our components. this will be updated during run time.
	2. main.ts - This is starting point for our application
	3. style.css - This is where we will add global CSS tags

