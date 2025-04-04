# Debugging

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.0.0. Its main goal is for the user to work on troubleshooting some basic errors in Angular:

1. Compilation error when not assigning the correct type
2. Logical error: The homepage should show the name of each user and it's showing `[object Object]`
3. Logical error: When adding a task using the "Add task" button, the new task does not appear

_Tips:_
- _You can use the browser developer tool to troubleshoot logical errors, setting breakpoints in the Sources tab_
- _It's a good idea to install the Angular DevTools browser extension to get more details about the application in an easier way_

## Development server

Ideally running `ng serve` will start a dev server to use the app, but given that the goal of this project is to understand how to debug and fix errors, first it won't compile. Once you fix the first error, you'll be able to navigate to `http://localhost:4200/` and check that the app is running. The application will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Further help

- To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
- You can read more about Angular DevTools [here](https://angular.dev/tools/devtools).
