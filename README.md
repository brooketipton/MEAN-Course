# MEAN-Course
Angular - NodeJS - MongoDB - Express

To initialize on a local server, run ng serve. 
----
MUST BE IN PROJECT ROOT DIRECTORY TO RUN ABOVE COMMAND

# NOTES
----
- Package.json includes dependencies
- angular.json is for angular cli
- node modules stores the dependencies
- to create new node modules folder, run npm install inside the project root directory
- app folder contains the actual meat of the angular application
- angular uses components
- within the app.component.ts file, you will add your seperate components, and then the root component is included in the app.html file
- app-root tag relates to the angular application we are building
- app module file defines the features our application has
- bootstrap array in module.ts defines the component to display, multi page apps are nested within this one usually
- main.ts starts our angular application in the browser
- bootstrap module references our app modules, starts that module through angular
----
COMPONENTS
- seperate re-usable components 
- you can define the HTML for a component within the TS file, but it is best practice to go ahead and create its own component.html file for readability and seperation purposes
- IMPORTANT - to register a new component, you have to add it to the module.ts file at the top level spplication you are currently in 
- property binding is for use directly on elements [value]="something"
- string interpolation {{ property }} for between opening and closing tags 
- local referece - # postInput will create a reference to any property to be passed into a type script method
- two way binding, combines the #postInput and property binding, combines setting and reading :)
- how to do two way binding! - [(ngModel)]=""
- two way binding is included in the forms module

