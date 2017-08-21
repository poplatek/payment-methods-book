# Swish

## About

Swish is effectively a Sweden and SEK only solution for mobile payment. It is the major player in Sweden. It has both strengths and weaknesses due to how it has been implemented. Balancing the issue of being Sweden & SEK only, the payments are always instant and you can see the payees name on the mobile phone screen when you're paying.
]

# TOC

<!-- toc -->

# Features

## List

- pay to friends, companies, organisations
- give to charity
- split bills
- ecommerce
- can be embedded to other apps
- QR-code initiated purchases
- instant payments to any of the participating banks
- supports 50 character payment messages

## Strengths

- Instant payments across the board
- Can see the payees name while paying

## Weaknesses

- Sweden only
- SEK only
- Two obligatory apps, Swish and BankId

Due to depending on the Swedish BankID Swish is effectively Swedish only albeit this is precisely why it supports instant payments across all participating banks and showing payee names during payment.

## Requirements

To use the service, one needs
- Swedish mobile Bank ID
- a Swedish bank account
- a smartphone
- a smartphone number
- the Swish app
- Swedish Bank ID app

# Use cases

## General

...

## Registration Process

...

## Use Case: Mobile payment using a QR-code

### Device Setup
### Preconditions

The Merchant/Clerk-side must already know the transaction amount. This means that if we are for example
in a traditional shoppe environment that all the bar codes from the customer's total purchase must be
scanned.

### Use Case Steps

This use case step list is based on Swich QR code integration documentation, the so called "Happy Case".

1. Clerk's backend calls Swish QR code generator API to request a QR-code for a purchase amount
2. Clerk's backend receives the QR-code
3. QR-code is displayed to the Customer.
4. The Customer disables the black screen
5. The Customer starts up the Swish app
6. The Customer scans the QR code
7. The Customer presses the “Pay” button.
8. A signing session is initiated with Mobile BankId.
9. Swish answers the Swish app.
10. The Swish app switches to the BankId app.
11. The Customer signs in BankId app.
12. The BankId app switches back to the Swish app.
13. The Swish app contacts Swish to execute the payment.
14. Swish checks the outcome of the signing with BankID. The money is then transferred, in real
time, from the consumer’s account to the company’s account.
15. The consumer see that the payment was performed successfully in the Swish app.

The consumer can view the payment in the events section “Händelser” as a sent payment in the Swish
app.

Ref:
https://www.getswish.se/content/uploads/2015/11/Guide-Swish-QR-code-design-specification_v1.5.pdf

## Use Case: Mobile to Mobile use case with verification of payment

### Device Setup

- The Payer's mobile phone w/Swish App and Bank ID App
- The Payee's mobile phone w/Swish App and Bank ID App

### Preconditions

The Payer has the Swish App already open, which means that they have clicked the phone open from the black screen and then clicked to start the Swish app.

### Use Case Steps

1. The Payer feeds the Payee's phone number into swish because it's not yet bookmarked
2. The Payer feeds in the payment amount
3. The Payer clicks OK to accept the payment amount
4. The Payer types in the optional 50 char message
5. The Payer clicks button to pay
6. Bank ID app pops up
7. The Payer visually verifies payment content from the window that appers
8. The Payer clicks a button to accept that the payment details are correct
9. A PIN screen appears
10. The Payer feeds in the 6 digit PIN code
11. The Payer pushes OK to accept
12. A processing screen appears for the Payer in the Bank ID app
13. A processing screen appears for the Payer in the Swish app
14. A success screen appears to the the Payer in Swish
15. A mobile notification appears to the Payee on the top of the mobile phone screen that informs about the payment
16. The Payee clicks the notification
17. The Payee clicks to remove a warning popup from the swish app that appers once it starts
18. The Payee clicks a button to access the list of payments
19. A processing screen appears
20. Bank ID app pops up for the Payee
21. A PIN code entry screen pop ups for the the Payee
22. The Payee feeds in the 6 digit PIN
23. The Payee clicks OK to accept the fed in PIN
24. A processing screen appears in the Bank ID app
25. Another processing screen appears, now on Swish app
26. A list of payments appears and the the Payee can visually confirm the payment
27. The Payer clicks OK on the money transfer success screen
28. A processing screen appears
29. The Payer visually confirms from a list that the payment has indeed been made

See the video: https://www.youtube.com/watch?v=px5XVOgW-tc

# Tech

## Locked screen purchases

...

## QR-code support

QR-code payload:
1. The receiving mobile or Swish-number (required)
2. The amount of the payment (optional)
3. Payment information such as reference number or order ID. (optional)

Refs:
[Swish QR-Code integration guide](https://www.getswish.se/content/uploads/2015/11/Guide-Swish-QR-code-design-specification_v1.5.pdf)
https://www.getswish.se/content/uploads/2017/06/QR_FAQ.pdf

## App

### Downloads

Android: https://play.google.com/store/apps/details?id=se.bankgirot.swish&hl=en
iOS: https://itunes.apple.com/fi/app/swish-payments/id563204724?mt=8

### Ratings
Android: 4.1/5
iOS: 4+

### OS Support

...

### SDK

...

### Language

...

## eCommerce

...

## Brick and Mortar

...

## Security

...



# Business

## Pricing

## Size

## Future Goals & Plans

## Collaboration

The banks that are supported by Swish in Sweden are:
- Danske Bank
- Handelsbanken
- ICA Banken
- Länsförsäkringar
- Nordea
- SEB
- Skandia
- Sparbanken Syd
- Swedbank
- Sparbankerna
- Ålandsbanken

## Ownership

...

## Background/History

...

# Refs

https://www.getswish.se/
https://en.wikipedia.org/wiki/Swish_(payment)
https://www.youtube.com/user/getswish
https://medium.com/@etiennebr/swish-the-secret-swedish-fintech-payment-company-created-by-nordic-banks-and-used-by-50-of-swedes-cfcf06f59d6f
https://www.bankid.com/en/
https://www.youtube.com/watch?v=s03Kt9uZ4l4
https://www.youtube.com/watch?v=px5XVOgW-tc
https://www.getswish.se/content/uploads/2015/11/Guide-Swish-QR-code-design-specification_v1.5.pdf
