# README.md

Allows running php artisan from anywhere in a Laravel 4 directory structure.

This is just a simple little bash script called **art** that you can stick in your bin directory. It allows you to execute Laravel's artisan command from anywhere within your project's hierarchy.

## Installation

1. Copy the `art` script to somewhere in your path.
2. Edit line #5 of the script and change the `DEFAULT_PROJECT` to whatever you want the default to be. If you are outside any Laravel project, then artisan will be executed within this directory.

## Usage

~~~~~~~~
$ cd /some/laravel-project/app/config
/some/laravel-project/app/config$ art routes
+--------+-------+------+---------+----------------+---------------+
| Domain | URI   | Name | Action  | Before Filters | After Filters |
+--------+-------+------+---------+----------------+---------------+
|        | GET / |      | Closure |                |               |
+--------+-------+------+---------+----------------+---------------+
~~~~~~~~

I've only tested it on Linux Mint 14.
