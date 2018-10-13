# Timebox

Seamless email client compatible with Gmail

## Team
- Kirk Rohani

## Roadmap

View the project roadmap [here]()



# Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)
    1. [Installing Dependencies](#installing-dependencies)
    1. [Tasks](#tasks)

## Usage

Click this [link]() and login with your Gmail acount to get started!

## Requirements



## Development

### Installing System Dependencies

```
brew install yarn
brew install postgresql
```

We chose to use Yarn as a replacement for npm. It's faster and *guarantees* consistency -- as we deploy in various environments, we don't run the risk of slight variations in what gets installed.

### Install Project Dependencies

```
yarn global add grunt-cli knex eslint
```


## Database Initialization

IMPORTANT: ensure `postgres` is running before performing these steps.

### Database Creation:




### Run Migrations & Data Seeds



## Running the App

To run webpack build: `yarn build`

To run server: `yarn start`

To run tests: `yarn test`

To run your redis server for the session store `redis-server`


