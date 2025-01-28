# IAU-Letter-Grade-Calculator

This is a C++ program designed to calculate the letter grade based on a student's score and average score, using a predefined grade chart. The program prompts the user to input their score and average, then outputs the corresponding letter grade from the chart.

## Features

- Accepts user input for score and average.
- Provides validation to ensure inputs are within the specified range.
- Displays the corresponding letter grade based on the input values.
  
## Grade Chart

The program uses a grade chart, where the rows represent different score ranges and the columns represent different average ranges. The values in the chart correspond to the letter grades.

## Requirements

- C++11 or later.
- A C++ compiler that supports standard libraries like `<iostream>`, `<sstream>`, `<vector>`, and `<limits>`.

## How to Use

1. Clone or download this repository to your local machine.
2. Compile the `IAU-Letter-Grade-Calculator` source code using a C++ compiler:
    ```bash
    g++ -o grade_calculator main.cpp
    ```
3. Run the compiled program:
    ```bash
    ./grade_calculator
    ```
4. Enter your score (between 30 and 90) and average score (between 20 and 70) when prompted.
5. The program will output the corresponding letter grade.

## Example

```
Enter your score (30 to 90): 45
Enter the average score (20 to 70): 35
The letter score of score 45 and average 35 is: CB
```

## License

This project is licensed under the MIT License.
