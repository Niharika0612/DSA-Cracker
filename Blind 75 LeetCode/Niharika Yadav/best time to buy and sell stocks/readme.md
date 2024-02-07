I utilized a direct method that involves traversing through the array of stock prices. At each iteration, I maintained a record of the lowest stock price encountered so far (min_price) and computed the potential profit achievable by selling at the present price (prices[i] - min_price). The maxprof variable, representing the maximum profit, was then updated to retain the greater value between its current state and the calculated profit. Furthermore, I adjusted min_price to be the lesser value between the ongoing stock price and the previously recorded minimum.