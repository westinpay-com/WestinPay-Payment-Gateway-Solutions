<img class="w-75" src="https://i.ibb.co/2KbqLG2/Westin-Pay.png" alt="image">

    
<form action="https://westinpay.com/payment/initiate" method="post">
      <!--- For manual entry of amounts and other variables, you can use "text" instead of "hidden"  --->
    <input type="hidden" name="identifier" value="DFU80XZIKS">
    <input type="hidden" name="currency" value="USD">
    <input type="hidden" name="amount" value="1.00">
    <input type="hidden" name="details" value="Pay with WestinPay">
    
     <!--- Set the return url for your domain here --->
    <input type="hidden" name="ipn_url" value="http://yourdomain.com/ipn_url.php">
    <input type="hidden" name="cancel_url" value="http://yourdomain.com/cancel_url.php"> 
    <input type="hidden" name="success_url" value="http://yourdomain.com/success_url.php">
    <input type="hidden" name="public_key" value="Your Westinpay Merchant Public Key">
    <input type="hidden" name="site_logo" value="https://westinpay.com/assets/images/logoIcon/logo.png">
    <input type="hidden" name="checkout_theme" value="dark">
    <input type="hidden" name="customer_name" value="John Doe">
    <input type="hidden" name="customer_email" value="john@mail.com">

    <!-- Add more hidden fields as needed -->

    <input type="submit" value="Submit Payment">
</form>


