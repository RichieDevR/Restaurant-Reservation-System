<h1>Periodic Tables: Restaurant Reservation System</h1>

Welcome! Thanks for using our app. This app is designed to help users manage reservations for their customers.

Some features include:

View all reservations on the Dashboard. The reservations are listed by date, which the user is able to change. Create and edit reservations. Create tables for seating your reservations. Assign a table to a reservation upon arrival at the restaurant. Free a table when the reservation has finished dining and leaves. Search for a reservation by mobile number. Cancel a reservation.

<h3>Installation</h3>

1. Fork and clone this repository.
2. Run `npm install` to install project dependencies.
3. Run `cp ./back-end/.env.sample ./back-end/.env`.
4. Modify `.env` with the following:
 `DATABASEURL=_productionURL  DATABASEURL_DEVELOPMENT=_developmentURL  DATABASEURL_TEST=_testURL  DATABASEURL_PREVIEW=_previewURL  LOG_LEVEL=info`
 
5. Replace "productionURL" with the URL to your production database.
6. Repeat step 5 for the remaining fields, but using the corresponding database URL.
7. Run `cp ./front-end/.env.sample ./front-end/.env`.
8. From inside the backend directory, run `npx knex migrate:latest`.
9. Run `npx knex seed:run`.
10. Finally, go back to the root of the main directory and run `npm run start:dev` to run the application locally.





<h3>Technologies</h3>

The frontend was built using HTML5, CSS3, Javascript, Bootstrap, and React. For the backend, we used Nodejs, Express, and Knex.
