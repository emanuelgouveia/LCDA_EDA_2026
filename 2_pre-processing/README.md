# 2. Data Pre-processing

1. Pick a numerical variable $x$ and a particular value of a nominal variable $y$, where $x$ and $y$ are from different tables. What is the average value of $x$ for the value of $y$ you chose?
2. Give a robust measure of the variability of $x$, broken down by values of a discrete variable $z$, different from $y$, but also from a different table than $x$.
3. For a pair of discrete variables $a$ and $b$, from different tables, create a table counting the occurrences of each combination of values. This is called a contingency table.
4. Pick a numerical variable and two discrete variables. Group the numerical variable twice, once by each discrete variable, with different aggregation functions, to get a meaningful quantity. Examples:
    - F1 - Record total points for one driver. Sum over races of each driver, maximum among drivers. Can you do it by nationality?
    - E-commerce - Average order value. Sum over items of each order, average over customers. Can you do it by geography of the customer?
    - Credit cards - Maximum income for a lowest-income customer of a credit card brand. Minimum over customers of each brand, maximum over brands. Can you do it by gender? 
5. Take a text variable and make it standardized by converting it to lowercase and removing all outer spaces and punctuation.