![PuzzleNode Logo](https://github.com/rmu/puzzlenode/raw/master/doc/puzzlenode.png)

PuzzleNode is a site for coders who enjoy to work on challenging problems, 
and is inspired by similar efforts such as 
[Project Euler](http://projecteuler.net/) and the 
[Internet Problem Solving Contest](http://ipsc.ksp.sk/). 

Puzzlenode is developed, maintained, and supported by 
[Ruby Mendicant University](http://university.rubymendicant.com) (RbMU) students
and staff.

If you are not a member of RbMU, please get in touch through our public channels:

- **Email:** <http://groups.google.com/group/rmu-talk>
- **IRC:** #rmu
- **Twitter:** #RbMU

## Key Features

Coming soon

## Installation

Puzzlenode is a Ruby on Rails 3 application which runs on 
[PostgreSQL](http://www.postgresql.org) databases. Other databases like MySQL 
or SQLite are not officially supported.

### Setting Up a Development Copy: Step by Step

To install a development version of Puzzlenode, follow these steps:

1. Fork our GitHub repository: <http://github.com/rmu/puzzlenode>
2. Clone the fork to your computer
3. Run `bundle install` to install all of the dependencies

To configure University Web:

1. Create a `database.yml` file in `config`. The `config` directory contains 
   an example `database.yml` for PostgreSQL.
2. Create an `omniauth.yml` file in `config`. The `config` directory contains 
   an example `omniauth.yml` file.
2. Run the Rails tasks to initialize a development and a test database:

`rake db:migrate`

`rake db:test:prepare`

Finally, run the test suite to make sure everything is working correctly:

    rake test

## Contributing

Approved features are tracked in 
[Pivotal Tracker](https://www.pivotaltracker.com/projects/258601) while bugs 
and requested features should be entered into 
[Github Issues](https://github.com/rmu/puzzlenode/issues).

Contributors retain copyright to their work but must agree to release their 
contributions under the [Affero GPL version 3](http://www.gnu.org/licenses/agpl.html)

If you would like to help with developing PuzzleNode, please get in touch! 
Our contact details are at the top of this file.

### Submitting a Pull Request

1. Fork the project.
2. Create a topic branch.
3. Implement your feature or bug fix.
4. Add documentation for your feature or bug fix.
5. Add tests for your feature or bug fix.
6. Run `rake test`. If your changes are not 100% covered, go back to step 5.
7. If your change affects something in this README, please update it
8. Commit and push your changes.
9. Submit a pull request.

------

PuzzleNode - a [Ruby Mendicant University](http://university.rubymendicant.com) project