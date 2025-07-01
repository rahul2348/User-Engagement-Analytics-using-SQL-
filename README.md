
# User_Engagement_Analysis
## Overview
This project involves SQL data analysis aimed at understanding user engagement and behavior on a platform. The queries provided analyze various aspects such as user activity, contest outcomes, hashtag usage, and user interaction patterns.

## SQL Queries and Objectives

### User Engagement and Activity Analysis
- **Oldest Users:** Identified the five oldest users to reward long-term engagement.
- **Registration Trends:** Determined peak registration days to optimize ad campaign scheduling.
- **Inactive Users:** Targeted users who have never posted a photo for re-engagement campaigns.

### Contest and Interaction Insights
- **Top Photo Likes:** Identified the user with the most likes on a single photo to understand content popularity.
- **Average User Posts:** Calculated the average number of posts per user to gauge user activity levels.
- **User Ranking by Posts:** Ranked users based on the number of posts made to identify top contributors.

### User Behavior and Trend Identification
- **Top Hashtags:** Determined the top 5 most commonly used hashtags to optimize post visibility.
- **Bot Detection:** Identified potential bot accounts by finding users who liked every photo on the site.
- **Commenting Behavior:** Analyzed user comments to classify inactive users and highly active commenters.

### Database Schema
The project includes tables for:
- **Users:** Stores user information including usernames and registration dates.
- **Photos:** Tracks photos uploaded by users with image URLs and timestamps.
- **Comments:** Stores comments made by users on photos, linked to users and photos.
- **Likes:** Records likes by users on photos, connected to users and photos.
- **Follows:** Manages user-follow relationships with timestamps.
- **Tags and Photo-Tags:** Tables for managing tags associated with photos.
