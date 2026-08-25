# Database Modelling for App

## Database 1

<img width="4080" height="3060" alt="20260825_182522" src="https://github.com/user-attachments/assets/8c92fce9-d3d7-43d2-b352-3695f8219926" />

## Database 2
<img width="4080" height="3060" alt="App1" src="https://github.com/user-attachments/assets/5898aa3a-061a-41b2-ae8f-dfc055908e4b" />

## From Database 1
The amount to be budgeted is stored in the (amount_budg) variable. This is taken from page 2 of the app

## From Database 2
Items to be bought within the budget are stored in the (Items_budg)variable. The respective price of each item is stored in the (Money_budg) variable. The (amount_budg) input received in page 2 is displayed as the current
budget.

## Logical Flow

### buget input received -> stored as a value(float) into (amount_budg) 
#### items added into expenses ( items stored as text and the price stored as numbers) in (Items_budg) and (Money_budg) respectively
##### since it is a list, items can be added and removed
##### Page 3 then displays the current budget which is sum(price_budg)- (amount_budg)

