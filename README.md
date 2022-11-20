# Bathroom Finder Api

Bathroom Finder Api provides bathroom data in UCI such as: the location of bathrooms, the nearest route to a bathroom, and the rating and comments on bathrooms.

## How to start developing

1. clone the `bathroom-finder-api` to your local machine.

```bash
git clone git@github.com:bensonjing/bathroom-finder-api.git
```

2. Chang into the project directory

```bash
cd bathroom-finder-api
```

3. Install the dependencies

```bash
npm install
```

4. Start the development server

```bash
npm run debug
```

5. The site should load on https://localhost:3000  
   As you make changes to the Express application, those changes will be automatically reflected in the API.

## Todo

- [x] Create a server using Node.js and Express
- [ ] Create a database using MongoDB and connect to the server
- [ ] Create models inside database representing bathroom
- [ ] Create routes for index, login, logout, bathrooms
- [ ] Create controller for each route
