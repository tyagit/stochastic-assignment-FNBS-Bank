# stochastic-assignment-FNBS-Bank
## FNBS Bank:

The First New Brunswick Savings (FNBS) bank opens at 8am and closes at 4pm. The time between arrivals
for the customers follow the distributions given below:
• Exponential 5 minutes between 8am & 11am
• Exponential 4 minutes between 11am & 1pm
• Exponential 6 minutes between 1pm & 4pm

Customers come to the bank for various services. Past data has shown that 50% of the customers come to
withdraw money, 30% come to deposit money and 20% come for other banking services (this is true for all
the three time windows mentioned above). The service time distributions are given in the table below:

Time|Service time for Withdrawal(mins)|Service time for Deposit(mins)|Service time for other services(mins)
------------|-------------------|-------------------|-------------------
8am - 11am| Uniform(3,5)| Uniform(4,6)| Triangular(5,13,18)
11am - 1pm| Uniform(3,7)| Uniform(3,8)| Triangular(4,11,17)
1pm – 4pm| Uniform(4,8)| Uniform(5,9)| Triangular(5,14,19)

In FNBS there are two agents that serve a single queue for both withdrawal and deposit services and two
other agents that serve another single queue for other services. The agents serving the withdrawal & deposit
queue, give higher priority to customers who have come to deposit money.

Simulate the banking operations at FNBS for 2160 minutes and fill-up the following table:
- Total number of customers completing their transactions between 8am-11am
- Total number of customers completing their transactions between 11am-1pm
- Total number of customers completing their transactions between 1pm-4pm
- Total number of customers who enter the bank to withdraw money between 8am-11am
- Total number of customers who enter the bank to withdraw money between 11am-1pm
- Total number of customers who enter the bank to withdraw money between 1pm-4pm
- Total number of customers who enter the bank to deposit money between 8am-11am
- Total number of customers who enter the bank to deposit money between 11am-1pm
- Total number of customers who enter the bank to deposit money between 1pm-4pm
- Average waiting time in the withdrawal-deposit queue between 8am-11am
- Average waiting time in the withdrawal-deposit queue between 11am-1pm
- Average waiting time in the withdrawal-deposit queue between 1pm-4pm
- Average Utilization of the agents serving the withdrawal-deposit customers
- Average Utilization of the agents serving the customers who come for other services
