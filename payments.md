---
id: payments
title: Payments
sidebar_label: Payments
---

## Payments
Taking upfront payment for bookings and tickets is one of the most important features of online booking systems.  
BetterBook supports various payment providers to enable you to take online payments across the globe.

### Payment Providers
  
The following payment providers are supported:
- [Stripe](www.stripe.com)
- [Flutterwave](www.flutterwave.com)
- [PayGate](www.paygate.co.za)
- [PayFast](www.payfast.co.za)
- [SnapScan](www.snapscan.co.za)


## Using your own payment provider accounts

When payments are enabled for bookings, the customer will be guided through a checkout process where the 
various payment options are presented, depending on your payment provider(s).  Is is possible to 
configure multiple payment providers to give more options to your customers.

Please note that you need to sign up to a payment partner in order to take online payments through BetterBook.
Once you have signed up, you can enable the payment type and configure your account details 
through the [BetterBook Portal](https://portal.betterbook.io).  Any payments received from customers
will settle directly into the account that have been configured with the payment provider.  


## Generic payment types
BetterBook also allows generic payment types to be used in bookings for example `Cash` and `Electronic Funds Transfer - EFT`.
Although BetterBook does not help manage the payments in terms of settlements, bookings are still 
managed and confirmed via the BetterBook Portal or mobile apps.

For example - when a booking is made with an `EFT` payment, BetterBook provisionally approves the booking 
pending receipt of the payment.  The customer is required to make an EFT into your account directly, and once payment has been 
confirmed (through proof of payment sent to you directly), the payment can be confirmed on the BetterBook Portal or mobile 
apps.  This will confirm the booking and customer will be notified via email of the receipt and the booking confirmation.


## PayFast Configuration

The following shows the configuration available to set up your PayFast account details in order to receive payments 
directly into your account from PayFast.

![PayFast Configuration](assets/payfast-configuration-popup.png?screenshot) 

#### Settings
The following table lists the available settings:

|  Setting |Description   |
|---|---|
|  __Merchant ID__| This is a string supplied by PayFast when signing up for an account.| 
|  __Merchant Key__| This is a string supplied by PayFast when signing up for an account.| 
|  __Enable email notifications on successful payments__| This lets PayFast send an email confirmation on every payment that is processed.| 
|  __Notification email address__ |  When email notifications are enables, this is the address to which notifications will be sent. |

