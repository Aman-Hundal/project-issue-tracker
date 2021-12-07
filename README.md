# Project Issue Tracker
A Project Management App intended for internal use within an organization. Users can create projects, manage team members, and create and track tickets and tasks on specific projects they are working on. Users are provided with real time data on the status of their projects. 

This project is built with React in the front-end and ruby on rails in the back-end. PostgreSQL is used as database to persist all data. Among other tech stacks used are material ui, storybook, reactstrap, react-router, chartjs-2, react-slack-chat.

## Setup

1. Create the `.env` by using `.env.example` as a reference: `cp .env.example .env`
2. Install fron-end dependencies with `npm install` (inside the client folder)
3. Install back-end dependencies with `bundle install` (inside the backend folder)
4. Run rake db:migrate and rake db:seed to setup database with Rails

Finally, retrieve a webhook key from slack by creating a workspace and put inside a .env file based on the .env_example provided.

## Running Webpack Development Server

```sh
npm start
```

## Running Rails Server

```sh
rails s
```

## Running Jest Test Framework

```sh
npm test
```

## Running Storybook Visual Testbed

```sh
npm run storybook
```

## Final Product

!["Screenshot of the Project Dashboard"](https://github.com/lateefazeez/project-issue-tracker/blob/master/client/src/images/Screen%20Shot%202021-12-01%20at%2012.32.40%20PM.png?raw=true)

!["Screenshot of the Project Dashboard 2"](https://github.com/lateefazeez/project-issue-tracker/blob/master/client/src/images/Screen%20Shot%202021-12-01%20at%2012.32.54%20PM.png?raw=true)

!["Screenshot of the Ticket Page"](https://github.com/lateefazeez/project-issue-tracker/blob/master/client/src/images/Screen%20Shot%202021-12-01%20at%2012.35.23%20PM.png?raw=true)

!["Screenshot of the Ticket Page2"](https://github.com/lateefazeez/project-issue-tracker/blob/master/client/src/images/Screen%20Shot%202021-12-01%20at%2012.35.39%20PM.png?raw=true)

!["Screenshot of the Ticket Page3"](https://github.com/lateefazeez/project-issue-tracker/blob/master/client/src/images/Screen%20Shot%202021-12-01%20at%2012.35.49%20PM.png?raw=true)

!["Screenshot of Ticket Creation"](https://github.com/lateefazeez/project-issue-tracker/blob/master/client/src/images/Screen%20Shot%202021-12-01%20at%2012.36.13%20PM.png?raw=true)

!["Screenshot of Team Member Addition"](https://github.com/lateefazeez/project-issue-tracker/blob/master/client/src/images/Screen%20Shot%202021-12-01%20at%2012.36.21%20PM.png?raw=true)

!["Screenshot of New Task Addition"](https://github.com/lateefazeez/project-issue-tracker/blob/master/client/src/images/Screen%20Shot%202021-12-01%20at%2012.36.25%20PM.png?raw=true)



## Dependencies

- Axios
- Node 5.10.x or above
- React 16.4.x or above
- Rails 6.0.0 or above
- React-Material UI
- Reactstrap
- React-slack-chat
- Node-Sass
- React Testing Library
- Storybook Testing App
- Cypress
- Chartjs-2
