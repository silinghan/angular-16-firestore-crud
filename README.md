# Angular16FirestoreCrud

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Technology
Angular 16
firebase 9
@angular/fire 7
rxjs 7

# Setup the Firebase Project
Please visit following tutorial for setting up project on Firebase

Console:
[How to Integrate Firebase into Angular 16](https://www.bezkoder.com/integrate-firebase-angular-16/)

# Setup Angular 16 Project
Let’s open cmd and use Angular CLI to create a new Angular Project as following command:

ng new angular-16-firestore-crud

? Would you like to add Angular routing? Yes
? Which stylesheet format would you like to use? CSS
We also need to generate some Components and a Service:

ng g s services/tutorial

ng g c components/add-tutorial
ng g c components/tutorial-details
ng g c components/tutorials-list

ng g class models/tutorial --type=model

Now you can see that our project directory structure looks like this.