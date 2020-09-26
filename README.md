(View Raw will give you the markdown that you can copy to your repos!)


![MIT LICENSE](https://img.shields.io/github/license/scottbromander/the_marketplace.svg?style=flat-square)
![REPO SIZE](https://img.shields.io/github/repo-size/scottbromander/the_marketplace.svg?style=flat-square)
![TOP_LANGUAGE](https://img.shields.io/github/languages/top/scottbromander/the_marketplace.svg?style=flat-square)
![FORKS](https://img.shields.io/github/forks/scottbromander/the_marketplace.svg?style=social)

# PowerliftsDB

## Description

_Duration: 2 Week Sprint_

I developed PowerliftsDB to address the problem of weight-lifters being able to conveninently log stats for their lifts. Weight lifters often use small notebooks to record their progress and reference in order to gauge what their next work-out should look like. PowerliftsDB allows users to record and review all of their stats in one place, as well as allowing users to view other users' stats. Users can also view a line graph generated from their history with a certain exercise at different rep ranges.

### Prerequisites

You will need [Node.js](https://nodejs.org/en/) and the node package manager to install dependencies for this app.
You will also need [PostgresQL](https://www.postgresql.org/) to run the database for this app.

## Installation

1. Fork this repository and Clone using `git clone <repo-url.git>`
2. Install any dependencies by navigating to the project directory and using `npm install` in terminal.
3. Create a database named `prime-app`,
4. The queries in the `database.sql` file are set up to create the table required for this project.
   The project is built on [Postgres](https://www.postgresql.org/download/), so you will need to make sure to have that installed.
   I recommend using Postico to run the CREATE TABLE queries, as this is what I used.
7. Run `npm run server` in your terminal
8. Run `npm run client` in your terminal -- the app should automatically open in your browser.

## Usage

1. Prospective users can register an account on the landing page. Existing users can click the "Login" button to be directed to the login page.
2. Once logged in, users will be directed to their home-page. If the user has stats logged in the database, they will see information here regarding their max efforts for different exercises.
3. If a user wishes to log stats, they can click the "Quick Log" link in the top right nav-bar.
4. Once on the Quick-Log page, the user can complete the form and submit their stats.
5. Navigating to the "Feed" page will allow the user to view a chronological list of all lifts.
6. For any exercise the user has logged, a card will appear on the home-page allowing the user to see all of their entries for this exercise. The user can also view a line-graph representing their progress with a lift by clicking the "View [exercise] Metrics" button and selectinga rep-range from the drop-down menu.

## Built With

I built this app using React-Redux, sagas, PostgresQL, node, express, and Material-UI. I scoped the app using dbdesigner, moqups, and trello boards.

## Acknowledgement
Thanks to [Prime Digital Academy](www.primeacademy.io) who gave me the training and guidance to complete this project. Special thanks to [Dane Smith](https://github.com/DoctorHowser), my instructor!

## Support
If you have suggestions or issues, please email [emerson.aagaard@gmail.com](emerson.aagaard@gmail.com)!
