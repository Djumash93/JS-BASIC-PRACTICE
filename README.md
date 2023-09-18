# JS-BASIC-PRACTICE - 

This project is a skeleton banking app, where you are able to execute basic banking functions such as - deposit, transfer, take a loan, withdraw. 
In the JS code you will see the labelled classes such as button Login, to which then I have added event listeners. 



These Event listeners then perform the functions for which they are designated, for instance the transfer button will transfer from one account to another.
The current account then has to log the withdrawal on the UI, whilst the receiving account UI has to log the deposit.
As well as logging the withdrawals and deposits, the UI also shows the date of the transfer on the current account UI and receiver's UI.



If the withdrawal or transfer is done 'today', the date of the transfer will be labelled as 'Today' on the UI, if within a week, as 'n days ago'. Otherwise the UI will show date itself.

The dates and currency have been organised according the country and currency of origin, using an Intenationalisation API with a date formatter. This means that if an account is German (de-DE), 
the date will show up in German format and the currency will be in Euros. If it is American, then dollars and mm/dd/year. If UK then GBP and pounds sterling nad dd/mm/year.

There are 4 accounts within the code with set Pin codes and names. I have written a full name in each, and the login username is the initials of each name.
For example Jimmy Poulsen will be jp (to lower case). 
When a login is made, the first name of the account holder will appear in the top left along with a greeting.


usernames and pins for each account
acc1 {username: jp   pin:1111, interestRate: 1.2%}
acc2 {username: bdg  pin:2222, interestRate: 1.5%}
acc3 {username: atu  pin:3333, interestRate: 0.7%}
acc4 {username: sk   pin:4444, interestRate: 1%}

A timer which is preset at 5 minutes begins a count down after a login. This timer refreshes after any of the banking functions are performed (loan, transfer, logging into another account).

The interest rates are preset at different values for each account. The interest rate derives it's value from deposits made into the account.
Every time there is a deposit or withdrawal, it shows up in the UI. This means that current balance, deposits sum, withdrawals sum and interest are updated.

Finally one can choose to close their account by logging the username and pin of the current account into the close account input which is the red box in the app.

Have fun and thank you! 


I have made this project as part of my coursework from Udemy by Jonas Schtedmann.
