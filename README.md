## J2D
### What is this ?
This is a Drupal 7 module.
This module is made for people who want to synchronize users from an old Joomla! 1.5 website to a new Drupal 7 website.
When the user is trying to log in the new Drupal website, if the user is not registered on the Drupal side, it will check the user credentials in the old Joomla! users table and if the username and password are correct, a new account is created on the Drupal website, then the account line is deleted on the Joomla! table.
### How to use this ?
* Export your Joomla! 's users table (usually jos_users)
* Import the table to your new Drupal 's database
* Enable the module
* Go to /admin/config/j2d and set the Joomla! 's users table name if this is not named "jos_users"
* Let the nature do the job.
* Sometimes, you can come back to the module's config page to check if there are still available users and if no users are still available, you can disable and forget this module.
