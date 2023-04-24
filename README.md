#Go Server

This is a simple HTTP server implemented in Go that serves static files and handles basic HTTP requests. It includes three routes:

GET /: serves static files from the static directory.
POST /form: expects two form fields (name and address) in the request and prints out their values in the response.
GET /hello: returns a simple "Hello!" message in the response.
The server listens on port 8080 by default and can be started with the go run main.go command. The log package is used for logging errors, and the fmt and net/http packages are used for handling I/O and HTTP requests/responses.

Feel free to use this code as a starting point for your own Go web applications!
