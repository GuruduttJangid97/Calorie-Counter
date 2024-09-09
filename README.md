## Overview

The **Calorie Counter** is a web application designed to help users track their daily calorie intake. It enables users to set a daily calorie budget, log their food consumption and exercise activities, and calculate the remaining calories based on their budget.

## Features

- **Set Daily Calorie Budget**: Input your daily calorie limit.
- **Track Meals and Exercise**: Add entries for breakfast, lunch, dinner, snacks, and exercise.
- **Dynamic Entry Addition**: Add multiple entries for each category dynamically.
- **Calculate Remaining Calories**: Compute remaining calories based on logged entries.
- **Clear All Entries**: Reset the form to start fresh.

## Demo

You can view a live demo of the application [here](#) (replace with the actual link if available).

## Getting Started

To run the Calorie Counter locally:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/GuruduttJangid97/Calorie-Counter.git
   cd Calorie-Counter

2. **Open the Project**
Open the index.html file in your web browser.

3. **Explore the Application**
You should see the Calorie Counter app. Use the form to set your calorie budget and log your food and exercise entries.
Project Structure

index.html: Provides the HTML structure for the application.
styles.css: Contains the CSS styles for the application.
script.js: Includes the JavaScript code for functionality and interactions.
Usage

Set Your Daily Budget: Enter your daily calorie budget and press Enter.
Add Entries:
Select a category (Breakfast, Lunch, Dinner, Snacks, Exercise) from the dropdown.
Click "Add Entry" to add a new entry for the selected category.
Enter the name and calorie count for each entry.
Calculate Calories:
Click "Calculate Remaining Calories" to view the remaining calories based on your budget and logged entries.
Results will indicate if you are in a calorie surplus or deficit and provide a summary of your calorie usage.
Clear Entries: Click "Clear" to remove all entries and reset the form.
Styling

Styling

The application uses the following styles:

Color Scheme:
<ul> 
   <li><span style="background-color: #f5f6f7; color: #000000;">Light Grey</span></li> 
   <li><span style="background-color: #0a0a23; color: #ffffff;">Dark Blue</span></li> 
   <li><span style="background-color: #1b1b32; color: #ffffff;">FCC Blue</span></li> 
   <li><span style="background-color: #fecc4c; color: #000000;">Light Yellow</span></li> 
   <li><span style="background-color: #feac32; color: #000000;">Dark Yellow</span></li> 
   <li><span style="background-color: #ffadad; color: #000000;">Light Pink</span></li> 
   <li><span style="background-color: #850000; color: #ffffff;">Dark Red</span></li> 
   <li><span style="background-color: #acd157; color: #000000;">Light Green</span></li> 
</ul>

addEntry(): Adds a new entry input field to the selected category.
calculateCalories(e): Computes remaining calories based on budget and entries, and displays the result.
getCaloriesFromInputs(list): Calculates total calories from input fields and handles invalid inputs.
clearForm(): Clears all entries and resets the form.
Contributing

Contributions are welcome! To contribute:

Fork the Repository.
Create a Branch for your feature or fix.
Commit Your Changes.
Push to Your Branch.
Create a Pull Request.
