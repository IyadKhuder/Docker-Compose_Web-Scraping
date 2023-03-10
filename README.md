# Web Scraping Project

# srealityProject
This  docker-compose Web-Scraping project scrapes the top 500 scraped ads published on sreality.cz, saves them in CSV format, which is saved in a PostgreSQL database, and then gets published in a front-end webpage.

This project is built as a docker-compose project, which contains the following containers:

1- Scrapy [name: scrapeit] : for now: disabled.

2- Database container [name: aptsdb11]: It uses Postgresql.

3- Server container [name: apts]: This uses Node.js.

4- The front-end container: This is a PHP-enriched HTML file.

