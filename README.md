# Personalized News Hub

> **The Personalized News Platform is a web application that provides users with news articles tailored to their preferences. It uses a public news API to fetch the latest news and applies a recommendation algorithm to filter and display articles based on user preferences. Users can create accounts, set their preferences, and receive a personalized news feed.**

![image](https://github.com/Rajdeep777/Personalized-News-Hub/assets/74129008/ac86d6ee-abf8-44e4-8067-d86e323e763c)

## Features

- User registration and authentication
- User profile management
- User preferences for news categories (e.g., technology, Health, sports)
- Real-time news recommendations based on user preferences
- Integration with a public news API for fetching news articles
- Responsive web design for optimal user experience on various devices

## Our Stack

- React with Vite.
- Nodejs and Express.
- Mongo hosted on ATLAS.
- Bcrypt and JWT for user signin and auth.

## How to build

- run `npm i` in both the client and server folders to install the dependencies.
- make a new file .env in server/ and copy the contents of .example.env
- in UNIX-based systems you can run `cp server/.example.env server/.env` to execute the above action
- fill in the `PORT`, `MONGO_URI` and `JWT` according to your settings
  > NOTE: MONGO_URI could be in local network or MongoDB Atlas URI
- run `npm run dev` inside both the apps to start them in watch mode.
- visit port 3000 in your localhost to see the app live.

