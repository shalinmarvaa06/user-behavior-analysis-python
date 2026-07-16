# user-behavior-analysis-python
User behavior analysis using Python, Pandas, and Matplotlib to explore engagement trends, marketing channels, and conversion metrics.

## Project Overview

This project analyzes user event data to understand user behavior, marketing channel performance, and user engagement trends. The analysis includes data cleaning, exploratory data analysis (EDA), and visualization using Python.

## Business Questions

This analysis aims to answer the following questions:

- What is the overall user conversion rate?
- Which marketing channels generate the highest user activity?
- What is the distribution of user events?
- Which devices are most commonly used?
- Which country had the highest number of active users in Q2 2025?
- How does Monthly Active Users (MAU) vary across marketing channels?

## Dataset

The dataset contains user interaction events collected from an e-commerce platform.
| event_id | user_id | session_id | event_type | event_timestamp | product_id | country | device | channel |
|----------|---------|------------|------------|-----------------|------------|---------|--------|---------|
| 9bd8725f... | 482c0ae4... | 98b232db... | product_view | 2025-09-22 16:35:27 | P1208 | US | iOS | paid_search |
| f6dc704c... | ff6c808d... | d4832af2... | page_view | 2025-06-04 21:55:04 | - | ID | Android | referral |
| abb69be8... | 78ea2c10... | 1f6c5b12... | page_view | 2025-06-24 02:02:51 | - | AU | iOS | paid_search |
| 76fd2399... | 9c63419c... | ed1c4ded... | page_view | 2025-06-05 12:35:33 | - | VN | iOS | organic |
| 26dcc5fa... | f9aee3bb... | 9a469fb9... | product_view | 2025-07-02 12:19:23 | P1315 | ID | Desktop | social |
| 86cffeab... | d34c7eab... | f56f38b4... | purchase | 2025-08-27 21:51:21 | P1144 | PH | iOS | organic |
| c8073c50... | bb36401f... | 6cbc0241... | product_view | 2025-05-03 09:27:43 | P1192 | SG | Android | direct |
| d74091e8... | bc073178... | 8dbbfa2a... | login | 2025-05-02 05:35:32 | - | ID | iOS | organic |
| 10ae191f... | 0bb46c83... | 940ad560... | page_view | 2025-05-01 06:23:57 | - | ID | iOS | referral |
| 7acf8e8f... | 7928b4be... | 3f8ba03c... | checkout | 2025-09-23 06:44:45 | P1468 | US | Desktop | email |

🔗 Full Dataset Link: 
