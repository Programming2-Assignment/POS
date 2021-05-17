# Programming 2 Assignment
## POS System in Java
## Group Members
> Obiora Kenneth Omalu - 220074895
> Sharmillah Viringa - 220070040 

## Justification Of Design Pattern
### The following Objects will be created as stated below with their respective attributes:
## Dealer
> Name
> Surname
> password
> username 


- The Dealer is regarded as the administrator or the owner of the shop .
- He/she will have basic attributes to gain access to complete functions relevant to the business.
- The login page will take into account the Dealers credentials and take him to the admin panel

## Customer class
> Name
>Surname
>username
>password
> bankAccount

- The Customer will have extend the bankAccount class which will have the relevant details concerning the payment.
- The customer will be able to purchase items and receive a reciept as well as a bank statement.
- The password and username is used to make sure that other customers do not gain access to other customers accounts.

## BankAccount Class
> cardNumber
>pin
> balance

- A bankAccount is assigned to each customer.
- the pin is defined by the customer and allows the payment to be completed if the password is correct and if the balance is enough to facilitate the transaction



## Cart Class
> item

- The cart class contains an list of items selected by the customer.

## Item
> name
> price
> stockLevel

- The item class has basic information on the products.
- The stockLevel attribute is used to calculate the stock level after the dealer restocks or the customer purchases the item.
