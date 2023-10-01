---
layout: post
---
After consideration we've come to the conclusion of using `next.js` as the framework for the admin panel,
`go` for the backend api, `mongodb` as database for the remake of the backend.

`next.js` is a fast and easy to use react-based framework. It was chosen due to its routing capabilities and
development similarities to `react-expo`, which the app is built with. It also has a lot of built in features
that makes it easy to get started. We have chosen to use a component library called `material-ui`,  
to keep the design process as easy and fast as possible. Compared to the previous solution, a self-made
system with `next-js` and `material-ui` is a lot easier to maintain and develop in-house without licensing fees.

`go` was chosen for the backend api for it's very simple nature of setting up api backends with minimal effort
while also being blazing fast and we're using it in a different course so everyone is somewhat familiar
with the language.

Since the previous database used `mongodb` we kept it for simplicity and also convenience since it's
very simple to store and return json from the database.

We've now had a couple days of remaking the backend and we've gotten a lot done on the admin website part
of the remake.
Some potential candidates have been found for the registration plate reading replacement but they are still under
scrutiny.
The database is all set up and works as expected when it comes to sharding and an effort is now made to integrate
it with the current api backend.
We've had some issues getting documentation on what endpoints are needed for the backend but we're making
progress with the known endpoints.
