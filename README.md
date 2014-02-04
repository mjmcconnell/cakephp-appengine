CakePHP on Google's App Engine
=======

####This is a barebones app, that will get your CakePHP app up and running on Googles' App Engine.

Once you have a Google App Engine Account set up and paired with Google SQL, and Google Cloud Storage, there are a couple of bits of code you will need to update.
What you need to update:
 * Update  `/app/Config/database.php` with Google SQL details
 * Add Google Cloud Storage Bucket ID's in `php.ini` and `/app/webroot/index.php`
 
For a full introduction to CakePHP on App Engine, and a tutorial on how to get a basic app up and running, please fallow the link below:
 
[Click Me](http://dev-mcconnell.blogspot.co.uk/2014/01/cakephp-2.html) - CakePHP with Google's App Engine tutorial


Some Handy Links
----------------
[Google PHP Runtime Docs](https://developers.google.com/appengine/docs/php/) - All you need to know about setting up your App and how to connect to other services, such as the Cloud Storage and Cloud SQL

[App Engine Launcher](https://developers.google.com/appengine/downloads) - Java runtime environment for Google App Engine apps