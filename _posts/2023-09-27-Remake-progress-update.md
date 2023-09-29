---
layout: post
---
After consideration we've come to the conclusion of using `next.js` as the framework for the admin panel,
`go` for the backend api, `mongodb` as database for the remake of the backend.

`next.js` is a fast, easy to use and react-based framework and will also share the same look as the app.
It gives the oppertunity to integrate almost anything into it which is a huge bonus
when adding features in the future.

`go` was chosen for the backend api for it's very simple nature of setting up api backends with minimal effort
while also being blazingly fast and we're using it in a different course so everyone is somewhat familiar
with the language.

Since the previous database used `mongodb` we kept it for simplicity and also convenience since it's
very simple to store and return json from the database.

We've now had a couple days of remaking the backend and we've gotten a lot done on the admin webside part
of the remake.
Some potential candidates have been found for the registration plate reading replacement but they are still under
scrutiny.
The database is all set up and works as expected when it comes to sharding and an effort is now made to integrate
it with the current api backend.
We've had some issues getting documentation on what endpoints are needed for the backend but we're making
progress with the known endpoints.
