# Food Delivery Data Analysis

This project combines data from three different sources:
- orders.csv (Transactional data)
- users.json (User master data)
- restaurants.sql (Restaurant master data)

The datasets are merged using LEFT JOINs to create a single source of truth:
`final_food_delivery_dataset.csv`

Analysis includes:
- Order trends over time
- User behavior
- City and cuisine performance
- Membership impact
- Revenue seasonality

Tools used:
- Python
- Pandas
- SQLite
- Google Colab
