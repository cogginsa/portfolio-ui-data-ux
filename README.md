# PortfolioOfUi

This project uses [Angular CLI](https://github.com/angular/angular-cli) version 11.0.9

## How to deploy (github pages)

run command
`ng build --prod --output-path docs --base-href /coggins-ui-portfolio/`

After build, it will generate a /docs directory
copy the index.html and rename to 404.html

push this to github and the deployment process will automatically start (main)


## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
