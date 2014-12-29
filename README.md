# The seed for AngularJS with CoffeeScript apps

This project is an application skeleton for a typical 
[AngularJS](http://angularjs.org/) web app with 
[CoffeeScript](http://coffeescript.org). It is based on the 
[angular-seed](https://github.com/angular/angular-seed) so if you are looking 
informations about angular-seed itself read orginal 
[README.md](https://github.com/angular/angular-seed/blob/master/README.md)

angular-seed-coffeescript is developed to be as similar as possible to 
angular-seed to be easy to update in the future.

# Compile CoffeScript
In order to compile `*.coffee`files run:
```
npm run coffee
```

# Changes compared with angular-seed
* [PhantomJS](http://phantomjs.org/) as environment for running unit tests 
  instead of Chrome. That gives you ability to test your application also in 
  cloud based IDE like Cloud9.
* Up-to-date Karma test runner with Jasmine 2.1

## @TODO
* E2E tests with CoffeeScript