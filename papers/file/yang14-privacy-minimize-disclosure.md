## [Minimizing Private data disclosures in the smart grid](http://dl.acm.org/citation.cfm?id=2382242)

### Summary

### Model
- observed load change: e'(t)
- real load change: d'(t)
- Objective: to provent leaking of information in the demand load change 
  - One approach is to maintain the observed load as a constant, however, this approach will require a very large battery.

### Algorithm-Stepping Framework (SF)
- Objective: maximize the difference between the demand load and external load
- **Lazy-Stepping**
  - try to maintain the external load unchanged as long as possible
- **Lazy-Charging**
  - try to keep charging the battery until the battery is full and then keep discharging the battery until it is empty
- **Random-Charging**
  - randomly choose whether to charge or discharge the battery
  
### TODO
- check how they compare the algorithms
