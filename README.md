# View the project

http://flashcards-hsk2.herokuapp.com/

# Start the project locally

Copy path of flashcards.html and open in browser

/xx/xx/xx/flashcards-version-1/flashcards.html

# Related github repo

https://github.com/tk-codelab/flashcards-hsk2/

# TODO

-   Remove the blue flickering when clicking on TIP on mobile

# Wishlist

-   Add list of radicals to practice, next to HSK1, HSK2 etc
-   Add a way to tag a card as 'learned' so only the ones are left that you have to practice. Using cookies? Database seems too much. If database then Firebase.
-   Use an actual text to speech API to generate the sound, instead of going to google translate and having to click the play button there https://cloud.google.com/text-to-speech/ or https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API/Using_the_Web_Speech_API#speech_synthesis. The latter seems promising, see https://mdn.github.io/web-speech-api/speak-easy-synthesis/

# Why make this project?

- Because I wanted to learn Chinese.
- Because I had to learn the HSK2 vocab if I wanted to pass the HSK2 exam.
- Because I found existing flashcards lacking, for example mnemonics, and ease of use.
- Because I love flashcards!
- Because I like actually flipping the cards.
- Because I wanted a pet project next to my work, to make someting in Vanilla Javascript.

# Why php files?

To prepare to deploy with Heroku, I needed some PHP files. Why?

"Heroku allows web-hosting, but what do you know? They do not host static websites with HTML, CSS, and JS."
https://medium.com/@winnieliang/how-to-run-a-simple-html-css-javascript-application-on-heroku-4e664c541b0b

That's why you need:

-   composer.json
-   index.php

to trick it to think it's a PHP application.
