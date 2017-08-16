# Brick and mortar mobile payment methods comparison

## About

This page is for discussion and comparison of those different ways of addressing mobile paying in brick and mortar situations. The specific use cases can be found from the respective pages of this book that explain the technology for MobilePay, Vipps, Swish, Dankort mobile and so on.

## Feasibility of the new mobile payment methods for brick-and-mortar situations

The new mobile payment methods vary but the most commonly used ways of communicating seem to be:

1. Bluetooth
2. NFC
3. QR-code
4. Internet

The solutions that support NFC allow for the user presenting/tapping (or double tapping) their phone to the NFC device to make a payment. Bluetooth works similarly. The QR-code solutions depend on the mobile phone camera which is used to take a photo of the QR-code that includes the payment information including but perhaps not limited to the sales price. There are also mobile to mobile solutions that depend on both mobile phones having Internet connections.

The strenghts of these technologies is that they do support the payment via a mobile phone. However, there is a hassle in many of the payment methods that is not non-significant. Especially some QR-code solutions look cumbersome and this is true to an extent to almost all payment methods that depend on the mobile phones because of the needs of activating the mobile phone screen, possible using a PIN-code or a swipe to unlock the screen, starting the application if it is not already running and signing into the payment application via a PIN-code or perhaps a finger print.

There seems to be methods of mitigating these problems and steps are being taken into making the purchase process less difficult on mobile devices. The newest solutions to this end seem to depend on starting the purchase from the locked mobile phone screen. There is a prototype video about this sort of payment method in the Internet and also at least Danske Bank has come out w/a MobilePay variant that actually brings this type of payment method to the market.

There are also advances being made in order to allow a payment using a mobile phone from the black screen and open screen. At least MobilePay is making efforts to get one or both of these payment methods to work. The black screen means the black screen that is displayed when the phone is not in use and the open screen refers to the screen lock having been opened already but that the application has not been started.

Also the support for mobile phone payment methods are getting more and more supported by the other hardware. Where it was once necessary e.g. for a MobilePay solution to have an extra Bluetooth/QR-code reader, these features are now beginning to be supported by payment terminals that look classic and ordinary. This removes the hassle of the new mobile phone payment methods that is related to the need of extra devices on the field.

Overall, even if there is significant advancement in the mobile phone payment method market, there is still some progress to be made. That said, the newest setups w/locked screen payment variants used together w/the old school payment terminals that support mobile payment methods seem now to be ready for wide-scale use. They are getting the threshold of being to cumbersome to use for comfort and then all that is left is the convenience of not needing to have your credit/debit card w/you when you leave the house.

The user bases are also exploding due to the honey that was given to the end-users: the apps are mostly free-of-cost to the end users and they allow for money transfer between friends as well as loaning to friends and splitting of bills. These new features along w/mostly supported instant payments on the mobile devices can clearly be attractive to the end-users.

## An Important Caveat

One thing that seems to be missing from lots of material is the very beginning of the mobile payment. This includes taking out the phone, perhaps opening a screen lock, starting up the application if it is not already running and then signing into the application which might take a PIN code or perhaps a finger print.

We would need to test the solutioins in real life to be certain how this part of the process works on different technologies. However, there is a video floating around in the Internet that shows some prototype solution that enables a customer to start the payment from a locked screen situation.

Whether that works only if the app has been started previously and perhaps a sign-in into the app has been made before cannot be deduced from the video but what can be said is that it looked rather handy apart from these caveats.

Perhaps this is Dankort Mobile prototype. Please view the video for yourself to decide: https://www.youtube.com/watch?v=FSLH9PvwnDU

The use cases explained in their own respective pages have the caveat that they are based on best available material of which some is meant for advertising purposes and does not therefore necessarily reflect the real world user experience.


## About the approaches

There are many ways to go about the brick and mortar mobile payment situation. Some solution start from the perspective of trying to integrate the new mobile payment solution to the already existing setup at the merchant's shoppe. Some solutions try to completely avoid this in an attempt to bypass all the older systems and then try to expand towards the existing solutions as necessary from this exact opposite starting point. There are certainly strenghts and weaknessess to both of these ways of approaching the brick and mortar payment situation.

### Dankort Mobile

The Dankort mobile solution is a white label wallet solution for mobile payments. White labeling is supported in order to be able to have the local banks use their logos in the apps to ensure customer loyalty. Overall the Dankort Mobile seems to be based on extending the existing solutions the customers already have at their sales locations.

Dankort mobile appears to support several payment methods but appears to be, above all, an old school way of going about it. The credit card is put into the mobile phone, so to speak, and a regular NFC payment can be made in the same way as you would w/a credit card.

Dankort mobile goes much further than this, however. There is an additional Bluetooth device that can be added to the existing POS setup which allows for paying via the mobile Dankort app through presenting/tapping the phone to this new device.

There is a new check in/check out solution that lets the customer in some way to first tap their dankort phone to a receiver which start the transaction processing and the transaction is processed at the same the customer is packing their things and completes apparently when the cashier has finished handling the products for this customer. This is basically a solution for making the bag packing and the payment work in parallel.

QR-code is also supported even though it does look somewhat clumsy as a use case and then there is the prototype of starting a purchase from a locked screen situation via the mobile phone which may or may not be a future Dankort mobile product.

The specifics about the use cases seem to depend on the setup. It is a bit different if you have a mobile phone and standalone terminal than it is if you have an integrated payment terminal w/a POS and a bluetooth reader device in addition to the mobile phone.

Also, it may be that the iOS/Apple phone solution differs from the Android solution which is based on the Android HCE technology. The iOS solution may be Bluetooth-based and it is not certain what features it supports and what features it perhaps does not.

View the specifics about the use cases from here: [Dankort Mobil](../dankort/dankortmobil/README.md)

## Danske Mobilepay

Danske Mobilepay is beginning to be well supported. There are payment terminals w/bluetooth and QR-code support that can be used as a standalone payment terminals or integrated to a POS that can handle MobilePay. This means that no additional MobilePay device is needed which used to be the case.

MobilePay is also out with a new locked screen purchase variant that makes low value purchases easier. They are saying that the will follow up with possibly both open screen and black screen purchase variants. There is also a setup where the clerk may use a mobile phone to receive the payment either over the Internet or via a bluetooth tap and probably also QR-code is supported.

Danske MobilePay seems to have succeeded in establishing itself quite well on the mobile payments market. MobilePay allows for many of their users to use their existing credit/debit cards and bank accounts in the Nordics and no Danske Bank account/card is necessary although getting them is the only current way of getting around the weakness of the MobilePay infrastructure, which is that payments are instant only to Danske Bank accuonts.

View the specifics about the use cases from here: [Danske MobilePay](../mobilepay/README.md)

## Swedish Swish

## Comparison table

* [Nordic Mobile Payments Brick and Mortar Comparison Spreadsheet](https://github.com/poplatek/payment-methods-book/blob/master/nordic-brick-and-mortar-comparison.ods)




