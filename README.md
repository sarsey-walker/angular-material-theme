# AngularMaterialTheming

The idea with this project is learn Angular Theming, how to change from CSS to SCSS and how to migrate from an Angular earlier version to a newer version as well as make some tests with git.

As always, this project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.1.2.

To run this project install node LTS, install `@angular/cli` globaly, clone this repo and run `npm ci` to install all the packages.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Troubleshoot

In order to manage to run this version, I had to modify `/etc/ssl/openssl.cnf` oin my fedora.

I un-commented this lines

```
##[provider_sect]
##default = default_sect
##legacy = legacy_sect
##
##[default_sect]
##activate = 1
##
##[legacy_sect]
##activate = 1
```

You may have to exclude the folder `node_modules` and run `npm install` again, and/or use `--openssl-legacy-provider`

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
