
#Dankort Mobile

Dankort Mobile is a white label mobile wallet solution. It allows for branding for a local bank so that the customer loyalty stays local.
Dankort Mobile is mostly based on a bluetooth reader that is needed as an added device to the payment system. However, NFC payments
can also be made via the mobile phone and even QR-code payments are supported even though they seem a bit clunky use-case-wise.

NETS advertises five ways to pay via Dankort mobile using a mobile phone:

1. NFC tap
2. Bluetooth tap
3. Bluetooth tap w/PIN entry
4. Bluetooth Check in/Check out solution
5. QR-code

See video: https://www.youtube.com/watch?v=PN8ARuIjbE8

# PIN entry

Dankort app advertises that you can either feed the PIN-code traditionally or use a finger print to do the same on the mobile phone.

Video: https://www.youtube.com/watch?v=QGRo3I668hU

# Brick & Mortar Use Case 1: Lock Screen Prototype?

Tommy Jessen released a mystical mobile payment prototype video on his channel 28th of December, 2016, where he seems to demonstrate a mobile payment via a mobile phone and an Atos Yomani development terminal. The payment was made so that the mobile phone had its screen lock on. He also claimed that this is a Dankort solution in the video description.

Please view the video yourself: https://www.youtube.com/watch?v=FSLH9PvwnDU

As it stands, this prototype probably used NFC to communicate between the mobile phone and the Yomani terminal. The other likely candidate would be Bluetooth, but does Atos Yomani support Bluetooth? It does have NFC.

There is also no clear way to know whether the application on the mobile phone was somehow pre-started and whether there was some kind of sign-in procedure like a PIN-code or a finger print to active the application into a mode where the payment was in fact possible.

What we can see from the video, for what it's worth, is that the use case seemed to proceed in the following manner:

Clerk:
- input a sales price into the Yomani terminal in standalone mode or via a some kind of POS device to initiante the purchase
- The customer turns on the display on the mobile phone
- The customer presents/taps the mobile phone to the terminal
- The mobile phone presents the purchase price as a notification on the locked mobile phone screen
- The customer clicks the notification on the mobile phone screen
- The mobile phone presents a menu for accepting the payment on the mobile phone screen
- The customer accepts the payment w/a click of a menu item (Godkand)
- The mobile phone displays the payment progress screen
- the mobile phone displays the purchase success screen

It could be that the prototype has been made so that it uses some kind of API for integrated solutions in the app. It could even be a third programme that is used in addition to the regular mobile payment app and the Yomani terminal software. Or the solution could be integrated into the mobile payment application. The video is less than informative on quite a few matters.

There is, indeed, no sure way to even be sure that this is a Dankort mobile solution, but so it is claimed.

# Brick & Mortar Use Case 2: SA/Mobile/NFC

## Device Setup:

Clerk:
  - a standalone payment terminal supporting NFC
Customer:
  - mobile phone w/Dankort mobile app

## Purchase use case

- Clerk inputs a low value sales price (Below 200 DKK, circa $30)
- Customer pays via NFC tap using the mobile phone

This payment methods is similar to normal NFC payment and in all likelihood requires a PIN entry every now and then and is unlikely to be this simple every time.

See video: https://www.youtube.com/watch?v=w5s4_mp5I2k

# Brick & Mortar Use Case 3: SA/Mobile/Bluetooth

## Device Setup:

Clerk:
  - a (standalone) payment terminal
  - bluetooth reader
Customer:
  - mobile phone w/Dankort mobile app

## Purchase use case

- Clerk inputs a low value sales price (Below 200 DKK, circa $30)
- Customer pays via Bluetooth tap using the mobile phone
- All devices signal purchase success:
 - The payment terminal display a purchase success screen
 - The phone displays a purchase success screen

Alternatively:

- Clerk inputs a high value sales price
- Clerk inputs a high value sales price (Above 200 DKK, circa $30)
- Customer starts via Bluetooth tap using the mobile phone
- Dankort Mobile App presents the customer w/a PIN screen
- Customer inputs a four-digit PIN-code
- Customer taps the Bluetooth device again (?)
- All devices signal purchase success

See video: https://www.youtube.com/watch?v=w5s4_mp5I2k

# Brick & Mortar Use Case 4: POS & Terminal/Mobile/Bluetooth

N.B. This use case is based on a different Bluetooth reader than the ones above.

# Device Setup:

Clerk:
  - POS (cash register)
  - a payment terminal
  - bluetooth device
Customer:
  - mobile phone w/Dankort mobile app

## Purchase

### Bird's eye view

- Cash register inputs a sales price
- The payment terminal presents the price to the customer
- The customer presents the mobile phone to the bluetooth device
- The customer accepts the purchase via a click on the mobile phone or via inputing PIN code
- Purchase completes

### Details

The basic arrangement is to have a POS (cash register), a payment terminal and a new bluetooth device to
support the Dankort Mobile. The idea is to integrate this new payment method into existing hardware
and infrastructure.

There are four devices involved in the purchase and it is important to consider how they interact
with one another during the purchase to present a use case to the customer that is easy to use.

In other words, what the payment terminal, bluetooth device and mobile phone are presenting at
different times during the purchase process is important. It is very easy to make such a complicated
setup confusing to the customer.

Dankort mobile solved the problem so that the bluetooth device has just one light/led that signals
the state of processing to the clerk and to the customer. The payment terminal also communicates
the purchase state via its on-screen messages and directs the customer's attention to the right
place.

Overall the purchase transaction seems to proceed thusly, in more detail:

