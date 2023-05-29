# Bank Account

## Instructions

Create a class BankAccount with properties accountNumber and balance. Add a method deposit(amount) that increases the balance by the amount parameter. Add a method withdraw(amount) that decreases the balance by the amount parameter. Create a subclass SavingsAccount that extends BankAccount, and has an additional property interestRate. Override the withdraw(amount) method of the SavingsAccount class to ensure that the balance cannot be reduced below zero.

## ample Input:

```
let savingsAccount = new SavingsAccount("123456789", 1000, 0.05);
console.log(savingsAccount.balance); // 1000

savingsAccount.withdraw(500);
console.log(savingsAccount.balance); // 500

savingsAccount.withdraw(600); // Insufficient balance
```
