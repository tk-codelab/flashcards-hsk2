# Why php files?

To prepare to deploy with Heroku, I needed some PHP files. Why?

"Heroku allows web-hosting, but what do you know? They do not host static websites with HTML, CSS, and JS."
https://medium.com/@winnieliang/how-to-run-a-simple-html-css-javascript-application-on-heroku-4e664c541b0b

That's why you need:

- composer.json
- index.php

to trick it to think it's a PHP application.
