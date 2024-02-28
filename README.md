**ElectionCampus**

**Overview:**

The ElectionCampus smart contract is designed to facilitate voting for two individuals (referred to as "personX" and "personY") within a campus or organizational setting. It allows participants to cast their votes for either personX or personY, tracks the total number of votes each person receives, and provides a mechanism for determining the winner based on the vote count.

**Contract Features:**

1. **Voting Mechanism:** Participants can vote for personX or personY by calling the `voteForPersonX` or `voteForPersonY` functions respectively. They specify the number of votes they wish to cast, and the contract updates the total number of votes for the respective candidates.

2. **Nominee Eligibility:** The `nomineeEligibility` function is provided to check if a nominee meets a certain age requirement. Currently, the requirement is set to be above 35 years old.

3. **Result Checking:** The `checkResult` function allows anyone to check the current status of the election. If the total votes for personX and personY are both 50, indicating a tie, the function will revert with a message indicating that a re-election needs to be organized. Otherwise, the function does not revert, allowing the election to proceed.

**Contract Deployment:**

The contract should be deployed with the addresses of personX and personY provided as constructor arguments. These addresses represent the Ethereum accounts associated with each candidate.

**License:**

This smart contract is released under the MIT License, which allows for free use, modification, and distribution under certain conditions. See the SPDX-License-Identifier comment at the beginning of the contract code for more details.

**Author:**

Kiran deshpande

**Contact:**

kirandeshpande0011@gmail.com

**Date:**

28/02/2024
