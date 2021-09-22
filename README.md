# investment-portfolio-rebalancing
Project undergone during the 2019 coop period.

## Project breacdown & summary

An investment portfolio is a set of invested assets being managed as a whole, with each asset holding a certain allocation of the total invested amount. As the value of these assets evolve over time due to the changing market, the relative allocation of each allocation also changes. This, coupled with the fact that the maintenance of a balanced portfolio is proven to make more money for an investor than the concept of always buying low and selling high, is reason to have a periodically rebalanced portfolio. Rebalancing a portfolio simply consists of returning assets back to their original allocations by buying into poorly performing stocks and selling from the wellperforming ones. 

However, this optimization of this process can be very time consuming for the investor. They are tasked with finding the least financially demanding approach to accomplishing this, and often can unnecessarily lose money due to transaction costs and following the wrong sequence of steps to reach this target portfolio. The standardization of this process in an application can be beneficial for investors and people wanting to learn to properly invest alike. It would provide an efficient solution to rebalancing, as well as a most efficient solution to reach a rebalanced portfolio.  

To solve this, a portfolio rebalancing tool was created as a web application to make rebalancing a simple task of inputting a current portfolio and the target allocations of that portfolio. In the early processes of design, a potential end user was consulted to better understand the need for this solution and the necessary features it may have. Several designs for the user interface of the tool were then considered, and a decision was made for the one to be implemented. Design requirements for the interface were decided, and upon the creation of the front end of the algorithm, were met. Similarly, the back end had several steps in design, each requiring testing before proceeding to next steps. Additionally, algorithms for establishing the best approach for next best actions needed to reach a target portfolio were discussed and evaluated, however it was not possible to identify the formula that optimized all given scenarios. 

It was concluded that the algorithm had an overall success, with the exception of its inability to optimize next best actions in the presence of a tolerance level on investments. As the user interface met all design requirements decided upon in the brainstorming process, it was also a success. Several recommendations were made at the completion of the project, including the addition of several features to improve user experience. It was also proposed to keep track of user portfolios over time to better understand user risk levels, which would influence rebalancing in future, more advanced versions of the algorithm. 
