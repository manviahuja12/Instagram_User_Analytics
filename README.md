# Instagram User Analytics

## Objective
The project analyzes an Instagram-like database to uncover key insights about user interactions, content engagement, and social connections. By writing SQL queries, the goal was to extract meaningful patterns related to user activity, photo popularity, and network relationships.

## Tools Used
- **Database:** MySQL Workbench 8.0 CE
- **Query Language:** SQL
- **Presentation Tool:** Canva

## Database Overview
The analysis was conducted on a relational database with the following tables:
- `users` – Stores user information, including username and account creation date.
- `photos` – Contains photo details, including the uploader and timestamp.
- `likes` – Tracks which users liked which photos.
- `comments` – Stores user comments on photos.
- `follows` – Captures follower-followee relationships.
- `tags` – Lists hashtags used in photos.
- `photo_tags` – Connects photos with hashtags.

## Key Insights
### User Analysis
- **Top 5 Most Loyal Users:** Identified the five oldest users based on account creation date.
- **Users Who Never Posted:** Found users who have never uploaded a single photo.

### Engagement & Content Trends
- **Most Liked Photo Contest Winner:** Determined the user whose photo received the most likes.
- **Trending Hashtags:** Found the top 5 most-used hashtags. Due to a tie at the fifth position, 8 hashtags were identified.
- **Best Day for Ad Campaigns:** Discovered that Thursdays and Sundays have the highest user registrations, making them ideal for marketing.

### User Activity & Fraud Detection
- **Average Posts Per User:** Calculated an average of 2.57 posts per user, indicating steady engagement but room for growth.
- **Bot Detection:** Identified users who have liked every single post on the platform, a strong indicator of bot activity.

## Summary
This project provides a deep dive into Instagram user interactions using SQL-based data analysis. The insights help in:
- 📈 Optimizing marketing campaigns based on user activity.
- 🔥 Identifying top content strategies using popular hashtags and engagement trends.
- 🛡️ Detecting bot-like behavior to improve platform authenticity.

The findings can assist social media analysts, marketers, and data teams in making data-driven decisions for enhanced engagement and security.
