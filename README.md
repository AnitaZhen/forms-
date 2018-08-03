# forms
A simple registration form
Webserver to form: https://csc642-form-anita.herokuapp.com

For the development I used bootstrap, express and node.js. I first installed node.js in my command line and implemented its code into my node.js file. Then I researched how to use bootstrap in my application, so the forms can be displayed on the screen.

For field validation I used javascript and included patterns, minlength and max length ; where it only enables certain characters in the text field. This means for example, for phone number, if  I wanted to include a letter it will not let me; instead only numbers are allowed and it will notify the user to follow input only numbers.

For maps I used google maps. I searched how to autofill the google map and implemented its code. In order to do that, I have to give my web server as credentials so I can insert its API key into my application for the address to display on the screen.

For captcha I used google captcha. I went to google.com and entered my site url. There they gave me directions on how to implement it in my code. I entered my link before the end of the head section and where the google captcha is placed in the application.

For testing I used Selenium and tested the following form fields: first name and last name. I first click record, which started to record the website I was testing. I tested in the localhost:3000 and I started to fill out the form. On the bottom of the screen, the log will record what I entered and check whether it passed or fail. In the log, it showed that it passed by having "OK". The following shows screenshots of the test

For WWW server I used Heroku. I first made an account for Heroku and followed its provided steps in installing the web server. I then tested my application to see if it was working in the localhost:3000 and everytime I was ready to push it, I will first test to see if the site is looking the way I want it to be then I "git add .",  "git commit –m”message”" and "git push Heroku master". This is how the site is running successfully.

“Here I list resources I used in order to design, develop and test this assignment


Bootstrap
https://getbootstrap.com/ (last accessed July 22, 2018)

https://getbootstrap.com/docs/4.0/components/forms (last accessed July 22, 2018)


Selenium
https://www.seleniumhq.org/

https://www.softwaretestinghelp.com/selenium-tutorial-1/  (last accessed July 31, 2018)


Google Captcha
https://www.google.com/recaptcha/intro/v3beta.html (last accessed July 30, 2018)


Google Map
https://developers.google.com/maps/documentation/javascript/places-autocomplete (last accessed July 30, 2018)


Heroku
https://www.heroku.com (last accessed July 31, 2018)
