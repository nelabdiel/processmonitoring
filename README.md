# Automated system monitoring

When Scraping a list of sites with Selenium (either threading or on a loop) I usually run into the trouble of a process that slows down the queue because it keeps hanging. Running This notebook while you run your scraping code will prevent processes from slowing your queue by stopping any _phanthomjs_ process that has been running for more than a minute.
