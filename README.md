# Digital Measures Module
## Purdue Digital Measures Personal Screen Integration 

This module pulls in content from the Digital Measures API and displays it on a user page.

Features:
* Create three system variables: *Digital Measures API URL*, *Digital Measures Username*, and *Digital Measures Password*
* Creates a block: "*Digital Measures Profile Data*" that can be assigned to user profile pages

** Installation Instructions
1. Get a username and password from your Digital Measures contact on Purdue University.
1. Set up the system variables in the configuration settings page here: /admin/config/content/digital_measures
1. Assign the "Digital Measures Profile Data" to the user display pages. For example: profile/* The block is located here: /admin/structure/block/manage/digital_measures/digital_measures_profile_data/configure
1. Edit a user page and check the box to pull data from the API. 
1. Make sure caching is turned on for the block/page in a production environment. If you don't, every pageload will be a new call to the API.
