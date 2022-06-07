# PostgreSQL Pagila database

Pagila PosgreSQL database script plugin for Magic that installs the Pagila database into
your _"/etc/pgsql/templates/"_ folder for you. Notice, this plugin does _not_ create
the database for you, or execute the SQL script in any ways, since that requires a valid
PgSQL connection, which we cannot determine with certainty that you actually have.

## Installation

Install this module in your Magic backend, open up SQL Studio, load the pagila script,
and exexcute it towards a valid database PostgreSQL connection.

## License

Notice, the SQL script itself is the copyright of Luis Rocha, and we have no idea of its
license terms, since it was hosted at CodePlex at a page that no longer exists. However,
CodePlex exclusively served open source projects as far as we know, and since the database
is only intended for educational purposes and to play with Magic, we're pretty sure of
that our usage is covered by what's considered _"fair use"_. If you are the copyright holder
of this SQL script, and you can clarify this for us, we'd love to know.
