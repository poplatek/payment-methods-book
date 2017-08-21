# MobilePay

## Exec Summary ??? <= why, merge the text into the document?

MobilePay is very strong in many ways.

MobilePay's use cases seems reasonably good even for brick-and-mortar payments. They used to require an extra Bluetooth/QR-Code device but this is no longer the case because e.g. Verifone and Ingenico are offering classic payment terminals that support these communications technologies.

On top of that, MobilePay uses only one app and is even sporting a locked screen purchase that allows the customer to purchase using mobile phone nofitications. And MobilePay is trying to get black screen and open screen purchases to work as well.

The use cases seem generally quite well designed for MobilePay, and MobilePay has a lot of features. 

MobilePay is also aiming at being able to interoperate w/the Swedish Swish. MobilePay is already available in Denmark, Norway and Finland and may well emerge as the winner from the mobile payment market in the Nordics. It already has a very significant user base.

MobilePay has a few weaknesses as well, most notably a delay in money transfer to a bank other than Danske Bank and the fact that it requires its users to own a credit/debit card in addition to the smartphone and a bank account.

## About

MobilePay is an application for iOS, Android and Windows phones that allows for payments using a mobile phone number instead of a bank account number or a credit card at hand.
A credit card and a bank account number is needed during registration and bound to the mobile phone number during the registration process.
During paying the credit card, which is not physically part of the payment process, is charged and the targeted bank account acts as the receiver of the payment.

It is used mainly in Denmark but also to a lesser extent in Finland and Norway.

MobilePay is free for use by private individuals.

# TOC

<!-- toc -->

# Features

## List of Features

- person to person payments
- solutions for small to medium size companies
- solutions for big companies
- a solution for a web store
- a solution for mobile payment
- a new terminal for cards and mobile devices which supports Bluetooth and QR-codes
- a solution for fundraising
- a way to mimic payment terminal payments via two mobile phones
- capture API allows for reservation payments
- refund amount API allows for refunds
- locked screen purchases
- mobile to mobile payments, e.g. in a restaurant table
- can be used to pay inside of other apps, see video: http://publisher.qbrick.com/Embed.aspx?mcid=E2B7A340A6500CCE
- digital receipts, see video: publisher.qbrick.com/Embed.aspx?mcid=6D7FD2A7A6500CCE
- a solution for many Nordic banks, cards and bank accounts
- a solution for paying invoices via MobilePay Invoice
- a bonus system for small companies
- loyalty programs for large chains
- WeShare solution

## Strengths

- has Locked Screen purchase support
- can register and use any Finnish bank account (probably similarly elsewhere)
- open to non-Danske users, 70% of users are not from Danske Bank

## Weaknesses
- delay in money transfer
- credit card to bank account only transfer of funds
  - can one use a debit card, then money would come from bank account?

MobilePay has a delay in money transfers. If the target account is in Danske Bank, the money transfer is instantanous. If not, in the evenings and over weekend it takes at least one day for the money to be transferred to the target account. Also, MobilePay is not a bank account to bank account transfer system and transfers money from a credit card to a bank account, instead.

## Requirements

TODO

# Use Cases

## General

The way the MobilePay app has been implemented it requires the app user to take out their phone for payment and then start the app and then enter the PIN code for the application before it can be used.

### Beginning of transaction

Beginnings of purchases are often omitted in advert material. In the case of Danske MobilePay you need to do the following steps to ready the phone for payments:

1. Unlock the phone screen if it is locked or activate the screen otherwise, e.g. w/a button press
2. Start the MobilePay app if it is not already running
3. Input the MobilePay personal PIN code

However, MobilePay now also supports payments from locked screen, see below.

## Registration Process

Registration process differs for app users and business users who are setting up a shoppe.

## Use Case: Mobile to mobile basic payment
### Preconditions

1. Payer opens the mobile phone black screen
2. Payer opens the MobilePay app
3. Payer clicks to start a payment

### Use Case Steps

4. Payer feeds in 4-digit PIN code
5. Payer feeds in payment amount and clicks OK
6. Payer feeds in payees mobile phone number or name from the address book + OK
7. Payer swipes to accept the payment
8. Mobile phone displays the success/receipt screen

See video: http://publisher.qbrick.com/Embed.aspx?mcid=ACD4EDCCa6500CCE

## Use Case: Brick & Mortar Use Case #1: SA terminal/mobile phone - in-app purchase case

### Device Setup

- Clerk: payment terminal that supports MobilePay (e.g. Verifone), this means Bluetooth & QR-code support
- Customer: phone supporting MobilePay

Specific setup:
- Verifone SA payment terminal w/a receipt printer and bluetooth support
- A mobile phone

