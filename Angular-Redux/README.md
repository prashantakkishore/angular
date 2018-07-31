# Angular-Redux

This is a pure Angular project. Redux is applied on top of this to save state. Redux related code is inside `checkpoints` here are 3 versions of __Redux__.

This project was created very old version of `Angular CLI` so `node_modules` is also packaged in.

Just run `npm start` to start the project.

1. __module_1__ - Basic Redux understanding, as discussed in [Redux-Basics](https://github.com/prashantakkishore/angular/tree/master/Redux-Basics "Redux-Basics") project.

2. __module_2__ - Implements Redux with ng-redux

3. __module_3__ - Redux prefers immutibility of store but still it can be modified later , to enforce immutibility we deepFreeze the store , which is implemented here.

## Screens

![Alt text](screenshots/courses.png?raw=true "Redux Flow")
![Alt text](screenshots/edit_courses.png?raw=true "Redux Flow")

## CourseLibrary

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.0-beta.31.

## Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

### References
https://github.com/hendrikswan/pluralsight-angular-redux
