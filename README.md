# CheckMate


## Idea
The idea is to create a simple node app that enables users to enter FQDNs or IP addresses into a list and select an interval at which time our server will ping the properties and report any that don't respond.

As a first pass, if/when users' properties fail to respond to a ping ( or `GET`-request to port `80` ), we'll simply email the user an alert notifying them as such.

## Eventually
It would be nice to have prettier email alerts, reports, graphs, etc.

Also, I wouldn't mind offering a paid tier which enables some set of *premium* features ( currently TBD ).
