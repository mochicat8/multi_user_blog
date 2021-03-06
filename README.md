# Multi User Blog  
A multi-user blog manages blog accounts and blog posts.  Users are able to like
posts and write comments.  

Features:
- Login/Logout/Signup
- Comments
- Create/Edit/Delete Blog Posts
- Likes/Unlike
- Cookies to identify valid user


**app.yaml**
  : configuration file needed for on how to map
URLs to static files, must be included when using google app engine

###Languages
- Python
- HTML

### Database
 - Google Cloud Datastore - a NoSQL document database

### Built With
 - webapp2 - web application framework
 - jinja2 - templating language for python
 - Twitter Bootstrap - front-end framework used for styling

#Installation
Install [Google App Engine] (https://cloud.google.com/appengine/docs/python/download)
###Google Deployment
```sh
$ cd [path of program]
$ gcloud app deploy
$ gcloud app browse
```
###Local Deployment

```sh
 dev_appserver.py [PATH_TO_APP]
```
Open browser and link to http://localhost:8080

Live example:
https://blog-153106.appspot.com
