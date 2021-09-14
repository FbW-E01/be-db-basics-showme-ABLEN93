# Backend - Database Basics - Show Me

You are planning to build an app where users can add poems anonymously. You want to have _some_ data regarding the poem, but nothing that can be used to identify the user. Before even starting, try to think about the data you will be handling. You (as an administrator) are allowed to edit the poems.

You could take some inspiration from here; https://www.poetryfoundation.org/poems/152825/

- What data to save?
i would use data (text)
- Which types of fields would you have? Do you need dates?
maybe if i want to show when this added
- Estimate how much data will you allow to be saved 
its have to be so much data cuz we talk about poems so its will be alot i think!!
- Describe the data in whatever way you find best
the data its whatever user will write and added to our app (text or Numbers or any thing)

- Show how you would create the table(s) for your data

we have to write like this command 
CREATE TABLE USERS (
project-name varchar(255)not null,
email varchar(255)not null,
locaion varchar(255)not null);
