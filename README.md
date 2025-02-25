# Yoga-Bliss-and-Brews 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yoga at The Cove Brewery with Jenna</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f4f8;
            color: #333;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }
        .container {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 600px;
            text-align: center;
        }
        h1 {
            color: #2a9d8f;
        }
        form {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        input[type="text"],
        input[type="email"] {
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
            width: 100%;
        }
        button {
            padding: 12px;
            background-color: #2a9d8f;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #21867a;
        }
        .payment-links a {
            display: inline-block;
            margin: 10px;
            padding: 10px 20px;
            background-color: #e76f51;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .payment-links a:hover {
            background-color: #d95c45;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Yoga at The Cove Brewery with Jenna</h1>
        <p>Join Jenna for a relaxing yoga session at The Cove Brewery. Sign up below and send your payment via Venmo or Zelle to reserve your spot!</p>
        <form action="https://formspree.io/f/yourFormID" method="POST">
            <input type="text" name="name" placeholder="Your Full Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <button type="submit">Sign Up</button>
        </form>
        <div class="payment-links">
            <h3>Payment Links</h3>
            <a href="https://venmo.com/JennaYoga" target="_blank">Pay via Venmo</a>
            <a href="zellepay://pay/JennaYoga" target="_blank">Pay via Zelle</a>
        </div>
    </div>
</body>
</html>
