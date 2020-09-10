---
published: true
---
### 4.5: 
### Using the technique suggested here, where natural language descriptions are presented in a standard format, write plausible user reqiurements for the following functions:

### An unattended gas pump system that includes a credit card reader. The customer swipes the cards through the reader, then specifies the amount of fuel required. The fuel is delivered and the customer's account debited.

User Requirements: 
- System can accept any brand of card
- System can cancel transaction
- System can check if fuel is available
- System checks if card has necessary funds
- System can increment/decrement amount of fuel
- System stops pumping once desired amount of gas is reached

### The cash-dispensing function in a bank ATM.

User Requirements: 
- System can accept only cards from its specified bank
- System has to read entered pin and verify it
- System has option to withdraw or deposit cash
- System checks if there are necessaruy funds in account to complete desired transaction
- System deispenses exact amount of desired cash
- System asks if transaction is complete
- System needs to be able to return card to user

### In an internet banking system, a facility that allows customers to transfer funds from one account held with the bank to another account with the same bank.

User Requirements:
- System must require access to both account (password)
- System must ask for a confirmation on amount being transfered
- System must check accounts for sufficient funds
- System checks for secure connection between accounts
- System shows new transfered money in account.

### 4.6: 
### Suggest how an engineer responsible for drawing up a system requrements specification might keep track of the relationships between functional and non-functional requirements.

One way to keep track of the relationships between functional and non-functional requirements is to include some kind of graph or chart to plot everytime they interact with one another. Similar to a binary tree, you could start from each beginning requirement (root) and stem to each requirement that stems after that. You can create a tree for functional and a tree for non-functional requirements and associate the root of the non-functional tree to the root of the functional tree and everytime a new requirement stems from another, you can record the non-functional requirement that related to the functional requirement. 

### 4.7: 
### Using your knowledge of how an ATM is used, develop a set of use cases that could serve as a basis for understanding the requirements for an ATM system.

Use Case: Entering Pin. The user will enter a pin to match his card and the system must check if that pin is a match for that card.

Use Case: Withdrawing Money. The user will specify an amount to withdraw and the system will check if there are sufficient funds in the account. If there are enough funds, the money with wthdrawal.

Use Case: Depositing Money. The user with specify desired amount and account they want to deposit to and system deposits it.

Use Case: Transfer Money between accounts. The user will transfer money from either checking to savings or vice versa if they so desire. The System will validate the transfer and the amount in the account will change.

### Article Reflection
All software has its flaws and weak points. But as software engineers, it is our job and responsibility to test every possible success and failure in order to ensure the software is reliable. Software engineers can be held accountable for leaks in data or infiltrations of software even after the code is released. In the 114th congress bill, it is stated that people in violation of Cybersecurity standards can be penalized $5,000. This is why you need to create as many text cases possible in order to prevent infiltration. 
According to “The Magical Number Seven, Plus or Minus Two”, a human can only carry about 7 things in their memory space at a time. Even if you thought about every possible test case, there are still more that have probably slipped your mind. A big way to prevent hackers and bugs in your software, you need to follow the concept of Test Driven Development. The way this concept works is you create your test, then you create the code to successfully complete the test. If you do not pass the test, you make changes and run the test again. If the test fails again, then new tests must be made, and the process repeats until you pass all the tests. The more test cases you make, the more you plan and prepare for the inevitable flaws in your software.

