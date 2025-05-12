# Codecademy Learners Mockup Data

## Overview
This SQL project analyzes mock Codecademy learners' data to explore user behavior, course preferences, and usage trends.  
It involves querying two key tables—`users` and `progress`—to extract insights through aggregate functions and joins.  
Unlike traditional step-by-step tutorials, this project encourages open-ended problem-solving using SQL.

## Project Goals
- Understand and explore mock learner data  
- Practice SQL queries, aggregate functions, and JOIN operations  
- Analyze learner behavior based on domain, city, and course progress

## Tables Used

### `users`:
- `user_id`  
- `email_domain`  
- `country`  
- `postal`  
- `city`  
- `mobile_app`  
- `sign_up_at`

### `progress`:
- `user_id`  
- `learn_cpp`  
- `learn_sql`  
- `learn_html`  
- `learn_javascript`  
- `learn_java`

## Key Tasks & Queries
- View all records in both `users` and `progress` tables  
- Identify the top 25 `.edu` email domains  
- Count `.edu` learners based in New York  
- Determine the number of learners using the mobile app  
- Analyze user sign-ups by the hour using date/time formatting  
- Join both tables to explore course preferences by domain  
- Investigate which courses are popular in New York and Chicago
