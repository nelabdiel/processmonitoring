# Automated system monitoring

When Scraping a list of sites with Selenium (either threading or on a loop) I usually run into the trouble of a process that slows down the queue because it keeps hanging. Running this notebook while you run your scraping code will prevent processes from slowing down your queue by stopping any _phanthomjs_ process that has been active for more than a minute.
