# xmlstats-nba-event-downloader
Python 3.5 project to download NBA basketball events from [xmlstats](https://erikberg.com/api) for a date range defined in the xmlstatsnbaeventdownloader/main.py file.

To setup:

git clone https://github.com/rpearce11/xmlstatsnbaeventdownloader.git

Instructions relative to the directory you have just installed from and sequential i.e. you run unit tests, then the program

To test:

$ cd xmlstatsnbaeventdownloader/tests

$ nosetests *.py

To run:

$ cd ../xmlstatsnbaeventdownloader

$ python main.py "access_token" "user_agent"

Details of the access_token and user_agent can be found at the site https://erikberg.com/account/token and https://erikberg.com/api respectively

To Do: See Issues
