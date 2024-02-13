<img class="w-75" src="https://i.ibb.co/2KbqLG2/Westin-Pay.png" alt="image">

<!DOCTYPE html>
<html lang="en">
<head>
 
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        form {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 300px;
            text-align: center; /* Center align the form content */
        }

        label,
        input[type="text"],
        input[type="hidden"],
        input[type="submit"] {
            margin-bottom: 15px;
            padding: 10px;
            width: 100%;
            box-sizing: border-box;
        }

        input[type="submit"] {
            background-color: #007bff;
            color: #fff;
            cursor: pointer;
            font-size: 16px;
            font-weight: bold;
            border: none;
            border-radius: 4px;
        }

        input[type="submit"]:hover {
            background-color: #0056b3;
        }

        /* Center align the logo */
        img {
            display: block;
            margin: 0 auto;
            max-width: 100%;
            height: auto;
        }
		   /* Logoların bulunduğu kısım */
        .payment-logos {
            margin-top: 20px;
            display: flex;
            justify-content: space-around;
            align-items: center;
        }

        .payment-logos img {
            max-width: 50px;
            height: auto;
        }
    </style>


<form id="paymentForm" action="https://westinpay.com/payment/initiate" method="post">
    <!-- Logo -->
    <img src="https://westinpay.com/assets/images/logoIcon/logo.png" alt="WestinPay Logo" style="max-width: 150px;">

    <label for="paymentReferenceNumber">Payment reference number:</label>
    <input type="text" id="identifier" name="identifier" value="">
    <label>Set Amount</label>
    <input type="hidden" name="currency" value="USD">
    <input type="text" name="amount" value="1.00">
    <input type="hidden" name="details" value="Pay with WestinPay">
    
    <!--- Set the return URL for your domain here --->
    <input type="hidden" name="ipn_url" value="http://yourdomain.com/ipn_url.php">
    <input type="hidden" name="cancel_url" value="http://yourdomain.com/cancel_url.php"> 
    <input type="hidden" name="success_url" value="http://yourdomain.com/success_url.php">
    <input type="hidden" name="public_key" value="xmqmefhjz44mr43ylli0yqqjuxkktilcu6h6pxub0ly0jt3c51">
    <input type="hidden" name="site_logo" value="https://westinpay.com/assets/images/logoIcon/logo.png">
    <input type="hidden" name="checkout_theme" value="dark">
    <input type="hidden" name="customer_name" value="John Doe">
    <input type="hidden" name="customer_email" value="john@mail.com">

    <!-- Add more hidden fields as needed -->

    <input type="submit" value="Submit Payment">
	
	
    <!-- Diğer kripto para logolarını ekleyin -->

</form>

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
</html>
