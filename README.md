# The Banking Game

The setup of the game and rules are as follows:
1) There will be 3 groups. No collusion is allowed.
2) You will be endowed with a starting amount of $25m equity capital in the form of cash on your virtual bank balance sheet (you manage and construct your own balance sheet).
3) Each play of the game is a single period game (single period = 1 year).
4) You may issue zero-coupon bonds to raise funds at the stated interest rate in order to fund your loans at a rate of 1% (i.e, you as the bank can borrow external funds to lend at 1% interest).
5) You will be presented with historical data on a set of borrowers, including whether they defaulted or not, the amount of the loan, and other information on their credit quality (such as earnings info). You can use this data to make your own credit scoring model. 
6) You will be presented with a simulated/virtual “market” which is comprised of several individuals (500 of them) seeking loans (not the same individuals in the historical data, but from the same population). Since there are so many, you will need a systematic way to evaluate the loans. All loans will be single period, zero coupon loans (for simplicity). Each (simulated) potential borrower will state the amount of the loan they want, as well as the maximum interest rate they are willing to pay on the loan. If you want to issue a loan to one of the simulated agents, you must offer the loan to them at an interest rate at least as low as their maximum stated willingness to pay rate. You will also be provided with other information on each borrower (the same variables as in your model above). We will assume any defaulting loans have an LGD of 100%. You will want to implicitly load your interest rate to both cover your spread, and your expected costs of defaults. The catch is that you will also be competing for loan volume with the other groups.
7) Bids for loans (i.e., in the form of the interest rates you will be willing to lend) must be in 1/4% increments. You may not enter the same bid as an existing bid from another group (if you do, you bid will be auto deleted). If you enter in a bid that is not in a 1/4% increment (e.g., 1%, 1.25%, etc.) then your bid will also be deleted automatically.

Once the game begins, there will be several steps, as follows:
Step 0, competing for loans: Several minutes of open live-bidding will take place whereby each bank may (for each loan), provide offers to each potential simulated borrower. This will happen live online and you will compete with the other groups/banks for these loans. You need not offer to make a loan to each potential borrower (in fact, you will not have enough capital to do so), and some borrowers will in fact be poor credit risks who will be demanding interest rates that are too low, that on average you would not want to offer. 
The point of the "game" is to figure out better than the other groups, which of the potential borrowers are good credit risks, and who are bad credit risks, then bid appropriate amounts for those loans. The bidding is dynamic, in that you can change your bid in response to other groups if they in turn bid a lower interest rate than you. 
There will be a large number of loans you will need to make, so you will need a systematic way of scoring and making decisions on which loans to compete for.
During this round, you can also indicate how many bonds you wish to issue in order to fund the transactions. A timer will be set for the round, and whoever offers the lowest interest rate to each borrower will be awarded that loan. Once the round is up, no more bidding or issuing of bonds may occur. 
Step 1, Loans issued (Beginning of loan period): At this point, you will prepare the following:
1)	A beginning of period balance sheet, 
2)	Report your capital position (you will be assessed as to whether you correctly calculate this given the loans you choose and meet the minimum capital ratio. Here we will simply define the relevant capital ratio as the ratio of equity to loan assets. This ratio must be maintained above 8%, and you also must have a non-negative cash position. Note that you will be graded on this portion since it is feasible to--with 100% certainty--arrange your portfolio to attain this state at the initial stage at the beginning of the year immediately after loans issue.  
3)	To prevent groups from simply not issuing loans, you also must remain competitive by levering your capital and making enough loans to attain no greater than a 20% equity to loan-assets ratio.
4)	Prepare based on your loans portfolio and debt issued, what your forecasts are for a) Interest Revenue, b) Expected Losses, c) Expected Default Rate (dollar weighted), d) Interest Expense, e) Net Interest Income, and f) end of period expected balance sheet values (cash, equity, retained earnings, etc.).
Step 2, Observe loan performance (End of loan period): Loans performance for the year will then be simulated, and we will observe which loans defaulted and which loans paid in full. The simulated loans will be calibrated to the data that we provided previously, so the best model on average will do the best predictions. Since these are all essentially zero coupons instruments, all loans will close, and you will also repay all debt you have issued with interest at this period. You will then prepare your end-of-period actual balance sheet and earnings statements, PD’s, etc. as above, and again be assessed as to whether you maintained an appropriate capital ratio of 8%, as well as a non-negative cash position. Since there is a degree of randomness, you will not be deducted points in this sections for falling into conservatorship as long as you initially had met your capital ratio in step one. However, you will not be eligible for extra credit. The group who makes the largest profit, provided they maintained appropriate capital ratios and liquidity.












