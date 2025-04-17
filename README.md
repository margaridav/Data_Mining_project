# ABCDEats Inc. Customer Dataset

## Overview

This dataset contains anonymized customer data from **ABCDEats Inc.**, representing user behavior over a three-month period. Each row corresponds to a single customer, and the dataset includes various attributes capturing demographics, ordering patterns, and preferences.

---

## Columns Description

| #  | Column Name     | Description |
|----|------------------|-------------|
| 1  | **customer_id**    | Unique identifier for each customer. |
| 2  | **customer_region**| Geographic region where the customer is located. |
| 3  | **customer_age**   | Age of the customer. |
| 4  | **vendor_count**   | Number of unique vendors the customer has ordered from. |
| 5  | **product_count**  | Total number of products the customer has ordered. |
| 6  | **is_chain**       | Indicates whether the customer’s order was from a chain restaurant (Boolean). |
| 7  | **first_order**    | Number of days from the start of the dataset when the customer first placed an order. |
| 8  | **last_order**     | Number of days from the start of the dataset when the customer most recently placed an order. |
| 9  | **last_promo**     | The category of the promotion or discount most recently used by the customer. |
|10  | **payment_method** | Method most recently used by the customer to pay for their orders. |
|11  | **CUI_<Cuisine>**  | Monetary amount spent by the customer on specific cuisines (e.g., **CUI_American**, **CUI_Asian**, **CUI_Chinese**, **CUI_Italian**, etc.). |
|12  | **DOW_0** to **DOW_6** | Number of orders placed on each day of the week (0 = Sunday, ..., 6 = Saturday). |
|13  | **HR_0** to **HR_23** | Number of orders placed during each hour of the day (0 = midnight, ..., 23 = 11 PM). |

---

## Notes

- The dataset provides a granular view of customer preferences and behavior, which can be used for clustering, segmentation, or predictive modeling.
- Cuisine-related columns (**CUI_**) and time-based columns (**DOW_** and **HR_**) offer rich insights into temporal and taste preferences.

---

Happy Analyzing! 🍽️