1. The purchase price is input via the POS cash register
2. The payment terminal presents the purchase price and the bluetooth device signals its readiness via the blue light.
3. The mobile phone is presented to the bluetooth device.
4. The bluetooth device signals that it has communicated w/the phone via a beep and also via turning its light yellow.
5. The payment terminal displays screens about the proceeding of the payment to keep the customer informed.
6. The payment terminal displays a screen that prompts the user to continue the purchase via their mobile phone
7. The mobile phone displays a screen containing the purchase price and a green button for accepting the purchase
8. The customer accepts the payment via clicking the green button // is re-tapping the bluetooth device needed?
9. All the three devices signal purchase success:
 - The bluetooth device beeps and turns its led/light green
 - The phone displays a purchase success screen
 - The payment terminal display a purchase success screen

Pinless case can be seen from this video: https://youtu.be/PfwIbYmIhkk?t=52s

The purchase case w/PIN input differs only slightly from the above sequence. Instead of presenting the customer w/a
green button to accept the purchase a PIN input screen is presented. Before and after the PIN input the transaction
proceeds as above. Only pressing the green button on the mobile phone is replaced w/a PIN input screen. The purchase
is accepted via inputing the PIN digits and pressing OK or possibly via finger print. There is no separate acceptance
screen in the use case. The limit for PIN entry is 200 DKK, circa $30.

PIN input use case can be seen from here: https://youtu.be/PfwIbYmIhkk?t=1m11s

# Brick & Mortar Use Case 5: SA/Mobile/Bluetooth: Check-in/Check-out

## Device Setup:

Clerk:
  - a (standalone) payment terminal
  - bluetooth reader
Customer:
  - mobile phone w/Dankort mobile app

## Purchase use case

- Customer checks in via tapping their mobile phone to the bluetooth reader
- Customer packs bags
- Clerk confirms purchase

This use case looks like it could use a bit more details about how the whole thing works.

See video: https://youtu.be/w5s4_mp5I2k?t=1m57s

# Brick & Mortar Use Case 6: SA/Mobile/QR-code

The upside of the QR-code solution is that it does not require an additional Bluetooth device. It is a bit more clunky as a use case, however.

## Device Setup:

Clerk:
  - a (standalone) payment terminal w/QR-code support software
Customer:
  - mobile phone w/Dankort mobile app

## Purchase use case:

- Clerk inputs a sales price
- Customer communicates to the clerk that they want to use the QR-code payment method
- Customer enabled QR-code from the mobile phone app
- The clerk clicks a button on the payment terminal to enable the QR-code payment mode
- The payment terminal displays the QR-code for the payment
- The customer moves the mobile phone camera so that it can read the QR-code from the payment terminal screen
- The payment terminal beeps so signal approval of the QR-code communication
- All devices signal purchase success

PIN entry may be needed in some purchases. This is unclear ATM.

See video: https://www.youtube.com/watch?v=w5s4_mp5I2k&feature=youtu.be&t=2m36s

# Tech

Looks like the an existing Dankort is stored into the mobile phone via a mobile wallet. The service is available through the mobile apps offered by each of the supporting banks and works on Android handsets through host card emulation (HCE) and on iOS through a Bluetooth acceptance device at the point of sale.

Like when using NFC the purchases below 200 DKK ($30) do not require PIN entry. This is what it says on the Dankort app page for Android and there is nothing been said about random selection. Perhaps this really is true and there won't be any PIN queries made below the price of 200 DKK.

You do not need your Dankort credit/debit card to be with you when you pay via the mobile app.

# Security

At least the Android app does not store the card number and when you cancel the card it will also be automatically cancelled from the app, also.

# Pricing

Seems free for at least card holders.

# Requirements

- Dankort
- A supported mobile phone
- Wallet App from one of the Bokis member banks
- A device combination at the sales point that supports Dankort Mobile. See use cases.

“Danish supermarkets are among the first merchants to accept Dankort mobile payments via a Bluetooth acceptance device that sits next to their conventional payment terminals. Following a simple software update to their POS terminals, all merchants that already accept contactless Dankort card payments will also be able to accept Dankort mobile payments.”

# Support

Customers of more than 60 banks belonging to The Bokis Partnership have become the first in Denmark to be offered a mobile payment service for Dankort.

Nets has created a Dankort App for customers of banks that do not have a mobile wallet that works w/Dankort.

# Future

Now support for The Bokis Partnership member banks, planned support for regional banks in Denmark.

Planned coupon support, may be supported by some implementations.

# Parties

Partnership between Nets and Japanese card issuer JCB in April to enable the launch of a mobile payment service for Dankort in Denmark. A partnership with Spire Payments was announced later in the year.

# App

## Downloads

iOS/Apple: https://itunes.apple.com/dk/app/dankort-app/id1213303296?mt=8
Android: https://play.google.com/store/apps/details?id=eu.nets.dankort&hl=da

## Ratings:

Android App (Beta): 1.7/5
iOS/Apple App: 4+

# Refs
https://www.nfcworld.com/2017/03/28/351303/nordic-banks-roll-out-first-mobile-payment-services-with-support-for-dankort/
https://www.nets.eu/Media-and-press/news/Pages/Dankort-goes-mobile.aspx
https://en.wikipedia.org/wiki/Host_card_emulation
https://itunes.apple.com/dk/app/dankort-app/id1213303296?mt=8
https://play.google.com/store/apps/details?id=eu.nets.dankort&hl=da
https://www.youtube.com/watch?v=PN8ARuIjbE8
https://www.youtube.com/watch?v=w5s4_mp5I2k
https://www.youtube.com/watch?v=QGRo3I668hU


