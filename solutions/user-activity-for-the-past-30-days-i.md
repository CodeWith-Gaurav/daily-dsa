# User Activity for the Past 30 Days I

**Status:** Accepted
**Language:** mysql
**Date:** 2025-12-05

## Learning Reflection
Implemented a SQL query to solve the "User Activity for the Past 30 Days I" problem on LeetCode, utilizing the concept of window functions to efficiently process the activity data and calculate the daily active users. Specifically, I leveraged the ROW_NUMBER function to assign a unique row number to each user on each day, and then utilized a window function to count the number of users with a row number less than or equal to the current row number. This approach allowed me to accurately calculate the daily active users within the given time frame.