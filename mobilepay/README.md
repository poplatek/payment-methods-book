# MobilePay

MobilePay is an application for iOS, Android and Windows phones that allows for payments using a mobile phone number instead of a bank account number or a credit card at hand.
A credit card and a bank account number is needed during registration and bound to the mobile phone number during the registration process.
During paying the credit card, which is not physically part of the payment process, is charged and the targeted bank account acts as the receiver of the payment.

It is used mainly in Denmark but also to a lesser extent in Finland and Norway.

MobilePay is free for use by private individuals.

# Features

MobilePay has:
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
- can be used to pay inside of other apps, see video: http://publisher.qbrick.com/Embed.aspx?mcid=E2B7A340A6500CCE
- locked screen purchases

MobilePay offers:
- a solution for paying invoices via MobilePay Invoice
- digital receipts, see video: publisher.qbrick.com/Embed.aspx?mcid=6D7FD2A7A6500CCE
- a bonus system for small companies
- loyalty programs for large chains
- WeShare solution

MobilePay Weaknesses:
- delay in money transfer
- credit card to bank account only transfer of funds

MobilePay has a delay in money transfers. If the target account is in Danske Bank, the money transfer is instantanous. If not, in the evenings and over weekend it takes at least one day for the money to be transferred to the target account. Also, MobilePay is not a bank account to bank account transfer system and transfers money from a credit card to a bank account, instead.

MobilePay Strengths:
- can register and use any Debit or Credit from a Finnish bank in Finland (probably similarly elsewhere) as long as the card is enabled to do Internet purchases
- can register and use any Finnish bank account (probably similarly elsewhere)

# Use Cases

# Registration process

Registration process differs for app users and business users who are setting up a shoppe.

TODO

# Beginning of transaction

Beginnings of purchases are often omitted in advert material. In the case of Danske MobilePay you need to do the following steps to ready the phone for payments:
1. Unlock the phone screen if it is locked or activate the screen otherwise, e.g. w/a button press
2. Start the MobilePay app if it is not already running
3. Input the MobilePay personal PIN code

# General

The way the MobilePay app has been implemented it requires the app user to take out their phone for payment and then start the app and then enter the PIN code for the application before it can be used.

## Brick & Mortar Use Case: MyShop - 2 mobile phones

### Device Setup:

Clerk:
  - MobilePay MyShop App
  - MobilePay App compatible mobile phone

Customer:
  - mobile phone w/MobilePay mobile app

### Purchase

- Clerk inputs sales price into their mobile phone MobilePay MyShop App
- Customer starts their phone app and signs in via a PIN code
- Customer presents their phone to clerk's phone (Bluetooth communications or QR-code)
- Customer swipes to accept the payment

See video: http://publisher.qbrick.com/Embed.aspx?mcid=357FCD1A059B2C01

## Brick & Mortar Use Case: ...

### Device Setup:

Clerk:
  - POS Cash Register
  - MobilePay wireless device

Customer:
  - mobile phone w/MobilePay mobile app

### Purchase

- Clerk inputs sales price into POS cash register
- Customer presents their mobile phone to the MobilePay wireless device
- Purchase amount is presented to the customer on the Mobile phone screen
- Customer chooses the payment card they want to use from a drop down menu on the Mobile phone screen (this step is probably optional)
- Customer swipes to accept the payment
- Customer receives the purchase receipt to the Mobile phone screen

See video: https://www.youtube.com/watch?v=PN8ARuIjbE8

# Locked screen purchases

MobilePay has launched a new payment type that allows for paying from locked screens of mobile phones in April 2017. The maximum purchase price for this type of payment is 250 DKK. For amounts above 250 DKK the customer must log onto the MobilePay app where the amount is automatically shown and can be accepted with a swipe.

Danske Bank says that this new payment method works with almost all mobile phone types.


See press release: https://www.mobilepay.dk/da-dk/PDF/Pressemeddelelser/pm-eng-dagrofa-verifone-mobilepay-20170410.pdf

# Mobile OS Support

MobilePay is supported on Android, iOS and Windows phones.

# Pricing

The MobilePay app is free to use at least for now to end-user customers, that is, to the person who installs the MobilePay app to their phone as a private individual. Payments vary for business customers depending on the chosen setup and current discounts.

# QR-codes

The app user can create their own QR-code via a generator here: https://stadel.dk/MobilePay_QR_kode_generator - however, apparently MobilePay Business version seems to be required.

# Goals

The stated goal of MobilePay is to provide a leading solution for the Nordic markets and to find a way to collaborate with the Swedish Swish. A long term goal of being able to make payments between Swish and MobilePay has been stated.

# Collaboration

Customers of all Finnish banks can use the application. DB has invited all Fennoscandian banks to join in collaboration with MobilePay. Originally MobilePay was created as a solution for DB that decided against national cooperation with Danish banks to build a common app for Denmark. The reasons sited for this decision included the fact that DB did not want to develop a Denmark-only solution.

Finnish Nordea Bank is in collaboration with MobilePay in Denmark and Norway.

DB has stated that it is following the Finnish solution, Siirto, but has not joined it. DB said that MobilePay basically has almost all of the features already that the Finnish Siirto would be offering.

# Size

In Denmark has more than 3.6 million downloads in the Nordics and more than 27 000 companies are using MobilePay out of which 4 800 are web shops.


In Denmark MobilePay where 90% of the smartphones have the app. Danes value the app as the 2nd most important next only to Facebook.

In Finland the app has been downloaded 450 000 times.

More then 205 million MobilePay transactions are processed yearly. 25% of these transactions are made in shops.

# Ownership

MobilePay was developed and owned by the Danish Danske Bank. It is currently being (2017) made into a subsidiary of DB.

# SDK

* https://github.com/MobilePayDev
* https://www.mobilepay.dk/da-dk/Developer/Pages/developer.aspx

# Language

REST API

# Ref

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


