---
id: payments
title: Payments
sidebar_label: Payments
---

## Payment Providers
When payment is required for a bookings, the user will be presented with a list of payment options to choose from.  
At the moment, BetterBook supports several payment providers which can process payments from customers.  

The following payment providers are supported:
- [Stripe](www.stripe.com)
- [Flutterwave](www.flutterwave.com)
- [PayGate](www.paygate.co.za)
- [PayFast](www.payfast.co.za)
- [SnapScan](www.snapscan.co.za)


## Using your own payment provider accounts

Should you already have an agreement with one of these providers, you can configure your own account details 
using the BetterBook Portal.  Any payments received from customers
will settle directly into the account that have been agreed with the payment provider.  


## Generic payment types
BetterBook also allows generic payment types to be used in bookings as in the case of Cash and EFT.  Although BetterBook does not
help manage the payments in terms of settlements, bookings can still be managed and confirmed from the BetterBook portal.

For example - when a booking is made with an EFT payment, BetterBook provisionally approves the booking pending receipt of the payment.  
The customer is required to make an EFT into your account directly, and once payment has been confirmed (through proof of payment sent to you directly), the payment can be confirmed on the BetterBook portal.  This will confirm the booking and customer will be notified via
email of the receipt and the booking confirmation.


## PayFast Configuration

The following shows the configuration available to set up your PayFast account details in order to receive payments 
directly into your account from PayFast.

![PayFast Configuration](assets/payfast-settings.png?screenshot60) 

#### Settings
The following table lists the available settings:

|  Setting |Description   |
|---|---|
|  __Merchant ID__| This is a string supplied by PayFast when signing up for an account.| 
|  __Merchant Key__| This is a string supplied by PayFast when signing up for an account.| 
|  __Completed Redirect URL__| This is a web address where PayFast will redirect the customer after a payment has been processed successfully.  This should be the address of the Booking page from which the payment was initiated.| 
|  __Cancelled Redirect URL__| This is a web address where PayFast will redirect the customer after a payment has been cancelled.  This should be the address of the Booking page from which the payment was initiated.| 
|  __Enable email notifications on successful payments__| This lets PayFast send an email confirmation on every payment that is processed.| 
|  __Notification email address__ |  When email notifications are enables, this is the address to which notifications will be sent. |

