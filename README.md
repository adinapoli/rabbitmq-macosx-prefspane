rabbitmq-macosx-prefspane
========================

This Preferences pane for RabbitMQ

*This is a shameless port of Remy Sassy's MongoDB Preference Pane to
RabbitMQ, so any credits goes to him for his outstanding job:*

(http://blog.remysaissy.com/)[http://blog.remysaissy.com/]

Functionalities
---------------

* Runs on MacOSX Snow Leopard, Lion and Moutain Lion
* Indicates if the server is running
* Manual start/stop of the RabbitMQ server
* Enable/disable automatic startup of the server at boot
* Keep your plist’s customizations safe
* Homebrew’s launchd plist is migrated
* Enable/disable automatic startup don’t delete the launchd plist
* Automatic update
* New versions install automatically
* A green label at the top right corner informs you that you should restart your system preferences

Localization
------------

* English
* French
* Simplified Chinese
* Spanish
* Brazilian / Portugese
* Italian

Prerequisites
-------------

It does not embed a RabbitMQ Server. Therefore, you first have to install RabbitMQ with HomeBrew.

$brew install rabbitmq

Installation
------------

1.	Download the latest version: https://github.com/remysaissy/mongodb-macosx-prefspane/raw/master/download/MongoDB.prefPane.zip
2.	Unzip MongoDB.prefPane.zip
3.	Double click on MongoDB.prefPane. This will install it in your System Preferences

Note: To Mountain Lion users. This application is presently not on the app store and therefore it is not signed. You can still install it but don't be surprised to have an alert about it.

Contributing
------------

Want to contribute? Great!

1. Fork it.
2. Create a branch (`git checkout -b my_mongodb_prefspane`)
3. Commit your changes (`git commit -am "Added Installer"`)
4. Push to the branch (`git push origin my_mongodb_prefspane`)
5. Create an [Issue][1] with a link to your branch
6. Enjoy a refreshing Diet Coke and wait

[1]: https://github.com/remysaissy/mongodb-macosx-prefspane/issues

Original Work
-------------

Shameless adaptation around the work of Rèmy Sassy: (https://github.com/remysaissy)[https://github.com/remysaissy]
