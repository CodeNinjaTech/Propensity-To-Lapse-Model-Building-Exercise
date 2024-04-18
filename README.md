# Propensity to Lapse Model Building Exercise

Assignment 3 for the Analytics Practicum II Course of AUEB's MSc in Business Analytics

**Concept:**
A loyalty business partner has provided raw customer transaction data to analyze and predict customer churn. Customers earn points from purchases with affiliated partners, which they redeem for various rewards. The dataset includes fields such as the customer's lapsed status (Active or Lapsed), number of collections, number of redemptions, total collected points, total redeemed points, years in the program, and months since the last transaction.

**Lapse Definition:**
A customer is considered lapsed if they have had no collections or redemptions for 12 consecutive months.

**Collections Definition:**
Customers earn points from purchases with loyalty partners.

**Redemptions Definition:**
Customers redeem points for rewards, such as flights or hotel bookings.

**Task:**
I. Build a machine learning model (using any technology) to predict if a customer with the given characteristics will lapse in the next 12 months.
II. Create a business presentation for the marketing team, including:
   A. Modelling logic
   B. Model findings
   C. Suggestions to reduce churn rates

**Dataset:**
- 5000 observations (customers)
- Fields:
  - State: Lapsed status (Active=0, Lapsed=1)
  - Sum_collect: Number of collections
  - Sum_redeem: Number of redemptions
  - Sum_collect_points: Total collected points
  - Sum_redeem_points: Total redeemed points
  - Years_in_the_program: Years since customer's registration
  - Months_since_last_transaction: Months since customer's last action

**Deliverable:**
Submit a PowerPoint file on the portal by July 31, 2023.
