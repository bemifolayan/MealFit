# MealFit

This Python script retrieves nutrition data for a given food item from the API-Ninjas API. It will also calculate the amount of calories shed doing a particular activity using the API-Ninjas CaloriesBurned API. It will be used to help people who want to gain/maintain weight.

## Prerequisites

- Python 3
- requests library
- pandas library 
- sqlalchemy library 

## Getting Started

1. Clone the repository.

2. Install the required libraries.

3. Obtain an API key from API-Ninjas (https://api-ninjas.com/) and set it as an environment variable named `API_KEY`. (Security Reasons)

4. Run the script by executing the following command:
   ```
   python pair-programming.py
   ```

5. Enter the name of a food item when prompted to retrieve its nutrition data. Ex: Brisket

6. Enter the name of the activity you want to participate in

7. The script will make an API request to API-Ninjas, retrieve the data, and display it in the console. 

8. The data will also be saved into a SQLite database file named `food_data.db`.

9. The amount of hours you should spend will be displayed to you.
