# ADE Syrup Pool FAQ

## FAQ

### What lock duration can we choose?

You can choose from 1-52 weeks. What do you prefer?

### What variables affect the new ADE Syrup Pool APYs (Flexible and Fixed-Term Staking options)?

Since flexible staking and fixed-term staking options are part of the same pool, the following variables affect the APY of both:

* Total ADE staked in flexible staking and fixed-term staking (the sum of both). The more ADE staked, the lower the APY.
* Total locked ADE in fixed-term staking. The more ADE locked means more yield boosts, resulting in fewer ADE rewards for others (especially flexible staking).
* The average lock duration of all ADE locked in fixed-term staking. If the average lock duration increases, APY will decrease.

### Can I harvest the rewards during the locked period?

No. You can harvest the rewards only when the locked duration is ended. This is based on the yield/return we are providing as well as the technical implementations.

### Can I extend the lock duration?

Yes. Extending the lock duration adds more time to your **initial lock duration**. When choosing to extend your lock duration, note:

New extended lock duration = initial lock duration + added duration

### Can I remove my ADE from Fixed-Term staking via contract if I change my mind?

No. Your ADE cannot be removed or withdrawn from fixed-term staking at any point in time until your lock duration ends and your ADE is unlocked.

### What is the "ADE Locked" amount?

The "ADE Locked" amount is a user's initial locked ADE balance plus ADE rewards to date.&#x20;

ADE Locked = Initial locked ADE balance + ADE rewards

When adding more ADE to fixed-term staking, the "ADE to be locked" amount is the user's initial locked ADE balance, ADE rewards to date, and the ADE being added.

### Can the Fixed-Term Staking ADE pool APY change after I lock my ADE?

Yes, the fixed-term staking ADE pool APY is variable, just like the old ADE pools. The fixed-term staking ADE pool APY is not fixed and is dependent on:

* Total ADE staked in the ADE pool (the sum of both Flexible + Fixed-Term Staking).
* The average lock duration of all ADE locked in fixed-term staking.
* A yield boost (similar to a multiplier) calculated from a user's initial lock duration. The longer you lock your ADE, the higher the yield boost.

For example, if you lock your ADE for 52 weeks, your yield boost will be larger than if you lock your ADE for 26 weeks. The yield boost increases linearly the longer you lock your ADE.

### Can I vote if my ADE is locked in the Fixed-Term Staking pool?

TBD, more information will be provided soon.

### Can I use both the Flexible Staking ADE pool and the Fixed-Term Staking ADE pool at the same time?

No. As mentioned above in the "What’s the difference" section, both options are part of the same, single pool. You currently can **never** have ADE in both fixed-term and flexible staking.

We have multiple solutions coming in the future to allow users to use both flexible staking and fixed-term staking at the same time, but for now, you can choose only one of them.

### Is there a fee for converting Flexible Staked ADE to Fixed-Term Staked ADE?

No. There are no additional fees for moving ADE from flexible staking to fixed-term staking, only network fees.

### What happens at the end of the lock duration? What is "After Burning"?

When your fixed-term staking period ends, and your ADE unlocks, you have 7 days to complete one of two options:

* Lock your ADE to begin a new fixed-term staking period\
  or
* Convert your staked ADE to flexible staking (no 72-hour withdrawal fee).

![](../../../.gitbook/assets/cake-pool-lock-end.png)

During these 7 days, you will still earn ADE.

After 7 days, if you have not done one of the two options, your staked ADE will enter what is called "After Burning". With "After Burning", your ADE rewards will start to be sent to burn. The % of ADE rewards being sent to burn will linearly increase in the 90 days "After Burning" period until it reaches 100%, which means all the ADE rewards are burnt.

So, to avoid missing out on ADE rewards, we recommend starting a new fixed-term staking period or converting your ADE to flexible staking at the end of your lock staking period.

![](<../../../.gitbook/assets/cake-pool-lock-burn (1).png>)
