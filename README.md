This project demonstrates how to protect a web application from SQL Injections. The basic idea is to use a validator to validate the web form. Then we use prepared statements for code efficiency and to keep SQL results away from the data. 

The views folder includes files that set up the theoretical database that stores various customer and ice cream info for an ice cream website. The package.json files include the necessary info for our csrf tokens.

All of the node_module files for the tools we've imported and installed with npm, such as validator, express, sqlite3, and cookie-parser, have been omitted from this project for the sake of brevity and readability.
