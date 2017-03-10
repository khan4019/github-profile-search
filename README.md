# Profile
The goal of this challenge is to see whether you can do some basic front end development. You don’t have to know angular2 or material design or typescript. 


## Getting started
1.  Make sure you have node  and npm installed
1.  If you don't have angular cli install, run `npm install -g @angular/cli`
1.  Fork this repository
2.	Run `npm install`
3.	Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## General Guideline
1.  Feel free to use internet
2.  You don't have to finish both level. 
3.  We recommend you to spend two hours and submit as much as you can
4.  The project has angular material design incorporated. Feel free to use any component . 

Run `ng generate component component-name` to generate a new component. You can also use `ng generate service service-name` to create a service.


# Challenge-Level-1: Fetch data and display
1.	Github user api: `https://api.github.com/search/users?q=eric` takes a search string to search users in github. The search string could be passed as parameter q
4.	Create a textbox in the main component under src\app\main to take user name and search that user name in github by using the above mentioned api
5.	From the search result display the total number of github user in `total_count`
6.  Display first 10 users in the search result
7.  Feel free to use material design (already included in the repository)


# Challenge-Level-2: Create a new component and route
4.	The goal of this level is to create a component to display user profile detail
1.  Allow user to navigate user profile detail from main component. 
5.	Create a route in the src/app/app.routes.ts



## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
