wiki

server
172.16.4.80
wiki.3rivers.local

basic design
login page
	its a login page
create new article page
	empty text area 
	after creation page is added to databse
editing articles page
	gives users a text area pre-populated with title of a article
viewing articles page
	searches databse for title of article
	parses markdown in from a database blob into pretty html and displays to user
	link to edit the page on that page
	will be articles themselves homepage set to default
		home page
		about page
	error state when article cant be found

later features:
revision tracking
user mgmt
nesting articles
media


databases
mysql?

users
-----
id (int)
email (string)  #used as username
hashed_salted_password (string)
other meta info?

articles
--------
id (int)
title (tinyblob)
content (mediumblob)
date_created (date)
last_edited (date)
user_created (tinyblob)
last_user_edited (tinyblob)











process:
database:

