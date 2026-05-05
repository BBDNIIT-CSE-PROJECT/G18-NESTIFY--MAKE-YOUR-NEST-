<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NESTIFY - Home Automation System</title>
    <style>
        body {
            background: linear-gradient(135deg, #89f7fe, #66a6ff);
            color: #333;
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 20px;
            text-align: center;
        }
        h1 {
            font-size: 3em;
            animation: rotate 10s linear infinite;
        }
        p {
            font-size: 1.2em;
            transition: transform 0.3s;
        }
        p:hover {
            transform: scale(1.1);
        }
        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>
<body>
    <h1>NESTIFY Home Automation System</h1>
    <p>Welcome to the NESTIFY project! Experience the future of home automation.</p>
    <button onclick="toggleDetails()">See Project Details</button>
    <div id="details" style="display: none;">
        <h2>About NESTIFY</h2>
        <p>NESTIFY is your go-to solution for a smarter home. Our home automation system allows you to control devices remotely and manage your home's energy with ease.</p>
        <h3>Key Features:</h3>
        <ul>
            <li>Remote Device Control</li>
            <li>Energy Management</li>
            <li>Integrated Security Features</li>
            <li>User-Friendly Interface</li>
        </ul>
    </div>
    <script>
        function toggleDetails() {
            var details = document.getElementById('details');
            if (details.style.display === "none") {
                details.style.display = "block";
            } else {
                details.style.display = "none";
            }
        }
    </script>
</body>
</html>
