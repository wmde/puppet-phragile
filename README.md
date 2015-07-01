# Puppet Phragile

This module sets up [Phragile](https://github.com/wmde/phragile).
Phragile generates sprint overviews and data visualizations for projects in Phabricator.

This installs and sets up:
* Apache
* PHP
* Composer
* Phragile
   * clone repository
   * download Composer dependencies
   * configure environment variables in .env
   * set up cron job for snapshots
   * run migrations

Some manual configuration (e.g. MySQL config and Phabricator connection) needs to be done in the .env file to complete the installation.
