# SEO-Friendly Markdown Blog

This is a blog template that can be integrated into a Node.js web application. 

## Features

### Blog

#### Admin User

Blog articles can only be created, edited, and deleted by an authenticated admin user. Upon logging in, each user will be given a jsonwebtoken that will expire after a short period of time. Re-logging in will generate a new token.

Each individual blog article will be generated using EJS. Every new article will be required to fill in 7 fields, and these 7 fields are responsible for supplying the article with it's metadata, slug, category, category slug, image, image description, and text content. The article's text content has been set up to be written in markdown.

#### Non-Admin User

Leave comment for each blog article. Limit of one comment per user per article.

## Future Features
  
  - Comment Replies for admin user
  - User Profile Page w/ option to change personal info
  - Search bar
