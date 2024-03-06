**WindEnergy**

This is a smart contract written in Solidity, a programming language used for creating smart contracts on the Ethereum blockchain. The contract is designed to manage wind energy production.

**Contract Overview:**
- The contract is named `WindEnergy`.
- It has three state variables:
  - `targetEnergy`: Represents the target energy to be produced (set to 10000 by default).
  - `currentEnergy`: Tracks the current amount of energy produced.
  - `windFlow`: Indicates the current wind flow, which contributes to energy production.

**Functions:**
1. **Constructor:** Initializes the `currentEnergy` and `windFlow` variables to 0.
2. **Reach_TargetEnergy:** External function that updates the `windFlow` and adds it to `currentEnergy`. It ensures that the provided wind flow is greater than 20.
3. **Check_speed:** External pure function that checks the speed of a fan. It ensures that the fan speed is within a specified range (greater than 0 and not exceeding 5).

**License:**
This contract is licensed under the MIT License, which allows anyone to use, modify, and distribute the code for any purpose.

**SPDX-License-Identifier: MIT**

**Author**

Kiran 

kirandesh0011@gmai.com
