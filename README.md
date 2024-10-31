# tdsproject
# GitHub Users and Repositories Scraper

## Overview
This project involves scraping data from the GitHub API to gather information about users in Delhi with over 100 followers and their public repositories. The project focuses on data extraction, cleaning, and analysis.

## Process

1. **Data Scraping**:
   - Used the GitHub API to collect user data for individuals located in Delhi with more than 100 followers.
   - Fetched up to 500 public repositories for each user, capturing relevant details.

2. **Data Storage**:
   - Stored user information in `users.csv` with fields such as login, name, company, location, email, hireable status, bio, public repositories count, followers, following, and account creation date.
   - Saved repository details in `repositories.csv`, including the repository owner's login, full name, creation date, star count, watcher count, language, and license details.

3. **Handling Missing Values**:
   - **users.csv**:
     - Filled missing company values with "UNKNOWN".
     - Replaced missing email entries with "NOT PROVIDED".
     - Substituted missing bios with "NO BIO AVAILABLE".
   - **repositories.csv**:
     - Filled missing license names with "NO LICENSE".
     
4. **Data Analysis**:
   - Conducted a statistical analysis of
