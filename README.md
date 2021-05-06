# This is your readme
You are required to fill it in with documentation similar to that found in the Sequelize example for the course as part of your final project.

sample: https://github.com/Berniez88/finalproject377 (Links to an external site.)
Link to the Heroku instance where your application is live and running
[Heroku](https://dashboard.heroku.com/apps/powerful-plateau-48422)
Title of your project
# Animal Shelters and Adoptions in Maryland
Description of your project
## Description
Over the past year, there has been an uptick in the number of people looking to adopt animals with one article from The Washington Post reporting that some shelters have seen double the adoption rate than pre-COVID. Our application aims to centralize the animals of many shelter databases into a single one as well as provide information about the associated costs of caring for that animal. In doing so, we hope to get more eyes on these animals and reduce the information incognizance and overload traditionally felt when going through this process. 
![image](insert image of screenshot of homepage)

Description of target browsers (iOS? Android? Which ones? Which versions?)
## Target Browsers
* Desktop Users
* Macbook Pro 13/15 
* IOS Tablet
* Andriod Tablet   

Link to Developer Manual
## Link
* [Developer Manual]()
# Developer Manual
## How to install application and all dependencies
1. Clone this repository through Github Desktop or through Terminal.
2. Open repository in VSCode Terminal or Terminal application.
3. type ```npm install``` into terminal window and run.
4. The application should now be set to use.

## How to run application on a server
1. Open repository in VSCode terminal or Terminal application.
2. Run ```npm start```. There should be no errors.
3. In a web browser, go to url: ```http://localhost:3000/```.

## To run tests for software
The are no prewritten tests in the source repository, but you can use Cypress to run your own written tests.
1. Open two terminals and make sure you are in the main project directory
2. In the first terminal, run ```npm start```.
3. In the second terminal run ```npm test```.

## Server application APIs
```/shelters``` - API route for Shelter data.
* GET - Logs to console response query from URL. returns shelter data or returns response 'no results found' if shelters length is less than 0.
* POST - obtains shelter name from request body to fetch url. fetch data json from PlanetTerp grades API and returns JSON response. 
* PUT - returns response 'Got a PUT request at /api'.

```/animals``` - API route for Animal and Shelter data.
* GET - Logs to console response query from URL. returns response 'Got a GET request from /api'.
* POST - obtains course name from request body to fetch url. fetch data json from PlanetTerp grades API and returns JSON response. 
* PUT - returns response 'Got a PUT request at /api'.

```/applicants``` - API route for Animal and Shelter data.
* GET - Logs to console response query from URL. returns response 'Got a GET request from /api'.
* POST - obtains course name from request body to fetch url. fetch data json from PlanetTerp grades API and returns JSON response. 
* PUT - returns response 'Got a PUT request at /api'.

```/pending``` - API route for Animal and Shelter data.
* GET - Logs to console response query from URL. returns response 'Got a GET request from /api'.
* POST - obtains course name from request body to fetch url. fetch data json from PlanetTerp grades API and returns JSON response. 
* PUT - returns response 'Got a PUT request at /api'.

```/types``` - API route for Animal and Shelter data.
* GET - Logs to console response query from URL. returns response 'Got a GET request from /api'.
* POST - obtains course name from request body to fetch url. fetch data json from PlanetTerp grades API and returns JSON response. 
* PUT - returns response 'Got a PUT request at /api'.

```/employees``` - API route for Animal and Shelter data.
* GET - Logs to console response query from URL. returns response 'Got a GET request from /api'.
* POST - obtains course name from request body to fetch url. fetch data json from PlanetTerp grades API and returns JSON response. 
* PUT - returns response 'Got a PUT request at /api'.

```/websites``` - API route for Animal and Shelter data.
* GET - Logs to console response query from URL. returns response 'Got a GET request from /api'.
* POST - obtains course name from request body to fetch url. fetch data json from PlanetTerp grades API and returns JSON response. 
* PUT - returns response 'Got a PUT request at /api'.

```/table/data``` - 
* GET - Logs to console response query from URL. returns response 'Got a GET request from /api'.
* POST - obtains course name from request body to fetch url. fetch data json from PlanetTerp grades API and returns JSON response. 
* PUT - returns response 'Got a PUT request at /api'.

```/map/data``` - API route for Animal and Shelter data.
* GET - Logs to console response query from URL. returns response 'Got a GET request from /api'.
* POST - obtains course name from request body to fetch url. fetch data json from PlanetTerp grades API and returns JSON response. 
* PUT - returns response 'Got a PUT request at /api'.

```/custom``` - API route for Animal and Shelter data.
* GET - Logs to console response query from URL. returns response 'Got a GET request from /api'.
* POST - obtains course name from request body to fetch url. fetch data json from PlanetTerp grades API and returns JSON response. 
* PUT - returns response 'Got a PUT request at /api'.

## Known Bugs & Future Development
### Bugs: None known


### Future Development: 
* Implement searchbar feature
* Add more ways to filter for animals/shelters
* Include automatic update of new animals/shelters







### How to use Markdown
Markdown is a text notation system used in Discord, Whatsapp and similar to structure pages without writing HTML at all. You'll be using it for your documentation.
* [Markdown guide](https://www.markdownguide.org/cheat-sheet/)