# Renocrew-Task


## Overview

This Python script is a simple restaurant recommender system. It allows users to input a type of food, and the system provides restaurant recommendations based on the user's input.

## How to Use

1. **Run the Script:**
   - Execute the script by running `python renocrew.py` in the terminal.
   - The script will prompt you to enter a type of food.

2. **Enter a Type of Food:**
   - Input the type of food you are interested in when prompted.
   - Press Enter to submit the input.

3. **View Recommendations:**
   - The script will display a list of recommended restaurants that match the entered cuisine.
   - Recommendations are sorted by rating in descending order and proximity in ascending order.

4. **Exit the Program:**
   - To exit the program, simply press Enter without entering any cuisine type.

## Implementation Details

### Restaurant Class

The `Restaurant` class is defined with attributes such as `name`, `cuisine`, `rating`, and `proximity` to represent restaurant details.

### Data Population

The `populate_data_structure` function initializes a list of sample restaurants with different cuisines, ratings, and proximities.

### Recommendation Function

The `recommend_restaurants` function filters restaurants based on user input and sorts them by rating and proximity.

### Error Handling

The script handles errors such as invalid or unavailable types of food and prompts the user to try again.

### Testing

The script includes a set of test cases using the `assert` statement to ensure the functionality of the recommendation function.

## Test Cases

- Test cases cover various cuisine types, including valid and invalid inputs.
- Assertions validate that the recommendation function returns expected results.

## Contributing

Feel free to contribute to this project by forking the repository, making improvements, and creating pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

