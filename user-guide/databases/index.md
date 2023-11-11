# Databases

To manage your databases or create a new one, click on "_**MySQL » Databases**_" in the sidebar and your databases will be shown.

## 1. Create a new database

At the top right of your databases overview there is a button "_**Create database**_" which opens the from to create a new database.

<UiBrowser :src="('/img/frx_ug_db_overview.png')" alt="Database overview"/>

Simply specify a database-description and a strong password. The database-name and -username will be autogenerated.

Additionally, you can specify whether the database information and credentials will be sent to you via email.

<UiBrowser :src="('/img/frx_ug_db_create.png')" alt="Create new database"/>

## 2. Access a existing database

Databases can usually be managed with phpMyAdmin, your reseller or admin might provide a web interface, if so it appears in the sidebar under "_**MySQL > phpMyAdmin**_".

To connect your software, e.g. a forum or CMS like wordpress, to it you have to specify the following for the database connection:

* Port: `3306`
* Hostname: `127.0.0.1` (or `localhost`)
* Database: `the selected database name` in our example **web1sql1**
* Username: `the selected database name` in our example **web1sql1**
* Password: `the selected database password`

## 3. Update an existing database

To update the database password or description, you have to choose your database in your overview list.

<UiBrowser :src="('/img/frx_ug_db_overview2.png')" alt="Database overview"/>

Click on the <i class="fa fa-edit"></i> icon to edit the database.

<UiBrowser :src="('/img/frx_ug_db_edit.png')" alt="Edit existing database"/>

## 4. Delete existing database

If you want to delete your database, you have to click on the red <span style="color: red"><i class="fa fa-trash"></i></span> icon.

<UiBrowser :src="('/img/frx_ug_db_overview2.png')" alt="Database overview"/>

You will now be asked if you want to delete the database, you must confirm this with "_**Yes**_".

::: warning ATTENTION
All data from this database will be lost, this action cannot be undone.
:::

<UiBrowser :src="('/img/frx_ug_db_delete.png')" alt="Security question"/>