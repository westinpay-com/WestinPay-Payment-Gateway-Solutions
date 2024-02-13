<img class="w-75" src="https://i.ibb.co/2KbqLG2/Westin-Pay.png" alt="image">

                                <div class="doc-code">
                                <div class="doc-code-inner">
                                    <div class="code-block">
                                        <button class="clipboard-btn" data-clipboard-target="#html">copy</button>
                                        <div class="code-block-header">Example HTML code</div>

<pre>
<code class="language-html" id="html">
    
&lt;form action="https://westinpay.com/payment/initiate" method="post">
      &lt;!--- For manual entry of amounts and other variables, you can use "text" instead of "hidden"  --->
    &lt;input type="hidden" name="identifier" value="DFU80XZIKS">
    &lt;input type="hidden" name="currency" value="USD">
    &lt;input type="hidden" name="amount" value="1.00">
    &lt;input type="hidden" name="details" value="Pay with WestinPay">
    
     &lt;!--- Set the return url for your domain here --->
    &lt;input type="hidden" name="ipn_url" value="http://yourdomain.com/ipn_url.php">
    &lt;input type="hidden" name="cancel_url" value="http://yourdomain.com/cancel_url.php"> 
    &lt;input type="hidden" name="success_url" value="http://yourdomain.com/success_url.php">
    &lt;input type="hidden" name="public_key" value="Your Westinpay Merchant Public Key">
    &lt;input type="hidden" name="site_logo" value="https://westinpay.com/assets/images/logoIcon/logo.png">
    &lt;input type="hidden" name="checkout_theme" value="dark">
    &lt;input type="hidden" name="customer_name" value="John Doe">
    &lt;input type="hidden" name="customer_email" value="john@mail.com">

    &lt;!-- Add more hidden fields as needed -->

    &lt;input type="submit" value="Submit Payment">
&lt;/form>



</code></pre>


<script>
    // Generate a random payment reference number and set it in the form
    document.addEventListener("DOMContentLoaded", function() {
        var randomReferenceNumber = generateRandomReferenceNumber();
        document.getElementById("identifier").value = randomReferenceNumber;
    });

    function generateRandomReferenceNumber() {
        var characters = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789';
        var referenceNumber = '';

        for (var i = 0; i < 10; i++) { // You can adjust the length of the reference number
            var randomIndex = Math.floor(Math.random() * characters.length);
            referenceNumber += characters.charAt(randomIndex);
        }

        return referenceNumber;
    }
</script>

</body>
</code></pre>
