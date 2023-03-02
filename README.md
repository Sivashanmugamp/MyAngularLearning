# MyAngularLearning

### Angular

#### To develop an Angular Project we need below stuff
1. node
	- This can be downloaded here https://nodejs.org/en/download/
	- use this command to make sure node has been installed ## node --version
2. npm
	- This has been included with node. so we no need separate installation
  - use this command to make sure npm has been installed ## npm --version
3. Angular CLI
  - use this command  ## npm install -g @angular/cli
  - to check the version use this command ## ng v
4. Once we installed all these three we are ready to create new project in Angular
5. use this command to create a new angular app ## ng new <project name>
6. This will ask few questions about do you need routing and which file extenstion you are going to use for CSS. Provide your choise and press enter.
7. Navigate to the folder which we created now
8. Use this command to edit/add the fils using visual studio code ## code .(. means current folder)
9. To run the angular app use this command ## ng serve
10. Once system set up the local web server which will display the url to access our application like "http://localhost:4200/"
11. use this url
#### Folder structure

1. e2e - this is where we will add our end to end test. Since from Angular 12 version this has been depricated.
2. node_modules - this is where we store all third party libraries which supports to our application. When we build the application this has been converted to bundle and deployed along with application. 
3. src - This is where we have our actual source codes. 
	- inside this folder we have "app" folder which has set of files. every application need atleast one module and component
	- assets - where we store static assets for our application like image, icon or text file
	- environments - this is where we have configuration for each environments
	## Files
	1. Index.html - this is the file being used to render all our components. this will be updated during run time.
	2. main.ts - this is starting point for our application
	3. style.css - this is where we will add global css tags

