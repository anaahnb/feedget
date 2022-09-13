# Feedget

This project is a widget that can be used in web and mobile applications to receive feedback from users. Developed on **Next Level Week Return** event by Rocketseat

## Technologies

- [ReactJS](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.io/)
- [Vitejs](https://vitejs.dev/)
- [Express](https://expressjs.com/)
- [Prisma](https://www.prisma.io/)

## Installation

### Requirements

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/) or [npm](https://www.npmjs.com/package/npm)
- [Expo CLI](https://docs.expo.dev/workflow/expo-cli)

**Clone the project and access the folder**

```bash
git clone https://github.com/EliasGcf/feedget.git && cd feedget
```

**Follow the steps below**

### Server

```bash
# From the project root folder access the 'server' folder
$ cd server

# Install the dependencies
$ npm install

# Make a copy of '.env.example' to '.env'
# and set with YOUR environment variables.
$ cp .env.example .env

# With a PostgreSQL running, run the migrations
$ npx prisma migrate dev

# Start the server
$ npm run dev
```

### Web

**Make sure to have the server running**

```bash
# From the project root folder access the 'web' folder
$ cd web

# Install the dependencies
$ npm install

# Make a copy of '.env.local.example' to '.env.local'
$ cp .env.local.example .env.local

# Start the application
$ npm run dev
```

### Mobile

**Make sure to have the server running**

```bash
# From the project root folder access the 'mobile' folder
$ cd mobile

# Install the dependencies
$ npm install

# If you are going to emulate with android, run this command
$ npm run android

# If you are going to emulate with ios, run this command
$ npm run ios

# Or just start the bundle
$ npm run start
```