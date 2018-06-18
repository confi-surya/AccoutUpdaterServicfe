# AccoutUpdaterService

Aim of this project is to read the content of all the containers files written by container
service in various REST operations (PUT,DELETE,POST) related to container/object.

This service commuicate with Container services to get the metadata information of it and then
communicate with Account Service to update the same data to respective account.

Trigger Recovery in Distributed System
=======================================

Account Service communicate with the Global Leader of the Distributed system to fetch the latest
component map in the system as per nodes. And recover its map in case some nodes goes down in system
and Global leader update the component map of whole system.


Account Data clean up
======================

Clean the data and metadata assoicated with the account from the complete file system.


Prevention from duplicate account creation
==========================================
