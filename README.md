Starwars GraphQL API + Twig templates Blazon example
====================================================

This directory contains a complete example for publishing a static
website based on data retrieved from the following GraphQL API:

* https://graphql.org/swapi-graphql/

## Directory structure

The example defines queries (for retrieving films and characters) in the `graphql/` directory.

Twig Templates for visualising the query responses are stored in the `templates/` directory.

The `src/PublicationFactory.php` file defines a custom Publication factory that executes the queries and constructs the publication for publishing.

## Publishing

Use the following command to generate a static website in the `build/` directory with verbose output:

    # install php dependencies into vendor/
    composer install

    # run blazon to publish into build/
    vendor/bin/blazon publish -vv

## Brought to you by the LinkORB Engineering team

<img src="http://www.linkorb.com/d/meta/tier1/images/linkorbengineering-logo.png" width="200px" /><br />
Check out our other projects at [linkorb.com/engineering](http://www.linkorb.com/engineering).

Btw, we're hiring!


