# User Adoption Prediction Assignment

## Project Overview
This project aims to identify the key factors that predict future user adoption of a product. The analysis involves processing two datasets, defining "adopted users" based on specific criteria, and building a predictive model to uncover significant influences on user engagement.

---

## Data Provided
The analysis is based on two attached CSV files:

### `takehome_users.csv`
This table contains data on 12,000 users who signed up for the product in the last two years. It includes the following attributes:

- **name**: The user's name  
- **object_id**: The user's ID  
- **email**: Email address  
- **creation_source**: How their account was created (one of 5 values):  
  - PERSONAL_PROJECTS: Invited to join another user's personal workspace  
  - GUEST_INVITE: Invited to an organization as a guest (limited permissions)  
  - ORG_INVITE: Invited to an organization (as a full member)  
  - SIGNUP: Signed up via the website  
  - SIGNUP_GOOGLE_AUTH: Signed up using Google Authentication (using a Google email account for their login ID)  
- **creation_time**: When they created their account  
- **last_session_creation_time**: Unix timestamp of last login  
- **opted_in_to_mailing_list**: Whether they have opted into receiving marketing emails  
- **enabled_for_marketing_drip**: Whether they are on the regular marketing email drip  
- **org_id**: The organization (group of users) they belong to  
- **invited_by_user_id**: Which user invited them to join (if applicable).  

### `takehome_user_engagement.csv`
This usage summary table has a row for each day that a user logged into the product. It includes:
- **time_stamp**: Date of activity  
- **user_id**: User’s ID  

---

## Defining "Adopted User"
A user is defined as an **adopted user** if they have logged into the product on **three separate days in at least one seven-day period**.

---

## Assignment Objective
The primary objective is to identify which factors predict future user adoption based on the provided datasets and the definition of an "adopted user."

---

## Deliverables
1. A brief **write-up of findings** (ideally no more than one page).  
2. Supporting **summary tables, graphs, code, or queries** to show the approach.  

In the write-up, please also include:
- Any factors you considered or investigations you did, even if they did not pan out.  
- Any further research or data you think would be valuable for this analysis.  

💡 **Suggested Time:** 1–2 hours (but you are welcome to spend more or less time as needed).  

---
