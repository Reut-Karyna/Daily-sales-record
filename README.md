# Daily-sales-record

This script processes a daily sales record stored as a string called daily_sales. It performs the following steps:

1. the delimiter ";,;" with a single delimiter ";" to make it consistent.
2. Splits the string into a list of individual transactions using the delimiter ",".
3. Splits each transaction into a list of data points using the delimiter ";".
4. Cleans up inconsistent whitespace in each data point.
5. Extracts the customer name, sales amount, and thread color from each transaction and stores them in separate lists.
6. Calculates the total sales amount for the day.
7. Splits the thread colors that contain multiple colors separated by "&" into individual colors and stores them in a new list.
8. Defines a function color_count(color) that takes a color as input and counts the number of threads sold in that color.
9. Iterates over a list of colors and uses the color_count() function to determine the number of threads sold for each color.
10. Prints a sentence for each color stating the number of threads sold in that color.
11. The final result is a printed statement for each color, indicating how many threads of that color were sold on the given day.
