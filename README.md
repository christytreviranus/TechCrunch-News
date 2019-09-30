# Mongo-NewsScraper

## Overview
This is a full stack web app that scrapes articles from the TechCrunch.com website.  In addition to scraping for articles, users are also able to delete, save, and leave comments on articles that are scraped.

## How It Works
- Scrape articles by clicking the "Scrape Articles" button.
- Read full articles by clicking on the link provided (this will redirect to the npr.org article) 
- Save articles by clicking the "Save Article" button.
- Saved articles can be viewed on the "Saved Articles" page.
- Comments can be added on saved articles by clicking the "Add a Note" button.
- Saved articles can be deleted or by clicking the "Delete/Remove" buttons.

[Check out the App](https://young-ocean-13485.herokuapp.com/)

## Technologies Used
- Node.js
- Express.js
- Handlebars.js
- MongoDB
- Mongoose
- Materialize
- npm packages
    - body-parser
    - express
    - express-handlebars
    - mongoose
    - cheerio
    - request