### Preconditions

...

### Use Case Steps

1. The Clerk inputs clicks the green button on the SA payment terminal to initiate the sales price input
2. The Clerk the sales price into the payment terminal
3. The Clerk pushes the green button to declare that the sales price has been put in
4. The payment terminal displays the insert card screen
5. The Customer removes black screen via a button press
6. The Customer opens the MobilePay app
7. The Customer inserts their MobilePay PIN-code to sign in
8. The Customer taps the mobile phone to the payment terminal
9. The Payment terminal displays the progress screen
10. The mobile phone displays the sales price on the mobile phone screen and activates the swipe
11. The customer swipes the swipe button/bar on the mobile phone to accept the payment
12. The mobile phone displays the progress screen
13. The payment terminal displays the purchase success screen
14. The mobile phone displays the purchase success screen
15. The payment terminal prints the receipt

See sample video: https://player.vimeo.com/video/203367072 - it shows some of the steps mentioned above but not all, as it is an advert.

## Use Case: Brick & Mortar #2: SA terminal/mobile phone - Locked screen payment

### Device Setup

- Clerk: payment terminal that supports MobilePay (e.g. Verifone), this means Bluetooth & QR-code support
- Customer: phone supporting MobilePay

### Preconditions

...

### Use Case Steps

...TODO...

## Use Case: Brick & Mortar #3: MyShop - 2 mobile phones

### Device Setup

Clerk:
  - MobilePay MyShop App
  - MobilePay App compatible mobile phone

Customer:
  - mobile phone w/MobilePay mobile app

### Preconditions

...

### Use Case Steps

- Clerk inputs sales price into their mobile phone MobilePay MyShop App
- Customer starts their phone app and signs in via a PIN code
- Customer presents their phone to clerk's phone (Bluetooth communications or QR-code)
- Customer swipes to accept the payment

See video: http://publisher.qbrick.com/Embed.aspx?mcid=357FCD1A059B2C01

## Use Case: Brick & Mortar #N ...

### Device Setup

Clerk:
  - POS Cash Register
  - MobilePay wireless device

Customer:
  - mobile phone w/MobilePay mobile app

### Preconditions

...

### Use Case Steps

- Clerk inputs sales price into POS cash register
- Customer presents their mobile phone to the MobilePay wireless device
- Purchase amount is presented to the customer on the Mobile phone screen
- Customer chooses the payment card they want to use from a drop down menu on the Mobile phone screen (this step is probably optional)
- Customer swipes to accept the payment
- Customer receives the purchase receipt to the Mobile phone screen

See video: https://www.youtube.com/watch?v=PN8ARuIjbE8

# Tech

## Locked screen purchases

MobilePay has launched a new payment type that allows for paying from locked screens of mobile phones in April 2017.

The other party in the payment is a classic card payment terminal. At least Verifone terminals are supported and probably also at least Ingenico terminals. Danke states that their goal was to provide a solution that requires only the mobile phone and a classic payment terminal because this is what their business customers were asking for.

The other goal was to provide a payment method that does not require the customer to sign into the MobilePay app.

Danske Bank says that this new payment method works with almost all mobile phone types and that 90% of all Danish smartphones are supported.

Black screen and open screen purchases are not yet supported. Only locked screen is. However, Danske is saying that they are developing solutions for these.

The maximum purchase price for this type of payment is 250 DKK and purchases up to this limit can be done 5 times before the next purchase will be asked to be done from the actual Mobile App. For amounts above 250 DKK the customer must log onto the MobilePay app where the amount is automatically shown and can be accepted with a swipe.

The support for locked screen purchase is scheduled to take place in Finland after the summer of 2017. The limit for this purchase type amountwise will be 25 EUR in Finland.

Terminal support:
- https://go.bambora.com/dk/mobilepay
- https://www.goappified.dk/terminal
- http://www.verifone.dk/da/Denmark/Start/Tjenester/MobilePay/
  - Video: https://player.vimeo.com/video/203367072

Refs:
https://www.mobilepay.dk/da-dk/Erhverv/Pages/mobilepay-terminaler.aspx
https://www.mobilepay.dk/da-dk/PDF/Pressemeddelelser/pm-eng-dagrofa-verifone-mobilepay-20170410.pdf
https://www.danskebank.fi/fi-fi/tietoa-danske-bankista/media/Tiedotteet/Pages/Bambora%20ja%20MobilePay.aspx

## QR-code support

The app user can create their own QR-code via a generator here: https://stadel.dk/MobilePay_QR_kode_generator - however, apparently MobilePay Business version seems to be required.

## App

### Downloads

Android: https://play.google.com/store/apps/details?id=dk.danskebank.mobilepay&hl=en
iOS: 

