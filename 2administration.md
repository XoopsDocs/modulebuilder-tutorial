# Administration Menu

![](.gitbook/assets/image001.png)

_Figure 1: Main view of the ModuleBuilder \(Admin side\)_

## Dashboard

![](.gitbook/assets/2dashboard.jpg)

_Figure 2: Import and Export of your current database \(Admin side\)_

When you start working with XOOPS ModuleBuilder, you can import our sample definition of a module. This will help you to understand the settings of a module, its tables, and individual fields.

If you create a very cool module, you can export the database and share with others, so they can import it and improve it or customize for their individual needs.

## Settings

![](.gitbook/assets/2settings.png)

_Figure 3: Module Settings \(Admin side\)_

You can define the Default settings for your future modules. Every new module will start with these values

## Modules

![](.gitbook/assets/2modules.jpg)

_Figure 4a: Module List \(Admin side\)_

In this tab you can see list of all you modules that you've worked on.

![](.gitbook/assets/2moduleedit.jpg)

_Figure 4b: Module Settings\(Admin side\)_

Here you can define the details of your new module.

## Tables

![](.gitbook/assets/2tables.jpg)

_Figure 5: Table List \(Admin side\)_

In the Tables tab, you can see all you modules

![](.gitbook/assets/2tablesexpand.jpg)

_Figure 6: Expanding module \(Admin side\)_

Click on this icon to expand the module and show all its tables. On the right hand sid you can click on the icons to edit the module, or to see all the fields defined in the table

## Fields

![](.gitbook/assets/2fields.jpg)

_Figure 7: Fields \(Admin side\)_

Here you can see the tables, and you can edit the table settings, or you can edit the fields

![](.gitbook/assets/2fieldsvisibility.jpg)

_Figure 8: Expanding fields View \(Admin side\)_

Before you go to edit the individual fields, you can click on the left icon - it will expand the table showing all the fields. You can then change the visibility of each field, i.e. if it will be visible in the list and in the form for Admin, as well as for the User

![](.gitbook/assets/2fieldsdetails.jpg)

_Figure 9: Fields details \(Admin side\)_

Here you can edit the details for each field.

## More Files

![](.gitbook/assets/2morefiles.jpg)

_Figure 10: More files \(Admin side\)_

If you want to include additional files in a particular module, you can add them here

![](.gitbook/assets/2morefilesform.jpg)

_Figure 11: More Files Edit view \(Admin side\)_

This is the information that you have to provide for the additional files

## Building Module

![](.gitbook/assets/2build.jpg)

_Figure 12: Generating the new module \(Admin side\)_

You're finally done \(or you think so\), so it's time to generate the module.

To make sure that you don't overwrite you code, the default is to write the files to /uploads/modulebuilder/repository folder. But if you're sure that you want to overwrite you current files, you can select the module to overwrite. This will save you some time, as you don't have to copy the files from the /uploads folder.

## Feedback

![](.gitbook/assets/2feedback.jpg)

_Figure 13: Feedback \(Admin side\)_

Here you have the option to provide feedback and recommendations to the developers

## Migrate

![](.gitbook/assets/2migrate.jpg)

_Figure 14: Migrate \(Admin side\)_

For developers of the module, we provide a "Migration" option

![](.gitbook/assets/2migrateshowsql.jpg)

_Figure 15: View SQL differences\(Admin side\)_

If the module database schema is in synch with the database, then there are no SQL commands here. However, since we just changed the version number of the module, there is no schema yet, therefore the "Show SQL" button shows all the code

![](.gitbook/assets/2migratewriteschema.jpg)

_Figure 16: Writing the schema \(Admin side\)_

When you make changes to the ModuleBuilder database structure, you should update the schema stored in /sql folder.

![](.gitbook/assets/2migrateschemafile.png)

_Figure 17: Module schema file \(Admin side\)_

This is how the schema file looks like. It will make updates from version to version much easier.

## About

![](.gitbook/assets/2about.jpg)

_Figure 18: About information \(Admin side\)_

Some additional information about this module, incl. the changelog

## Help

![](.gitbook/assets/2help.jpg)

_Figure 19: Help view \(Admin side\)_

Every module contains a Help information.

