simple-http-listener
====================

A basic http server for node.js that logs all incoming requests in raw format. Currently the server returns 200 OK to all requests.

Uses [parsley](https://github.com/substack/node-parsley) to obtain the raw HTTP requests

Usage
-----------
`node simple-http-listener`

Configuration
-----------
Modify config.json to change configuration:

*   log file (default log.txt)
*   listening port (default 8080)

