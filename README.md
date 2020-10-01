# Monte Carlo Simulations
### Computational Economics Project 1

This project contains monte carlo simulations for the Ascending Clock Auction and Vegas Hotel Profit Projections.

## Ascending Clock Auction:

**Rules for Ascending Clock Auction:**

An ascending clock auction is an auction where the seller starts bidding at a low price and gradually raises the price as the auction progresses. As the price increases, bidders can choose to stay in the auction (bid for the item at the clock price) or drop out and forgo their chance at winning the item. The clock price is usually raised by a fixed discrete increment. The auction ends when there is only one bidder remaining. The winning bidder gets the item and pays the posted price (clock price from the last round with multiple bidders). A reserve price is the minimum price a seller is willing to accept to sell the item. If the final clock price is below the reserve price the seller receives zero revenue. This means, with a reserve price, the auction now ends when either there are zero buyers bidding at the current clock price, or there is one buyer bidding and the reserve price has been met.

*For this simulation, assume the following parameters:*
- Buyer values are drawn between 0 and 100 in increments of 5
- Seller reserve prices are allowed to be between 0 and 100 in increments of 5
- The item is considered sold when the clock price is greater than or equal to the reserve price
- The auction ends when there is one or less buyers bidding at the clock price.
- In the case of two buyers dropping out at the same price, you can go back to the previous price and randomly choose the winning buyer.
 
**The problem:**

- Find expected revenue if there are 5 buyers and the clock increment is $1.
- Find the expected revenue if there are 5 buyers and the clock increment is $10.
- Find the expected revenue if there are 20 buyers with a clock increment of $1.
- Find the reserve price that the seller should choose.

## Vegas Hotel Projections:

**Rules:**

We have the following model:

*We have the following rules:*
- You begin in year 1.
- The main competitor currently has no hotels.
- They can only build one hotel at a time.
- A hotel takes m years to build.

**The problem:**

Find the expected profit over the next T years, where T = 10 and m = 2. 

#### Emily Daskas
