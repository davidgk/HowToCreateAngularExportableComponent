# Creation and use of native component with angular 6

This exercise is based upon post:
https://medium.com/@nikolasleblanc/building-an-angular-4-component-library-with-the-angular-cli-and-ng-packagr-53b2ade0701e

## Create proyect

Create two proyects, one for create the component, one to use it once it was created
Rely in bibliries I'm using here, in the original post some of them are deprecated or changed.


## create the component as simple as post Said.
It's just an experiment, so for know just learn how to create a new component, follow from here up 
to post title:'Let's share the love'

## Libraries to be exported need some change:

In your component change package json in this way :

´´´

{
  "name": "my-sandbox",
  "version": "0.0.0",
  "license": "MIT",
  "scripts": {
    "ng": "ng",
    "start": "ng serve",
    "build": "ng build",
    "test": "ng test",
    "lint": "ng lint",
    "e2e": "ng e2e",
    "packagr": "ng-packagr -p ng-package.json"
  },
  "private": false,
  "peerDependencies": {
    "@angular/animations": "^6.0.0",
    "@angular/common": "^6.0.0",
    "@angular/compiler": "^6.0.0",
    "@angular/core": "^6.0.0",
    "@angular/forms": "^6.0.0",
    "@angular/http": "^6.0.0",
    "@angular/platform-browser": "^6.0.0",
    "@angular/platform-browser-dynamic": "^6.0.0",
    "@angular/router": "^6.0.0",
    "core-js": "^2.4.1",
    "rxjs": "^6.0.0",
    "zone.js": "^0.8.14"
  },
  "dependencies": {
  },
  "devDependencies": {
    "@angular/cli": "^1.6.0",
    "@angular/compiler-cli": "^6.0.0",
    "@angular/language-service": "^6.0.0",
    "@types/jasmine": "~2.5.53",
    "@types/jasminewd2": "~2.0.2",
    "@types/node": "~6.0.60",
    "codelyzer": "^4.4.2",
    "jasmine-core": "~2.6.2",
    "jasmine-spec-reporter": "~4.1.0",
    "karma": "~1.7.0",
    "karma-chrome-launcher": "~2.1.1",
    "karma-cli": "~1.0.1",
    "karma-coverage-istanbul-reporter": "^1.2.1",
    "karma-jasmine": "~1.1.0",
    "karma-jasmine-html-reporter": "^0.2.2",
    "ng-packagr": "^4.0.0",
    "protractor": "~5.1.2",
    "ts-node": "~3.2.0",
    "tslint": "~5.7.0",
    "tslib": "^1.9.0",
    "tsickle": "^0.27.3",
    "typescript": "~2.7.0"
  }
}


´´´

Now you are in conditions to follow the post.



	
