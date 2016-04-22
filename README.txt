Bookpak
Allows users to browse books and read book reviews, 4.22.2016

By Josh Overly

Description

Users can remain anonymous or create an account. Users can browse book reviews and see ratings. They can contact the bookstore owner.  Authenticated users can see special coupons.  Reviewers can add book reviews.

Setup/Installation Requirements

You will need to have MAMP or WAMP installed.

Go to https://github.com/jos-h20/drupal_bookstore.
Copy the directory.
From your terminal, change your directory to desktop.
Type in git clone https://github.com/jos-h20/drupal_bookstore.git
Open MAMP and click on Preferences
Click on the folder icon and select drupal_bookstore
Start servers
Open WebStart Page
Select Tools/PHPMyAdmin
Click on Import
Choose file/go to drupal_bookstore/sites/db-backup
Click on the zipped database
Click Go
Once database has downloaded, click josh_bookstore_database
Go to Privileges, click Add User
For user name put in admin_bookstore
change host to local
For the password, type in book
Click Go
In your browser, type in localhost:8888
Select standard installation/select English
Enter josh_bookstore_database, user name: admin_bookstore, password: book
Under advanced options, change host to 127.0.0.1
And port to 8889
The user name and password are the same for the site.








Known Bugs

No known bugs.

Support and contact details

email: joshoverly@student.com

Technologies Used

Drupal, PHP

License

Copyright (c) 2016 OverlyDev Licensing MIT
