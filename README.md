# mpesapay
 Mpesa Payment API


# Android M-Pesa Daraja SDK

This is a simple Android M-PESA SDK to allow you to integrate Safaricom M-PESA API 
> This version only offers the MPESA Express (STKPush) Support.

## Download

Daraja available for download on `mavenCentral()`

Dart

```kotlin
dependencies {
    implementation("com.androidstudy:daraja:2.0.0")
}
```

Groovy

```groovy
dependencies {
    implementation 'com.androidstudy:daraja:2.0.0'
}
```

## Quick Start

WIP - need to be updated


## Requirements

* AndroidX
* Min SDK 14+
* Java 8+

## Lipa na M-Pesa Online Payment API

The following table highlights the requirements needed by Daraja, as described in the [Safaricom Developer API Page](https://developer.safaricom.co.ke/lipa-na-m-pesa-online/apis/post/stkpush/v1/processrequest)

| Name                  | Description           | Parameter Type    | Possible Values |
| -------------         |:--------------------: | ----------------: | ---------------:|
| BusinessShortCode     | The organization shortcode used to receive the transaction        | Numeric             | Shortcode (6 digits)           |
| Passkey     | Lipa Na Mpesa Online PassKey       | Alpha-Numeric              |           | 
| Amount     | The amount to be transacted      | Numeric             | 100           |
| PhoneNumber     | The MSISDN sending the funds        | Numeric             | MSISDN (12 digits)          |
| CallBackURL     | Call Back URL        | URL             | https://ip or domain:port/path           |
| AccountReference     | Account Reference        | Alpha-Numeric	             | Any combinations of letters and numbers |
| TransactionDesc     | Description of the transaction        | String             | any string of less then 20 characters          |

> Get the Pass Key Here : https://developer.safaricom.co.ke/test_credentials
