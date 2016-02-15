# Extended "observable" approach:
This approach builds on the patterns used in the part "observable" approach. The URL is observed in a similar way that the store is observed.

Dispatching side effects of updating the URL are managed with react-router's (history's) browserHistory.listen() method. (see - [index.js](index.js#L28))

## To run
```sh
npm install
npm start
```
