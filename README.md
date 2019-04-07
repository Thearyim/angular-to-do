# ToDo

### A to do list generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.5.
#### By **Theary Im**  04/04/19

## Specs
1. A user can view all tasks.
2. A user can add a new task.
3. A user can add priority of each task.
2. A user can edit task.
3. A user can mark task as complete and remove task.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Setup/Installation Requirements

-Clone from Github https://github.com/Thearyim/angular-to-do

-Navigate to root project directory in the terminal.

-Input npm install into the terminal to install dependencies.

-Create your own api-keys.ts file in the app folder and populate it with your own firebase credentials.

-Input ng build into the terminal.

-Input ng serve to deploy the server to localhost, or firebase deploy to deploy to your own firebase hosting.

## Firebase Set up
As soon as the project has a dedicated Firebase project to host it, we'll create several configuration files in our project directory that Firebase requires to host a project.

To do this, we'll use the firebase-tools npm package. This package provides additional Firebase capabilities directly from the command line.

We can install it using npm:

$ npm install -g firebase-tools
Once installed, run the login command:

$ firebase login
This will open a browser window prompting you to log into your Google/Firebase account.

Next, initialize Firebase in the root directory of the Angular project you'd like to deploy:

$ firebase init

Your application should now be correctly configured for deployment. You can now deploy with the deploy command:

$ firebase deploy

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Known Bugs
_No known bugs_

## Technologies Used

_Angular, JavaScript ES6, TypeScript, Firebase, Node Package Manager, Bootstrap, Jasmine, Karma_

### License

*MIT License*

Copyright (c) 2019 **_Theary Im_**
