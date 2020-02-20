# Angular8CrudRestAPI

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.6.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).



step 1>npm install bootstrap

Step 2> angular.json
"styles": [
            "node_modules/bootstrap/dist/css/bootstrap.min.css",
            "src/styles.css"
          ]

Step 3>ng g c employee-create

	ng g c employee-edit

	ng g c employee-list

Step 4>Install JSON server in our project, run the following command in Angular CLI.

npm i json-server --save

Step 5>mkdir server && cd server

Step 6>Once the db.json file is created then add some data in it.

{
  "employees": [{
    "id": 1,
    "name": "Tony Stark",
    "email": "tony@mcu.com",
    "phone": "001-123-4567"
  }, {
    "id": 2,
    "name": "Black Widow",
    "email": "black-widow@mcu.com",
    "phone": "001-123-4568"
  }]
}
After that run the following command to run the JSON server.

json-server --watch server/db.json

You can check your local db.json file on this URL http://localhost:3000/employees.

step 7>ng g cl shared/Employee

Step 8>ng g s shared/rest-api
# Angular8CrudRestAPI