### Ratings

Android: 4.3
iOS: 4+

### OS Support

MobilePay is supported on Android, iOS and Windows phones.

### SDK

* https://github.com/MobilePayDev
* https://www.mobilepay.dk/da-dk/Developer/Pages/developer.aspx

### Language

REST API

## eCommerce

...

## Brick and Mortar

...

## Security

...

# Business

## Pricing

The MobilePay app is free to use at least for now to end-user customers, that is, to the person who installs the MobilePay app to their phone as a private individual. Payments vary for business customers depending on the chosen setup and current discounts.

## Size

In Denmark has more than 3.6 million downloads in the Nordics and more than 27 000 companies are using MobilePay out of which 4 800 are web shops.

In Denmark MobilePay where 90% of the smartphones have the app. Danes value the app as the 2nd most important next only to Facebook.

In Finland the app has been downloaded 500 000 times. The user base has doubled in one year.

More then 205 million MobilePay transactions are processed yearly. 25% of these transactions are made in shops.

## Future Goals & Plans

The stated goal of MobilePay is to provide a leading solution for the Nordic markets and to find a way to collaborate with the Swedish Swish. A long term goal of being able to make payments between Swish and MobilePay has been stated.

## Collaboration

Customers of all Finnish banks can use the application. DB has invited all Fennoscandian banks to join in collaboration with MobilePay. Originally MobilePay was created as a solution for DB that decided against national cooperation with Danish banks to build a common app for Denmark. The reasons sited for this decision included the fact that DB did not want to develop a Denmark-only solution.

Finnish Nordea Bank is in collaboration with MobilePay in Denmark and Norway.

DB has stated that it is following the Finnish solution, Siirto, but has not joined it. DB said that MobilePay basically has almost all of the features already that the Finnish Siirto would be offering.

## Ownership

MobilePay was developed and owned by the Danish Danske Bank. It is currently being (2017) made into a subsidiary of DB.

# References

https://mobilepay.fi/fi-fi/Pages/faq.aspx
http://www.mobilepay.fi/fi-fi/Pages/mobilepay.aspx
https://en.wikipedia.org/wiki/MobilePay
https://fi.wikipedia.org/wiki/MobilePay
https://www.mobilepay.dk/da-dk/pages/the-story-in-english.aspx
https://www.danskebank.fi/fi-fi/tietoa-danske-bankista/media/Tiedotteet/Pages/Danske-Bank-kutsuu-kaikki-pohjoismaiset-pankit-mukaan-MobilePay-yhteistyohon-.aspx
http://www.hs.fi/paivanlehti/07032017/art-2000005116588.html

- mobilepayssa lienee e-kuitti
- MobilePay MyShop
 - https://www.mobilepay.fi/fi-fi/Yritykset/Pages/mobilepay-myshop.aspx
 - https://www.mobilepay.fi/fi-fi/Yritykset/Pages/mobilepay-point-of-sale.aspx <- maksutapakuvaus

			Nopea tapa maksaa ostokset kassalla

			Yhdistä tunnistin kassajärjestelmääsi ja uusi maksutapa on käytössä:

					Asiakkaasi avaa MobilePay-sovelluksen älypuhelimessaan ja kirjautuu henkilökohtaisella tunnuksellaan. 
					Asiakas skannaa kassajärjestelmässäsi olevan QR-koodin tai laittaa puhelimensa MobilePay-tunnistimen lähelle.. 
					Asiakas hyväksyy maksun pyyhkäisemällä puhelimen kuvaruudulle näkyviin tulevasta nuolesta.

 - https://www.mobilepay.fi/fi-fi/Yritykset/Pages/mobilepay-appswitch.aspx
 - https://www.mobilepay.fi/fi-fi/Yritykset/Pages/mobilepay-online.aspx
 - https://www.mobilepay.fi/fi-fi/Yritykset/Pages/mobilepay-myshop.aspx

https://stadel.dk/MobilePay_QR_kode_generator
https://www.mobilepay.dk/da-dk/PDF/Pressemeddelelser/pm-eng-dagrofa-verifone-mobilepay-20170410.pdf

https://www.youtube.com/watch?v=eeSyS9gmbYE
https://www.youtube.com/watch?v=JENIMfJIzRo
https://www.youtube.com/watch?v=VSQx5yTfYcg

instore: http://publisher.qbrick.com/Embed.aspx?mcid=6D7FD2A7A6500CCE
inapp: http://publisher.qbrick.com/Embed.aspx?mcid=E2B7A340A6500CCE
pay in 4: http://publisher.qbrick.com/Embed.aspx?mcid=ACD4EDCCa6500CCE

