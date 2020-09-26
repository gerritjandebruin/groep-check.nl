# groep-check.nl

This repository server https://groep-check.nl, a website that allows you to calculate the probability that at least one person in a group is infected.
Currently, we calculate this in the following way:

(1) `p_group = (1 - (1-p_individual) ** n)`

In this formula, `p_individual` is the probability that one person is infected, `n` the number of people in group and `p_group` the quantity of interest.
