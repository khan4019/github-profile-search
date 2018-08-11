# Test task
The goal of this challenge is to see whether you can do some basic front end development.


## Getting started
1.  Make sure you have node  and npm installed
1.  Fork this repository 
1.  If you do not have latest angular cli installed, run `npm install -g @angular/cli`
2.	Run `npm install`
3.	Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## General Guideline
1.  Feel free to use internet
3.  We recommend you to spend maximum three hours and submit as much as you can
2.  The project has angular material design incorporated. Feel free to use it 
1.  Before start coding 
    *   Create a branch by using your full name
    *   When you are done, send a pull request



# Task (Level 1)
I am giving you an api https://api.github.com/search/users?q=eric This api takes a query parameter name "q" and passes query string to server. Server returns bunch of users. Now I want you to create a input text box and button so that you can type anything on the text box and hit on the button to retrieve data from the given api. Upon retrieval display total_count and first 10 users in the search result.

**Steps**
1.	Github user api: `https://api.github.com/search/users?q=eric` takes a search string to search users in github. The search string could be passed as parameter q
4.	Create a textbox in the main component under src\app\main to take user by using the above mentioned api
5.	From the search result display the total number of github users in `total_count`
6.  Display first 10 users in the search result

# Task (Level 2)
Convert each user profile as a router link so that upon clicking on each user profile you will navigate to a route that has "login" property in the route. Pass user.login as route parameter. Create a separate component where you will read the route parameter and then fetch data for that user by using this api https://api.github.com/users/eric . Please Notice that last part of this api is the user.login (the route parameter that you have passed). Finally display user image and few other information in the component

# Task (Level 3)
Use any charting framework that you can find and then create a simple bar chart to display number of followers of first 10 users

## Further help
1.  Feel free to ask google or the person sent you this challenge

