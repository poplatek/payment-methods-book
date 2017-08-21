# Brick and mortar mobile payment methods comparison

## About

This page is for discussion and comparison of different ways of addressing mobile paying in brick and mortar situations. The specific use cases can be found from the respective pages of this book that explain the technology for MobilePay, Vipps, Swish, Dankort mobile and so on.

## Exec Summary

Missing: Vipps, Dankort

### MobilePay

MobilePay is very strong in many ways. The use cases seem generally quite well designed for MobilePay and MobilePay has a lot of features. 

MobilePay's use cases seems reasonably good even for brick-and-mortar payments. They used to require an extra Bluetooth/QR-Code device but this is no longer the case because e.g. Verifone and Ingenico are offering classic payment terminals that support these communications technologies.

On top of that, MobilePay uses only one app and is even sporting a locked screen purchase that allows the customer to purchase using mobile phone notifications. MobilePay is also trying to get black screen and open screen purchases to work, as well.

MobilePay has a few weaknesses, most notably a delay in money transfer to a bank other than Danske Bank and it requires its users to own a credit/debit card in addition to the smartphone and a bank account.

### Swish

Swedish Swish uses a Swedish BankId application as an extra mobile app. This approach has strengths buts also significant weaknesses: Swish is SEK and Sweden only.

As it uses two apps, its use cases are more cumbersome than they need to be. On the plus side, due to BankId, Swish is able to transfer the payments instantly to all participating banks as well as being able to show the payee's name before the payment is being made.

### Predictions

MobilePay is aiming at being able to interoperate w/the Swedish Swish in order to be able to transfer payments between Swedish Swish users and Mobilepay users. MobilePay is already available in Denmark, Norway and Finland and may well emerge as the winner from the mobile payment market in the Nordics. It already has a very significant user base.

Swish has a large market share in Sweden and seems solely geared to the Swedish markets. As it is so strong locally and offers instant payments in that area, MobilePay is now trying to get into collaboration with Swish rather than attempting to take over its market.

It is likely that Swish will win the Swedish mobile payments market. If it ends up in collaboration with MobilePay its users will be able to transfer money to most Nordic destinations via the MobilePay infrastructure. Together, they could become the actor in the mobile payments markets in the Nordics.

## Feasibility of the new mobile payment methods for brick-and-mortar situations

The new mobile payment methods vary but the most commonly used ways of communicating between devices seems to be:

1. Bluetooth
2. NFC
3. QR-code
4. Internet

The solutions that support NFC allow for the user to present/tap their phone to a NFC device to make a payment. Bluetooth works similarly. The QR-code solutions depend on the mobile phone camera which is used to take a photo of the QR-code that includes the payment information including but not necessarily limited to the sales price. There are also mobile to mobile solutions that depend on both mobile phones having Internet connections.

The strenghts of these technologies is that they do support the payment via a mobile phone. However, there is a hassle in many of the payment methods that is not non-significant. Especially some QR-code solutions look cumbersome and this is true to an extent to almost all payment methods that depend on the mobile phones because of the need to:

1. Activate the mobile phone screen (from black screen)
2. Unlock the screen, possibly via using a PIN-code, biometry or a swipe
3. Start the application if it is not already running 
4. Sign into the payment application via a PIN-code or perhaps a finger print.

There seems to be methods of mitigating these problems and steps are being taken into making the purchase process less difficult on mobile devices. The newest solutions to this end seem to depend on starting the purchase from the locked mobile phone screen. There is a prototype video about this sort of payment method in the Internet (which may or may not be Dankort Mobil) and also at least MobilePay has come out w/a variant that actually brings this type of payment method to the market.

Please view the video for yourself about the locked screen payment method variant prototype: https://www.youtube.com/watch?v=FSLH9PvwnDU

There are also advances being made in order to allow starting a payment from the mobile phone black screen and open screen. The black screen means the black screen that is displayed when the phone is not in use and the open screen refers to the screen lock having been opened already but the application not yet being started. At least MobilePay is making efforts to get one or both of these payment methods to work.

In addition, the mobile phone payment methods are getting more and more supported by the other hardware. Where it was once necessary e.g. for a MobilePay solution to have an extra Bluetooth/QR-code reader, these features are now beginning to be supported by payment terminals that look classic and ordinary. This removes the hassle of the new mobile phone payment methods that is related to the need of developing, fielding and supporting extra devices and teaching staff and customers to use them.

Overall, even if there is significant advancement in the mobile phone payment method market, there is still some progress to be made. That said, the newest setups w/locked screen payment variants used together w/the old school payment terminals that support mobile payment methods seem now to be ready for wide-scale use. They are getting over the threshold of being too cumbersome to use for comfort and then all that is left is the convenience of not needing to have your credit/debit card w/you when you leave the house. The electronic receipt is likely to become widely supported, as well.

The user bases are exploding, too, due to the honey that was given to the end-users: the apps are mostly free-of-cost to the end users and they allow for money transfers between friends as well as loaning to and from friends as well as the convenience of being able to split bills easily. These new features along with the mostly supported instant payments on the mobile devices can clearly be attractive to the end-users.

Vipps has even developed a scheme for paying to non-users of their app. If you pay to a non-user they will be sent a text message (SMS) about the payment and told in that message that they need to install the Vipps app to be able to receive the payment. This is a very sneaky way of basically paying the new customer to install the Vipps app to their mobile phone while in reality paying nothing.

## About the approaches

