# SpaceX Booking App

🚀 [Apollo tutorial](http://apollographql.com/docs/tutorial/introduction.html): building an interactive app for reserving a seat on an upcoming SpaceX launch – with authentication, pagination, testing, and more.

Built on top of the tutorial [starter pack](https://github.com/apollographql/fullstack-tutorial).

## Installation

Clone the repository, install dependencies and we are ready to run the server! For doing so, run the following commands on a terminal window, located in the directory you want to store the project.

```
git clone https://github.com/celiagomezdev/spacex-booking-app.git
cd spacex-booking-app/server && npm i && npm start
```

Once the server is running, you should be able to access to the GraphQL Playground at `http://localhost:4000/`, where you can test different queries like:

```graphql
query GetLaunches {
  launches(pageSize: 3) {
    launches {
      id
      mission {
        name
      }
    }
  }
}
```
