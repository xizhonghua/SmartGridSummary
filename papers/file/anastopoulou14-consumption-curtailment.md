## [Efficient Incentive-Driven Consumpion Curtailment Mechanism in Nega-Watt Markets]()


### Summary
In this paper, the authors study the load curtail problem. They propose an incentive mechanism that benefit both the consumers and utility operator.

### Model
- Utility operators purchases energy from the wholesale market at time-varying prices and resell it to consumers at fixed tariffs.  
  - Nega-Watt market: a unit of energy that is curtailed-not consumed.
- The operator buys energy from the wholesale market at price C.
- The operator resell the energy to consumers at fixed price p.
- In periods of high demand, there hold C > p
  - Aussme the total demand load for such period is d, then the net loss of the operator is (C-p)*d
  - Thus the opeartor would like to select a consumer to curtail a particular volumn &delta; d of load

### Challenge
- Even if a priori agreement is reached between the operator and a user about the load to curtail
  - It is entirely up to the user to consume the load or not.
  - when obeys the curtail, consumer i receives reward r_i
  - when vilate the curtail, consumer i receives find f_i
  
### Algorithm
- The model the problem as a full information game and dicuss the case of one consumer one producer, and N consumer one producer.

### Question
- How this incentive different from dynamic energy price?

### TODO
- I didn't go into details of how the game works.

