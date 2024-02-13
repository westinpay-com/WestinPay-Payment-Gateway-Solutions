<img class="w-75" src="https://i.ibb.co/2KbqLG2/Westin-Pay.png" alt="image">
<a href="https://westinpay.com/testpayment.html" target="_blank">
    <img width="543" height="55" src="https://westinpay.com/img.png" alt="WestinPay Logo">
</a>
```html
<pre><code class="language-html">
<style>
    .payment-button {
        background-color: #4CAF50; /* Green color */
        border: none;
        color: white;
        padding: 20px 40px; /* Wider and longer */
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin: 4px 2px;
        cursor: pointer;
        border-radius: 8px; /* Rounded corners */
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Light shadow effect */
    }
</style>

<!-- Payment form -->
<form action="https://westinpay.com/payment/initiate" method="post">
    <input type="hidden" name="identifier" value="Test Order Payment">
    <input type="hidden" name="currency" value="USD">
    <input type="hidden" name="amount" value="1.00">
    <input type="hidden" name="details" value="Pay with WestinPay">
    <input type="hidden" name="ipn_url" value="http://example.com/ipn_url.php">
    <input type="hidden" name="cancel_url" value="http://example.com/cancel_url.php">
    <input type="hidden" name="success_url" value="http://example.com/success_url.php">
    <input type="hidden" name="public_key" value="your-westinpay-public-key">
    <input type="hidden" name="site_logo" value="https://westinpay.com/assets/images/logoIcon/logo.png">
    <input type="hidden" name="checkout_theme" value="dark">
    <input type="hidden" name="customer_name" value="John Doe">
    <input type="hidden" name="customer_email" value="john@mail.com">
    <input type="submit" value="Test Payment Button" class="payment-button">
</form>
</code></pre>

 
# WestinPay Transfer

WestinPay Transfer is an excellent solution for payment gateway integration. WestinPay enables your customers to make secure and fast payments, ensuring smooth merchant transactions.

## WestinPay Transfer PHP Entegrasyon

For PHP integration with WestinPay Transfer, please visit the [WestinPay Transfer PHP Integration Repository](https://github.com/westinpay-com/API).

## Features

- Secure and fast payments
- Ideal for money transfers
- User-friendly interface
- Multi-currency support
- Fraud protection
- Customizable payment forms
- Real-time transaction monitoring
- Seamless refunds
- Dedicated customer support
- Integration with popular e-commerce platforms

## Integration Steps

1. **Creating a Payment Link**: Create a special payment link for your customers to make payments.
2. **Integrating the Payment Form**: Integrate the payment form into your website to allow your customers to make payments.
3. **Completing the Payment Process**: When your customers complete the payment, they will be redirected to success or cancellation pages.
4. **Configuring Webhooks**: Set up webhooks to receive notifications about payment events.
5. **Implementing Two-Factor Authentication**: Enhance security by implementing two-factor authentication for payment verification.
6. **Customizing Email Notifications**: Customize email notifications to keep your customers informed about their payment status.
7. **Setting Up Recurring Payments**: Enable recurring payments for subscription-based services.
8. **Integrating with Accounting Software**: Seamlessly integrate payment data with accounting software for streamlined financial management.
9. **Enabling Multi-language Support**: Provide payment forms in multiple languages to cater to a global audience.
10. **Performing A/B Testing**: Test different payment form designs and configurations to optimize conversion rates.

For more advanced integration options, please visit the [Merchant Developer Page](https://westinpay.com/api/documentation#currency).

## Registration

To start using WestinPay, users can register [here](https://westinpay.com/user/register), while merchants can register [here](https://westinpay.com/merchant).

## Mobile Applications

Download the WestinPay Transfer app for your device:
- [Google Play Store](https://play.google.com/store/apps/details?id=com.westinpaytransfer.app)
- [Apple App Store](https://apps.apple.com/gb/app/westinpay-transfer/id6470148207?platform=iphone)

## Supported Currencies

| Currency Name        | Currency Symbol | Currency Code |
|----------------------|-----------------|---------------|
| United States Dollar | $               | USD           |
| GBP                  | £               | GBP           |
| Euro                 | €               | EUR           |
| Canadian dollar      | CAD             | CAD           |
| Swiss franc          | CHF             | CHF           |
| Australian dollar    | A$              | AUD           |
| Hong Kong dollar     | HK$             | HKD           |
| Indian rupee         | ₹               | INR           |
| New Zealand dollar   | NZ$             | NZD           |
| Russian ruble        | ₽               | RUB           |
| Romanian leu         | L               | RON           |
| Bulgarian lev        | BGN             | BGN           | 
| Swedish krona        | kr              | SEK           |
| Turkish lira         | ₺               | TRY           |
| Brazilian real       | R$              | BRL           |
| Polonya zlotisi      | zł              | PLN           |
| South Africa ZAR     | R               | ZAR           |
| Bitcoin              | ₿               | BTC           |
| ETHEREUM             | Ξ               | ETH           |
| DOGECOİN             | Ð               | DOGE          |
| AZN MANAT            | ₼               | AZN           |
| TRX                  | TRX             | TRX           |
| USDT.BEP20           | ₮               | USDT          |
| Monero XMR           | XMR             | XMR           |

WestinPay streamlines your payments with its user-friendly interface and secure infrastructure, helping you optimize your payment processes. Choose WestinPay today and streamline your payment transactions.
