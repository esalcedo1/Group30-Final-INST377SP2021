# This is your readme
You are required to fill it in with documentation similar to that found in the Sequelize example for the course as part of your final project.

sample: https://github.com/Berniez88/finalproject377 (Links to an external site.)

[Heroku](https://dashboard.heroku.com/apps/powerful-plateau-48422)
# Animal Shelters and Adoptions in Maryland
## Description
Over the past year, there has been an uptick in the number of people looking to adopt animals with one article from The Washington Post reporting that some shelters have seen double the adoption rate than pre-COVID. Our application aims to centralize the animals of many shelter databases into a single one as well as provide information about the associated costs of caring for that animal. In doing so, we hope to get more eyes on these animals and reduce the information incognizance and overload traditionally felt when going through this process. Our target audience is aimed towards employees & adminisrators of these animal shelters so they can view each shelter and their data.
![image](insert image of screenshot of homepage)

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
* POST - submits the shelter data to the database of newShelters.
* PUT - updates shelter database with selected inputs.
* Delete - deletes item in shelter database and returns 'Successfully Deleted'

```/animals``` - API route for Animal data.
* GET - requests data from animal database and gets animal ID.
* PUT - updates animals database and returns 'Animal Successfully Updated'.

```/applicants``` - API route for Applicant data.
* GET - Requests data from applicant database along with their IDs.
* POST - obtains course name from request body to fetch url. fetch data json from PlanetTerp grades API and returns JSON response. 
* PUT - updates applicants with their information from database and returns 'Successfully Updated'.

```/pending``` - API route for Pending adoptions data.
* GET - requests data from pending adoptions database. Gets the ID as well.

```/types``` - API route for Animal types data.
* GET - Request data from animal types database and gets the species ID.

```/employees``` - API route for Employee data.
* GET - Requests data from employee data base and returns employee ID.

```/websites``` - API route for Websites data.
* GET - Requests data from website database and returns website ID.

```/table/data``` - API route for table data.
* GET - Requests custom sql query in the sequlize database. 

```/map/data``` - API route for map data.
* GET - requests data using custom query from sequelize database .

```/custom``` - API route for custom data.
* GET - requests data from sequlize database using a custom query.

## Known Bugs & Future Development
### Bugs: None known


### Future Development: 
* Implement searchbar feature
* Add more ways to filter for animals/shelters
* Include automatic update of new animals/shelters

### How to use Markdown
Markdown is a text notation system used in Discord, Whatsapp and similar to structure pages without writing HTML at all. You'll be using it for your documentation.
* [Markdown guide](https://www.markdownguide.org/cheat-sheet/)