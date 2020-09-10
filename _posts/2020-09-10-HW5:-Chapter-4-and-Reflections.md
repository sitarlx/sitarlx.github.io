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
