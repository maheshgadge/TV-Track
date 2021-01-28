

The project is split into `client` and `server`. Latter is a simple [JSON Server](https://github.com/typicode/json-server) at the moment.

Clone the repository and change into the `client` folder. Install dependencies:

```sh
npm install
```

Repeat for the `server` folder.

The project uses the TMDb API and requires an API key. After creating an account on [TMDb](https://www.themoviedb.org), you can request an API key under `Profile > Settings > API`. Please add your key in `./client/src/config.js`!

Afterwards open two separate terminal windows and run `npm start` in the `client` folder as well as the `server` folder.

The `client` (frontend) will run at `http://localhost:3000` (opens automatically), and the `server` (backend) will run on port 3001.

### Available scripts

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), so all its scripts are available in the `client` folder:

```sh
npm start
npm test
npm run build
npm run eject # be careful :)
```


