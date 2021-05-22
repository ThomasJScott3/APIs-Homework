# APIs-Homework

## Summary
This homework is split into two parts. The first part deals with pulling data from two APIs. The first is a public API for cryptocurrency data. The second is Alpaca, which requires a public and secret key. You can [register for one here](https://alpaca.markets/). In addition, Alpaca API information can be found [in the documentation](https://alpaca.markets/docs/api-documentation/). Note: you will need to set up a dotenv file locally so the code can call your key as an environmental variable. I have named my environmental variables so that they mimic the instructor's solution code, that way the evaluator will hopefully not need to alter my code to call their API key. 

The second part of the homework deals with montecarlo simulations. These allow us to run a set number of forecast simulations to ascertain potential returns of a given asset. I have followed the instructions very closely. That being said, I did use dynamic variable names in the second half of the code in case the evaluator wants to adjust weights or possibly even ticker strings. 

I was also able to complete the extra credit portion. The code for each part of the assignment has been tested as well and should run.

## Caveats
- I adjusted the start and end date variables to reflect the most up to date prices for the assets provided. I wanted the hypothetical client to see simulations based on up to date information. If the simulation is based on stale data, then what is the point? The simulation is most effective when it incorporates data based on current market performance in my opinion.
- The JSON for the crypto information is not dynamic. I had to review the output to ensure that the pricing information particular to that JSON was pulled individually.
- I imported the time and datetime libraries in order to get dates in ISO format. My thinking was it was best to use occam's razor and a 'don't reinvent the wheel' approach.
- Finally, a lot of my solution comes from examining the instructor code solutions. I did my best to make alterations where possible, but also wanted to ensure that my solutions comported with the starter code. Consider this a broad citation in this regard. Aside from that, this assignment is my original and unique work.
