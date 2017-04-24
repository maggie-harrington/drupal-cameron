# Cameron's Coffee

#### Epicodus Guided Example Project for Drupal

#### _By Maggie Harrington_
##### _4-17-17 through 4-24-17_


## Description

##### _A sample small business website for a coffee shop written in Drupal. The basic content of the site is mostly provided by Epicodus curriculum. The styling is a modified version of the theme Danland._


##### This project demonstrates the following skills:

* Learn basic Drupal terminology and see how the parts of a project are structured.
* Practice the steps for setting up a new Drupal project with a database.
* Use Git to track your Drupal projects and set up local development environments for ongoing projects.
* Practice site building using Drupal's browser interface.
* Add and organize content on your sites using Basic Pages, Articles, Blocks and Custom Content Types.
* Change the look and feel of your site by configuring themes.
* Use both Core and Contrib modules.
* Use the Features module to keep your configuration settings in code.
* Write a basic custom module in PHP.


## Setup/Installation Requirements

##### Requirements:

* MAMP (see https://www.mamp.info/en/downloads/ for installation details)


##### Clone Project:

* Open the terminal and enter `cd Desktop`

* Enter `git clone ` and copy/paste the project link: https://github.com/maggie-harrington/drupal-cameron-site

* Enter `cd drupal-cameron-site`


##### Import Database and Configure:

* In MAMP Preferences, change document root to project folder listed above. Make sure Apache Port is set to 8888 and MySQL Port is set to 8889.

* In your web browser, open phpMyAdmin: http://localhost:8888/MAMP/index.php?page=phpmyadmin&language=English

* Click the 'Import' tab, leave the default settings and make sure the character set is 'utf-8'.

* Click the 'Choose File' button next to 'Browse your computer' and navigate to sites/db-backup/cameron_database.sql.zip , then click 'Go'.

* Select the 'Privileges' tab and click 'Add User', then enter 'Admin' for the username and 'Sample68Database*' for the password.

* Navigate to localhost:8888 in your web browser to view the project. (Make sure to keep the terminal window containing the server open while the project runs.)


## Support and contact details

If you run into any issues or have questions, ideas or concerns, please feel free to contact me at maggie.harrington@gmail.com


## Technologies Used

Written using Drupal, MAMP, PHP, Pixlr, Google Fonts, Atom, and Git.

Modules used: CTools, Easy Social, Sweaver, Variable, Views

Theme used: Danland (modified)


## MIT License

Copyright (c) 2017 Maggie Harrington
