**Bike Rental**

**Overview:**

This Solidity smart contract, named "BikeRental", facilitates the rental of bikes. It is designed to be deployed on the Ethereum blockchain and provides functionalities for renting bikes, setting customer age, and recording distance traveled.

**Features:**

1. **Owner Functionality:**
   - The contract owner has exclusive rights to rent bikes. Only the owner can initiate bike rental transactions.
   - Rental of only one bike at a time is allowed for the owner.

2. **Age Verification:**
   - Customers must specify their age before renting a bike.
   - Only customers aged 18 or older are permitted to rent bikes.

3. **Distance Tracking:**
   - The contract records the distance traveled by each customer using the bike.
   - Customers can update the distance traveled through a designated function.

4. **Exception Handling:**
   - The contract includes mechanisms for handling exceptions.
   - If the speedometer reading exceeds 1000, indicating potential bike damage, the transaction is reverted with an appropriate error message.

**Usage:**

1. **Renting a Bike:**
   - Call the `RentBike` function with the desired number of bikes to rent. Only the owner can perform this action.

2. **Setting Customer Age:**
   - Call the `setCustomerAge` function and provide the age as a parameter. This function sets the age of the customer renting the bike.

3. **Recording Distance Traveled:**
   - Use the `DistanceTravelled` function to update the distance traveled by a customer using the bike. Ensure the speedometer reading is within the acceptable range (not greater than 1000).

**License:**

This smart contract is licensed under the MIT License. See the SPDX-License-Identifier tag in the contract file for details.
**Author** 

Venkatesh 

svenkatesh2111@gmail.com

