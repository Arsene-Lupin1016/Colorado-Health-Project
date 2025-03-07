# Colorado-Health-Project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phishing Awareness Project</title>

    <!-- Google Analytics Tracking Code -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());

        gtag('config', 'G-XXXXXXXXXX'); // Replace with your real Measurement ID
    </script>

    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 10%;
            background-color: #f8f9fa;
        }
        h1 {
            color: #d9534f;
        }
        p {
            font-size: 18px;
        }
        form {
            margin-top: 20px;
        }
        input, textarea {
            width: 80%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <h1>Welcome!</h1>
    <p>You have clicked on a fake phishing link.</p>
    <p>This is being used for a project of mine. Thank you!</p>
    <p>- Brandon Kim</p>

    <form action="https://formsubmit.co/youyupe123@gmail.com" method="POST">
        <input type="text" name="Name" placeholder="Enter your name" required><br>
        <textarea name="Response" rows="4" placeholder="How and why did you click the link?" required></textarea><br>
        <button type="submit">Submit</button>
    </form>
</body>
</html>
