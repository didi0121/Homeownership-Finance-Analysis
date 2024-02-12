# Homeownership-Finance-Analysis
Homeownership Finance Analysis: Mortgage Amortization and Point Purchasing Strategies

This project involves using Python to address the financial aspects of purchasing a home, focusing on mortgage calculations and decision-making regarding points.

Suppose you want to get a 30-year mortgage on a $400,000 home. You can get a 7.1% annual mortgage rate that is compounded monthly when you make a 20% down payment (so the initial loan principal will be $400,000 minus 20% of that value). 

The fixed monthly payment $PMT$ on a mortgage is given by the annuity formula:

$$
PMT = P \times r \times \frac{(1+r)^n}{(1+r)^n-1}
$$

where $P$ is the initial principal, $r$ is the **monthly** interest rate, and $n$ is the number of months in the mortgage term.

$$
INT_t = B_{t-1} \times r
$$

$$
PRN_t = PMT_t - INT_t
$$

$$
B_t = B_{t-1} - PRN_t
$$

where $INT$ is the interest portion, $PRN$ is the principal portion, and $B_t$ is the outstanding balance of the loan at the end of month $t$. $B_0$, the initial balance, is the initial loan amount $P$.


Part A: Calculate the Amortization Schedule

1. Computes and displays key values such as monthly payment, final payment, final balance, total interest, principal paid, and total payments over the life of the loan.
2. Generates a plot illustrating the principal balance over time, providing insight into the mortgage repayment process.
3. Creates a separate plot showing monthly principal and interest payments over time, identifying the approximate year when these payments intersect.

Part B: Choosing Points

1. Refactors code from Part A into a function that calculates the present value of the mortgage based on points, interest rate, and months until selling the house.
2. Utilizes the function to determine the optimal decision of whether to purchase points based on the duration of residency in the house. Considers different scenarios and potential discount rates, providing insights through printing or plotting relevant results.
3. Overall, the project offers a comprehensive analysis of mortgage amortization and decision-making strategies related to purchasing points, aiding individuals in making informed financial choices when buying a home.

