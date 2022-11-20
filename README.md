# srealityProject
# srealityProject
This  docker-compose project takes as input a csv file that contains the top 500 scraped ads published on sreality.cz, saves it in a Postgresql database, and publishes them in a front-end web page.

This project is built as a docker-compose project, which contains the following containers:
1- Scrapy [name: scrapeit] : for now: disabled.

2- Database container [name: aptsdb11]: It uses Postgresql.

3- Server container [name: apts]: This uses Node.js.

4- The front-end container: This is a PHP-enriched HTML file.

