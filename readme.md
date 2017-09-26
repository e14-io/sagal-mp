
# Landing page form MP

## Features

- Webpack development and production environment configuration
- Webpack SCSS configuration
- React Hot loader
- React Router configuration
- React, Redux configuration
- Linting with Airbnb eslint configuration

## Getting Started

Clone Repo

````
git clone
````

npm install dependencies

````
cd landing-mp

npm install
````

### Start development server with hot reloading

````
npm run dev
````

### Linting

For linting i'm using Eslint with Airbnb Eslint configuration

````
npm run lint
````

### Production

Build for production

````
npm run build
````

Start production server

````
npm run start
````

Note: I'm using pm2 for production server, you should install it on server via 'npm install pm2 -g'.
if you don't want to use pm2, just change pm2 with node in package.json file in scripts section.
