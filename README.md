# React Jobly (Backend)

“Jobly” is a job searching API built with Node, Express, and PostgreSQL with relationships. 

This is a pure API app, taking values from the query string or from a JSON body. It returns JSON.

The app gets authentication/authorization with JWT tokens. 

Testing was developed using test-driven development methodology. Model tests check the underlying database actions. Route tests check the underlying model methods and do not rely directly on the database changes.
