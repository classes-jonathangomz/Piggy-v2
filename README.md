# Exam:
### Points to evaluate:
- [ ] Write a Smart Contract that store PiggyBanks following the next rules (25%):
  - A PiggyBank will be created by the user with only three fields:
    a) finishDate: The date when the PiggyBank will be broken*.
    b) userAddress: The address of the user who is the owner.
    c) balance: The amount of Ether inside the PiggyBank.

  - The funds only will be avaliable when the finishDate is pass.
  - Only the owner will be able to see his balance.
  - Everyone can add funds to PiggyBanks of others, but only if the receiver have a PiggyBank created.
- [ ] Compile (35%)
- [ ] Tests (35%)
- [ ] Deploy (5%)

* Search for how to store a date in Solidity.

### How I'm going to qualify?
Every repository will have the the code that meets the requirements.

**After the deadline I'm gonna edit this file to let you know how much do you get from every point.**

### Why that percentaje?
- **The code** is not easy part. You need to have the logic and understand the rules.
- You can have good logic and write the code but if this doesn't **compile** it doesn't work.
- **Test** are essential to work with Smart Contracts (and general development) and you need to be able to write _**good tests**_.
- **The deployment**, in this case, is the easiest point.

### **Bonus**

- [ ] Write a Smart Contract that generate a random number.
  - I doesn't care the range of the random number.
