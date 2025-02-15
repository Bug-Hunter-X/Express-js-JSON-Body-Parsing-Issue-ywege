# Express.js JSON Body Parsing Issue
This repository demonstrates a common issue encountered when working with JSON request bodies in Express.js applications. The problem occurs when the application fails to correctly parse the incoming JSON data, resulting in an empty or undefined `req.body`. This usually happens due to incorrect middleware configuration or missing dependencies.

## Bug Description:
The Express.js server is unable to parse incoming JSON requests and `req.body` remains empty.  The console log in the `/data` route shows an empty object. This is despite the inclusion of `express.json()` middleware.