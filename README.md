# Lending-Club-Loan-Defaulter-Prediction

# Peer-to-Peer Lending
Peer-to-peer lending refers to the practice of lending money to individuals (or small businesses) via online platforms that match anonymous lenders (or investors) with borrowers.
Lenders typically earn higher returns relative to investment products offered by banks. However, there is of course the risk that the borrower defaults on his or her loan.
The intermediary platform (such as Prosper or LendingClub) generates revenue by collecting
fees on funded loans (from borrowers) as well as on servicing (from investors).
The peer-to-peer lending industry in the United States started around 2006 and by 2012,
LendingClub was the largest peer-to-peer lender based on issued loan volume and revenue.
Peer-to-peer lending has been one of the fastest growing investments, with ∼16 billion in
loans reportedly originating from LendingClub by the end of 2015

# Investing on Lending Club
As of 20203, LendingClub interest rates ranged from 6.7% to 22.8% (depending on the
loan duration and the borrower’s rating), and the default rates varied between 1.3% and 10.6%.
Based on these statistics, you believe that becoming a loan investor on LendingClub.com
could be a good idea. Therefore, you go ahead and collect more information on how investments work and find out about the following information.
* LendingClub issues loans between $1,000 (min) and $40,000 (max).
* Each loan is issued for a duration of either 36 months or 60 months.
* Each loan is split into multiples of $25, called “notes” (e.g., for a $2,000 loan, there
will be 80 notes of $25 each). An investor can purchase any number of the notes of
a loan (in a similar manner to “shares” of a stock). The total amount of the loan is
typically invested by multiple investors.
* LendingClub categorizes its loans using a grading scheme (grades A, B, C, D, E, F,
and G where grade A corresponds to the loans judged to be “safest” (i.e., least likely
to default).
* LendingClub sets the interest rates based on the borrower’s credit history. Of course,
the safer the loan the lower the interest rate, and so as an investor, you would have to
balance risk and return when deciding which loans to invest in.
* Individual investors can browse loan listings online (See Figure 1.1). From here, investors can obtain more detailed information on each loan by clicking on it within the listing

# The Data
In this project, we will use the historical data from loans that were issued on LendingClub
between April 2008 and September 2019.
The dataset contains more than hundred features, including the following, for each loan:
1. Loan amount
2. Interest rate
3. Monthly installment amount
4. Several additional attributes about the borrower (type of house ownership, annual
income, monthly FICO score, debt-to-income ratio, number of open credit lines, etc.)
5. Loan status (e.g., fully paid, default, charged-off)
Current refers to a loan that is still being
reimbursed in a timely manner. Late corresponds to a loan on which a payment is between
16 and 120 days overdue. If the payment is delayed by more than 121 days, the loan is
considered to be in Default. If LendingClub has decided that the loan will not be paid off,
then it is given the status of Charged-Off.
In short, each loan expires 5 months after the term of the loan has ended, and ends in
one of two LendingClub states—fully paid or charged-off. In the former, the investor is
reimbursed fully for the balance plus interest, and has earned positive return. The latter,
on the other hand, causes loss depending on how much of the loan was paid of before being
charged-off.

# The objective
The objective of this project is to predict the probability of default for a loan and the return on a loan using ML. Based on that, we test out different investing strategies.
