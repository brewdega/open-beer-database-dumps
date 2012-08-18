# Open Beer Database Dump

This is a cleaned up and sanitized dump of the data originally provided by the
[Open Beer Database][open-beer-db] project. We originally tried to use this data
before discovering, and quickly adopting, [BreweryDB.com][brewerydb] as the
canonical source of beer information for [Brewdega][brewdega].

## Usage

We've merely cleaned the data to make it easier to import into other data
stores. How you use it is up to you. That said, we'd strongly recommend checking
out [BreweryDB][brewerydb] if you're looking for an up-to-date source of beer
information.

### Rake tasks

Also included are a few rake tasks we used to use to export the MySQL dumps into
`.cvs` files, and then import those `.cvs` files back into our domain model (via
`ActiveRecord`). If you find them useful, great! If not... they're free, so
don't complain.

## License

This information is licensed under the [Open Database License][open-db-license].
Any rights in individual contents of the database are licensed under the
[Database Contents License][db-contents-license].


[brewdega]: http://brewdega.com
[brewerydb]: http://brewerydb.com
[db-contents-license]: http://opendatacommons.org/licenses/dbcl/1.0/
[open-beer-db]: http://openbeerdb.com/
[open-db-license]: http://opendatacommons.org/licenses/dbcl/1.0/
