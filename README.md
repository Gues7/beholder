beholder
========

beholder is an IRC channel statistics aggregation bot written in PHP

Forked from https://github.com/zoiteirc/beholder to perform some of the to-do tasks and make improvements where possible, with the intention of issuing a pull request when complete.


To-Do (Unordered)
-----------------
* [x] Determine folder layout.
* [ ] Update the MySQL connections / queries to use MySQLi and prepared statements where possible.
* [ ] Break each class out into it's own class.
* [ ] Turn bot.php into an instantiable class.
* [ ] Create beholder.php which instantiates beholder.class.php to run the bot.
    * [ ] Include command line arguments for bot settings in addition to the ability to specify a configuration file.
    * [ ] Add error handling.
    * [ ] Change configuration file from included PHP file to ini file and parse.