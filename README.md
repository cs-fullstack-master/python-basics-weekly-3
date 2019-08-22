# python-basics-weekly-3

## Create a bank program.

Give the user the following options. Once the option that is selected is completed keep asking them until they hit 4 to quit:

```
Hello, please choose one of following options:
1) Check balance
2) Add money to account
3) Withdraw money from account
4) Quit
What will you like to do?
```

#### Check Balance
Check balance should show the current balance. Make sure a $ sign is in the sentence.

<strong>Example:</strong> ```Your account has $200 dollars```

#### Add money to account
Once this selection is chosen, ask the user how much money they want to deposit. Update their account, then print the updated balance.

<strong>Example:</strong> ```How much would you like to deposit?```

<strong>Example:</strong> ```Your account now holds $205 dollars```

#### Withdraw money from account
Once this selection is chosen, ask the user how much money they want to withdraw. If they don't have enough money in the account, print "Insufficient funds". Otherwise, update their account, then print the updated balance.


### Challenge
Before the program starts, ask the user for their account name and a pin number.
- Instead of using "you", use the account user's name
- Before allowing them to withdraw, check to see if they know the pin number. If they don't get the correct pin, ask them to try again.