There are many ways to go about the brick and mortar mobile payment situation. Some solution start from the perspective of trying to integrate the new mobile payment solution to the already existing setups at the merchant's shoppe. Some solutions try to completely avoid this in an attempt to bypass all the older systems and then trying to expand towards the existing solutions, as necessary, from the exact opposite starting point.

There are certainly strenghts and weaknessess to both of these ways of approaching the brick and mortar payment situation. It seems however that the different ways to go about it end up converging to somewhat similar end results.

### Dankort Mobile

The Dankort mobile solution is a white label wallet solution for mobile payments. White labeling is supported in order to be able to have the local banks use their logos in the apps to ensure customer loyalty. Overall the Dankort Mobile seems to be based on extending the existing solutions the customers already have at their sales locations.

Dankort mobile appears to support several payment methods but seems to be, above all, an old school way of going about it. The credit card is put electronically into the mobile phone, so to speak, and a regular NFC payment can be made in the same way as you would w/a credit card.

Dankort mobile goes much further than this, however. There is an additional Bluetooth device that can be added to the existing POS setup which allows for paying via the mobile Dankort app through presenting/tapping the phone to this new device.

There is a new check in/check out solution that lets the customer in some way to first tap their dankort phone to a receiver which start the transaction processing and the transaction is processed at the same the customer is packing their things and completes apparently when the cashier has finished handling the products for this customer. This is basically a solution for making the bag packing and the payment work in parallel.

QR-code is also supported even though it does look somewhat clumsy as a use case and then there may be a prototype of starting a purchase from a locked screen situation via the mobile phone which may or may not be a future Dankort mobile product.

The specifics about the use cases seem to depend on the setup. It is a bit different if you have a mobile phone and standalone terminal than it is if you have an integrated payment terminal w/a POS and a bluetooth reader device in addition to the mobile phone.

Also, it may be that the iOS/Apple phone solution differs from the Android solution which is based on the Android HCE technology. The iOS solution may be Bluetooth-based and it is not certain what features it supports and what features it perhaps does not. It could be, for example, that there is no support for NFC purchases on iOS.

View the specifics about the use cases from here: [Dankort Mobil](../dankort/dankortmobil/README.md)

## Danske Mobilepay

MobilePay is very strong in many ways.

MobilePay's use cases seems reasonably good even for brick-and-mortar payments and MobilePay is beginning to be quite well supported. It also has a lot of features.

MobilePay used to require an extra Bluetooth/QR-Code device but this is no longer the case because e.g. Verifone and Ingenico are offering classic payment terminals that support these communications technologies. These payment terminals are probably available for both standalone and POS integrated setups.

On top of that, MobilePay uses only one app and is even sporting a locked screen purchase that allows the customer to purchase using mobile phone nofitications. The low value purchases can be paid this way without the need to open the app and feed pin codes. MobilePay is trying to get the black screen and open screen purchases to work as well.

There is also a mobile to mobile setup where the clerk can use a mobile phone to receive the payment either over the Internet or via a bluetooth tap and probably also via a QR-code.

MobilePay can be used w/non-Danske Bank credit/debit cards and 70% of the MobilePay users are using some other bank than Danske. This is an asset to MobilePay even if it comes with the weakness that only Danske Bank users will be able to send and receive payments instantly.

MobilePay is aiming at being able to interoperate w/the Swedish Swish in order to be able to transfer payments between Swedish Swish users and Mobilepay users. MobilePay is already available in Denmark, Norway and Finland and may well emerge as the winner from the mobile payment market in the Nordics. It already has a very significant user base.

MobilePay has a few weaknesses as well, most notably a delay in money transfer to a bank other than Danske Bank and the fact that it requires its users to own a credit/debit card in addition to the smartphone and a bank account.

View the specifics about the use cases from here: [Danske MobilePay](../mobilepay/README.md)

## Swedish Swish

Swish is the major mobile payment solution in Sweden. The way it depends on the Bank ID and the Swedish bank systems makes it SEK only and in effect, Sweden only. This also leads to the situation where a Swish user also needs to use another Bank Id app.

On the plus side, this leads to the strength of being able to make instant payments to all the participating banks and being able to show the payee's name during payments 
but being dependent on the Bank ID application is a clear minus on the level of usability. During registration you need to be eligible for both of these apps. Then, when in use, most of the things are done in the Swish app that then launches the Bank ID to do its part. After Bank ID processing has been done, the Swish app reappers again to take care of the rest of the transaction.

This architecture hinders the usability of all of the available payment methods that Swish supports. It has this extra cumbersomeness regardless of whether you are doing a mobile to mobile payment or if, indeed, you are paying to a shoppe clerk using a QR-code. The Bank Id is always there and for the good things that it provides it is clear that it is not a good solution from the point of view of usability and use case design.

Swish has a large market share in Sweden and seems solely geared to the Swedish markets. As it is so strong locally and offers instant payments in that area, MobilePay is now trying to get into collaboration with Swish rather than attempting to take over its market. It seems likely that Swish will win the Swedish mobile payments market and if it ends up in collaboration with MobilePay its users will be able to transfer money to most Nordic destinations via the MobilePay infrastructure.

View the typical use case flows from the [Swish page](../swish/README.md)

## Vipps

...

## Comparison table

* [Nordic Mobile Payments Brick and Mortar Comparison Spreadsheet](https://github.com/poplatek/payment-methods-book/blob/master/nordic-brick-and-mortar-comparison.ods)

