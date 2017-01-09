#Hypemachine Python Downloader
hypme.py is a Python script to bulk download songs from [HypeMachine](http://hypem.com). The script is fairly
simple to use.


##How To Use

1. Make sure you have Python installed (2.7~)

2. Make sure you have [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/) installed. I haven't figured out
how to deploy with dependencies yet

3. Open hypeme.py and modify the script to your choosing!

    `AREA_TO_SCRAPE:` Set this variable to what you'd like to scrape. i.e. popular or a username.

    `NUMBER_OF_PAGES:` Number of pages to scrape. For initial download you can set this number really high and later just cron job the script set to 1.


4. Launch the script `python hypeme.py`
