
# Overview #

Since the db will be used by various example architectures, the decision was made to use Liquidbase.



## Setup ##

The following is how to setup the env to run the db migrations:

* Install liquidbase: mac `brew install Liquidbase`  or ubuntu `sudo apt-get install liquidbase`
* Update `liquidbase.properties` with db information
* Run `liquidbase --changeLogFile=db/changelog.xml migrate`
