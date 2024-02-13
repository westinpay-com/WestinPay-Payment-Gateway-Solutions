<img class="w-75" src="https://i.ibb.co/2KbqLG2/Westin-Pay.png" alt="image">

                                               <div class="doc-section" id="ipn">
                            <div class="doc-content">
                                <section id="">
                                    <h2>Sample HTML form codes</h2>
                                    <p class="mt-2">You can accept payments using the sample HTML codes below..</p>
                                    <hr>
                                   <h5>Codes and parameters:</h5>
                                 
                                    <div class="table-responsive">
                                        <table class="table table-bordered">
                                            <thead>
                                                <tr>
                                                    <th>Param Name</th>
                                                    <th>Description</th>
                                                </tr>
                                            </thead>
                                            <tbody>
                                                <tr>
                                                    <td>status</td>
                                                    <td>Payment success status.</td>
                                                </tr>
                                                <tr>
                                                    <td>identifier</td>
                                                    <td>Identifier is basically for identify payment at your end.</td>
                                                </tr>
                                                <tr>
                                                    <td>public_key</td>
                                                    <td>Your westinpay merchant public key.</td>
                                                </tr>
                                                <tr>
                                                    <td>success_url</td>
                                                    <td> URL to redirect if payment is successful.</td>
                                                </tr>
                                                  <tr>
                                                    <td>cancel_url</td>
                                                    <td> URL to redirect if payment fails.</td>
                                                </tr>
                                                 <tr>
                                                    <td>amount</td>
                                                    <td> The payment amount you will receive, if you want, you can call the valid parameter on your site, for example:  .</td>
                                                </tr>
                                                 <tr>
                                                    <td>identifier</td>
                                                    <td> Payment ID, random value can be defined. It is used to make it easier for you to control. ex: .</td>
                                                </tr>
                                            </tbody>
                                        </table>
                                    </div>
                               <form action="https://westinpay.com/payment/initiate" method="post">
    <input type="hidden" name="identifier" value="DFU80XZIKS">
    <label>Currency:</label>
    <input type="text" name="currency" value="USD"  readonly="" >
        <label>Set Amount:</label>

    <input type="text" name="amount" value="1.00">
    <label>Description: </label>
    <input type="text" name="details" value="product" readonly="" >
    
     <!--- Set the return url for your domain here --->
    <input type="hidden" name="ipn_url" value="https://westinpay.com/api/documentation">
    <input type="hidden" name="cancel_url" value="https://westinpay.com/api/documentation"> 
    <input type="hidden" name="success_url" value="https://westinpay.com/api/documentation">
    <input type="hidden" name="public_key" value="xmqmefhjz44mr43ylli0yqqjuxkktilcu6h6pxub0ly0jt3c51">
    <input type="hidden" name="site_logo" value="https://westinpay.com/assets/images/logoIcon/logo.png">
    <input type="hidden" name="checkout_theme" value="dark">
    <input type="hidden" name="customer_name" value="John Doe">
    <input type="hidden" name="customer_email" value="john@mail.com">

    <!-- Add more hidden fields as needed -->

 <input style="background-color:MediumSeaGreen;" type="submit" value="Test Submit Payment" >
</form>

















                            </div>  
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


                                    </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
