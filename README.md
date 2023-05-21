For this assignment, I used Scrapy to scrape data from sreality.cz, focusing on the "flats for sale" section. I gathered the titles and image URLs of the first 500 flats listed on the website.

To manage and store this data efficiently, I used SQLAlchemy, a Python SQL toolkit and Object-Relational Mapping (ORM) system, to interface with a PostgreSQL database. This setup not only helped to organize the scraped data but also provided an easier way to query and retrieve the information when needed.

I created a simple HTTP server using Flask, making the data accessible. The server displayed a web page showing the titles and images of the 500 flats, emulating a user-friendly gallery. To enhance the aesthetics and user experience of the gallery webpage, I also developed a frontend webpage using advanced Bootstrap skills.

For streamlined deployment, I employed Docker Compose. With the use of a single command, "docker-compose up," I was able to see the scraped flat ads on a web page. It was as simple as opening my web browser and visiting http://127.0.0.1:8080.

Through the completion of this assignment, I demonstrated my proficiency in web scraping with Scrapy, managing databases using SQLAlchemy and PostgreSQL, developing web pages with Python and Flask, and implementing containerization with Docker Compose. These skills are invaluable for roles that require user-friendly data extraction, efficient data management, and appealing presentation on websites.
