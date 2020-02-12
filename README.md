# docker-watch-test

This repository keeps code used for testing file watching capabilities in Docker on Windows.

## Setup

### 1. Install dependencies

```
docker-compose run app npm install
```

### 2. Start the application

```
docker-compose up
```

### 3. Test automated rebuild on change

1. Head to `http://localhost:9955`
2. Change `index.js`
3. Reload `http://localhost:9955`

You should see the changes made reflected in the browser in case this works as expected.
