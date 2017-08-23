# Brick and mortar mobile payment methods comparison

## About

This page is for discussion and comparison of different ways of addressing mobile payments in brick and mortar situations. The specific use cases can be found from the respective pages of this book that explain the technology for [MobilePay](../mobilepay/README.md), [Vipps](../vipps/README.md), [Swish](../swish/README.md), [Dankort](../dankort/dankortmobil/README.md) mobile and so on. 

Business and market level comparisons and considerations can be viewed from [here](../biz-lvl-comparison/README.md).  There is also a spreadsheet comparison about the different players [generally](https://github.com/poplatek/payment-methods-book/blob/master/nordic-brick-and-mortar-comparison.ods) and as it pertains to the brick and mortar more [specifically](https://github.com/poplatek/payment-methods-book/blob/master/nordic-brick-and-mortar-comparison.ods).

There is also a collection of [mobile app features](../mobile-app-features/README.md), which attempts towards comprehensiveness.

## TOC

<!-- toc -->

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


## Mobilepay

MobilePay's use cases seem generally quite well designed and they seem reasonably good for even brick-and-mortar payments. MobilePay used to require an extra Bluetooth/QR-Code device but this is no longer the case because e.g. Verifone and Ingenico are offering classic payment terminals that support these communications technologies. These payment terminals are probably available for both standalone and POS integrated setups.

On top of that, MobilePay uses only one app and is even sporting a locked screen purchase that allows the customer to purchase using mobile phone notifications. Low value purchases can be paid this way without the need to open the app and feed pin codes. MobilePay is trying to get the black screen and open screen purchases to work, as well. In addition, MobilePay has a good support of features.

There is a mobile to mobile setup that basically replaces a standalon terminal where the clerk can use a mobile phone to receive the payment either over the Internet or via a bluetooth tap and probably also via a QR-code.

MobilePay is not tied to one bank and 70% of its user base is from a bank other than Danske Bank. Instant payments can only be made to Danske Bank accounts, however.

View the specifics about the use cases from here: [Danske MobilePay](../mobilepay/README.md)

## Swish

Swish is Sweden and SEK only and supports instant payments to all participating banks as well as being able to show the payee's name before the payment is being made.

To be able to do this, Swish uses a Swedish BankId application as an extra mobile app and in using two mobile apps instead of one, its use cases are more cumbersome than they need to be. 

During registration you need to be eligible for both of these apps. Then, when in use, most things are done in the Swish app that then launches the Bank ID to do its part.

After Bank ID processing has been done, the Swish app reappers again to take care of the rest of the transaction.

This architecture hinders the usability of all of the available payment methods that Swish supports. 

View the typical use case flows from the [Swish page](../swish/README.md)

## Vipps

Vipps is the major Norwegian player with its own innovations. 

Vipps app has a chat that lets the users converse with one another and supports a message that will be attached to a payment.

Vipps also has an innovative SMS-based solutions for letting Vipps users make payments to non-Vipps users.

If a Vipps user pays a non-Vipps user the latter will be sent a text message that tells them of the payment they are about to receive as long as they install the Vipps app.

This is brilliant because Vipps is basically paying the payment receiver to install their app while the payment, in reality, is not paid by Vipps.

## Dankort Mobile

Dankort differs fundamentally from the other and typical mobile phone payment apps. It is not an Internet based mobile payment app but a white label mobile wallet which, in effect, holds an existing Dankort payment card the customer already has. Dankort app doesn't appear to support the person to person payment features that are typical of the other mobile phone payment apps.

The Dankort app can be used in the brick and mortar case just like a contactless NFC card.  This is a strength because the payment terminals supporting NFC have been already largely fielded for contactless payment cards.

However, the Dankort app is declared to still be in beta. While its iOS version has a 4+ rating its Android rating is a lowly 1.7/5. The app download rates are also two decades lower than for the competing apps. Then again, Dankort payment cards are used in retail payments as much as cash, so there is that potential for growth.

Dankort app also supports Bluetooth and QR-codes as well as a check in/check out solution for making the transaction handling go in parallel with real world back packing at a store.

The QR-code use case looks somewhat clumsy.

There may be a prototype of starting a purchase from a locked screen situation via the mobile phone which may or may not be a future Dankort mobile product. This is unclear.

The specifics about the use cases seem to depend on the device setup.

The iOS solution is probably Bluetooth-based and might not support the exact some things as the Android version which is based on Android HCE.

View the specifics about the use cases from here: [Dankort Mobil](../dankort/dankortmobil/README.md)

