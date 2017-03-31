# Wide World Travel Guides

#### Part 3: Routing

This project builds off of [Wide World Travel factory exercise](./MF_WIDE_WORLD_TRAVEL.md)

## Instructions

You are going to use `ngRoute` to load the HTML for diplaying guide books from a partial into `index.html`

1. Include the separate `angular-route` provider into `index.html`: `<script src="my-path-to-angular-route.min.js"></script>`
1. Inject it into your app as a dependency: `var myApp = angular.module("MyAppName", ['ngRoute']);`
1. Setup routing in app.js using the config method: `app.config(['$routeProvider'....etc`
1. Remember to remove `ng-controller` references from index.html. Angular-route will now handle binding controllers to partials.
