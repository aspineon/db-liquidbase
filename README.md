
# Overview #

Since the db will be used by various example architectures, the decision was made to use Liquibase.



## Setup ##

The following is how to setup the env to run the db migrations:

* Install liquibase: mac `brew install liquibase`  or ubuntu `sudo apt-get install liquidbase`
* Update `liquibase.properties` with db information
* Run `liquibase --changeLogFile=db/changelog.xml migrate`


## TODO ##
* Example of yaml version
* fill out tables