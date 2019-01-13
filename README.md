# Project S-Bahn-Verspätet
Goal: a simple app that sends an alert to my phone when my daily train (S-Bahn) is delayed

Roadmap:
 1. create Python script that pulls train schedules from [Deutsche Bahn](https://www.bahn.de/p/view/index.shtml) web
    - simple web scrapping: [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
    - simple programming tasks: get journey details (origin, destination, time), check train schedules, find if delayed, notify
 2. create bot that can send a message to phone
    - use [Telegram bot](https://core.telegram.org/bots/api)

 3. integrate Python scripts with bot scripts
    - maybe allow for some interaction with user?

 4. create web app
    - simple [Flask web app](http://flask.pocoo.org/)
   
 5. deploy on the cloud for continuous run
    - [Heroku](https://www.heroku.com/)
