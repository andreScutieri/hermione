# hermione
Hermione Knowledge Gatherer

## About

This is a simple Reddit-like link sharing engine. Through a secure RESTful API, threads can be started, commented, deleted and moderated, while subreddit-like communities (called "Boards") can be created by mods. Next version we'll probably allow users to create their own boards.

## Technical Info

Hermione is an API-centric system, thus interaction with the system is done through HTTP requests, and data is received as JSON. Non-fatal errors are received as JSON too. At some fatal error, the system tries to gracefully exit. Tries being the keyword at this 0.1 version.

The system is based on Slim Microframework and OAuth2 for user authentication. Some additional libraries may be added as the project grows. Don't forget to update your composer autoloader whenever this occurs, so you can have the same environment.

For now, configuration is stored at `config.php`. I added a skeleton file for you to add your server configs. The `$api_key` is used by OAuth2. The skeleton file will be properly commented when version 1.0 is released.

## The name

Yep. Harry Potter.

## The frontend

A frontend will be coded soon, the project is still unamed. Probably I'll do it using Twitter's Bootstrap + AngularJS.