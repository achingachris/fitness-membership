# Expressed

Node framework for server-side/back-end

EXPRESS:
 - build web apps fast
 - works with apps and microservices

Before:
- basic js
- basic node and npm
- http codes
- json
- arrow functions

Basic server syntax:

```javascript
const express = require('express');

// initialize
const app = express();

// create route handler
app.get('/', function(req, res) {
    res.send('Hello World!');
});

// set port
app.listen(3000);
```

### Middleware

functions that access request and response objects
a stack of functions that executes when a request to server is made.
