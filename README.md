# PostgreSQL Pagila database

Pagila PostgreSQL database script plugin for Magic that installs the Pagila database into
your _"/etc/pgsql/templates/"_ folder for you. Notice, this plugin does _not_ create
the database for you, or execute the SQL script in any ways, since that requires a valid
PgSQL connection, which we cannot determine with certainty that you actually have.

## Installation

Install this module in your Magic backend, open up SQL Studio, load the pagila script,
and execute it towards a valid database PostgreSQL connection.
