# InitLiveCodeTestAngular
## vendingMachine integrated with AngularJS


*Pre interview test*

```
The Soylent Corporation has selected you to implement the software to power their new revolutionary Soylent Green product.  The hardware is complete and the library to interact with the hardware has been provided to you in the attached files. The vending machine must be able to do handle the following requirements
•	The input buttons are labelled A,B,C,1,2,3,4,5 where the letters describe the product location row and the numbers describe the column.  For example a products location will be A1 or C4
•	Every Item on row A costs 50 cents.  Row B costs 75 cents, Row C Costs 1.00 dollar
•	The machine takes only quarters, nickels, and dimes
•	The customer can request to have their money returned any time until the item is vended.
•	If the customer inputs too much money their change must be returned after vending
•	The customer must be shown how much money they have added as a running total 
```
The code can be written inline in the html file or broken into separate js files.  

Library Function Documentation:
Print : prints output to the user interface
getInput: gets the next user input from the queue
vend: tells the machine to vend a specific item (A1, A2, A3…..)
returnCurrency:  tells the machine the amount of money to return;
