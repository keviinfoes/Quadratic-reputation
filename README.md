# Quadratic-reputation
A new implementation of quadratic voting named quadratic reputation.

## Introduction 
I propose a new implementation of quadratic voting named quadratic reputation. The idea is to use the quadratic voting principle in a reputation system. This would mean the reputation of an individual user is determined by the square root of the reputation points they earn in the reputation system. The difference with quadratic voting is that the points are stored (added to the accounts reputation) and do not result in a single conclusion (vote outcome).

Currently reputation systems primarily use a linear approach in determining the reputation of a user. A user for example would get one reputation point per work/step needed in the reputation system. This creates a strong divide in high and low reputations and does not incentivise new users in generating a reputation when it is dominated by old users. By using a quadratic reputation the initial growth in reputation is high and as your reputation is higher growth will decrease. This is an incentive for new users to join and create a reputation and also for old users to actively participate in the reputation system (or other users will receive higher reputations). 

## Example
A potential implementation for gitcoin is to use quadratic reputation in the bounty program. Where a user receives a square root of reputation points based on the amount earned from the bounty. This would incentivise the user to participate in more bounties with lower payment. The reputation of a user can be used as bar for submission for high profile bounties.

## Conclusion
A test of quadratic reputation seems to fit perfectly in the goal of gitcoin as it is an incentive for user to perform work for multiple bounties (also bounties with lower reward). This would in turn potentially increase the bounties added by users, as more lower value bounties are performed.
