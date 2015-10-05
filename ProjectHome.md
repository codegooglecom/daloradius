![http://daloradius.wiki.sourceforge.net/space/showimage/radius.jpg](http://daloradius.wiki.sourceforge.net/space/showimage/radius.jpg)
# daloRADIUS #


## Overview ##
daloRADIUS is an advanced RADIUS web management application aimed at managing hotspots
and general-purpose ISP deployments. It features user management, graphical reporting,
accounting, a billing engine and integrates with GoogleMaps for geo-locating.




## In Depgth ##
daloRADIUS is written in PHP and JavaScript and utilizes a database abstraction layer
which means that it supports many database systems, among them the popular MySQL,
PostgreSQL, Sqlite, MsSQL, and many others.

It is based on a FreeRADIUS deployment with a database server serving as the backend.
Among other features it implements ACLs, GoogleMaps integration for locating
hotspots/access points visually and many more features.


daloRADIUS is essentially a web application to manage a radius server so theoretically
it can manage any radius server but specifically it manages FreeRADIUS and it's database
structure. Since version 0.9-3 daloRADIUS has introduced an application-wide database
abstraction layer based on PHP's PEAR::DB package which support a range of database
servers.

As a web application, daloRADIUS acts as a management console to control all aspects
of a RADIUS server as well as providing extended commercial or
professional features such as Accounting information, graphical reports, a Billing
engine and built-in integration for GoogleMaps service for geo-locating NAS servers
and HotSpots centers.



## News ##

### Upcoming release notes for 0.97 ###
> - fixed support for password hiding in users/operators listings

> - fixed deletion of usergroup instances of the user

> - fixed saving encrypted password changes in database (reported by kreg, thanks)

> - fixed deletion of attributes from profiles page (reported by kreg, thanks)

> - fixed user accounting page to support Max-Daily-Session and Max-Monthly-Session (reported by Kelvin)

> - improved usability on disconnect user page

> - improved greatly attributes management with support for dynamic helper functions

> - added quick editing of online users and showing mac addresses listing

> - added new pages - realms and proxys configurations

> - added support to remove user accounting records in the delete page

> - added dhtmlgoodies libraries for ajax auto-complete and popup tooltip

> - added vendor/attributes management page to allow editing of official and custom attributes

> - added more icons, variable translation and layout changes