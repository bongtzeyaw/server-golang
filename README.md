# Server
A Golang project that spins up a server on local machine using Chi Router. We can use for example ThunderClient on Visual Studio Code to make requests to this server.We also respect common conventions such as nesting a V1 router under v1 path under the main router. A basic error handling is also implemented such as returning 5XX code to signify internal error.

# Objective
Users can create RSS feeds and query the feeds or select the feeds that they want to follow.

# Database
We use pgadmin to host a POSTGRES database on local machine. We then use API keys to uniquely identify users.

# Other technical details
We are using 'database/sql', which is a part of Go's standard library to connect to a SQL database, execute queries, and scan the results into Go types. We also use Goose, which is a database migration tool.
