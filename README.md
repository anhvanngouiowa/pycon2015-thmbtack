Pass in a string of digits where the last digit is the answer and this will determine if there is a possible combination of digits and operands that evaluate to the final answer.

Examples:

❯❯❯ echo '3 2 1 4 5 6 3' | python3 beer.py
3 + 2 + 1 - 4 - 5 + 6 = 3  (21 solutions tried)

❯❯❯ echo '1 2 3 5' | python3 beer.py
1 * 2 + 3 = 5  (9 solutions tried)