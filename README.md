## Background

I have created 3 contracts that each serve a purpose. First contract is to split any business profits among employees. I named it AssociateProfitSplitter.
It allows to:

* Pay your Associate-level employees quickly and easily.

After creating the contract you can execute it as such: 

![contract](./Resources/AssociateProfitSplitter.PNG)

The second contract called TieredProfitSplitter allows you to:

* Distribute profits to different tiers of employees.

such as: ![contract](./Resources/TieredProfitSplitter.PNG)

The third contract called DeferredEquityPlan.sol allows you to:

* Distribute company shares for employees in a "deferred equity incentive plan" automatically.

After compiling the contract you run it as such by first fastforwarding the first year to be allowed to distribute the years vested shares:
Originally I already have 250 shares released and am starting from there:


![contract](./Resources/DeferredEquityPlan.PNG)

Next:

![contract](./Resources/DeferredFastForwarding.PNG)

Then distributing the shares:

![contract](./Resources/DeferredDistribute.PNG)

Finally checking the shares released:

![contract](./Resources/DeferredSharesReleased.PNG)

## Thank you
