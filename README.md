# Docker Teamcity image
Centos 7 + Java 8 + Teamcity

This repository contains dockerfile for building image with Teamcity installed. In adition it downloads Postgresql driver and removes some of the default plugins: 

* clearcase
* mercurial
* eclipse-plugin-distributor
* vs-addin-distributor
* win32-distributor
* svn
* dot*


**NOTE**: Image contains only teamcity server without build agent.

Also it is needed to update config file with your DB connection properties, or 

Installation directory: /srv/apache-tomcat/webapps/ROOT
Server directory: /home/app/.BuildServer
