<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NESTIFY Home Automation System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(120deg, #f0f0f0, #d6d6d6);
            margin: 0;
            padding: 0;
            overflow: hidden;
        }
        h1 {
            color: #4A90E2;
            text-align: center;
            animation: rotate 10s infinite linear;
        }
        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        .hover-effect {
            transition: transform 0.3s;
        }
        .hover-effect:hover {
            transform: scale(1.1);
        }
        .content {
            text-align: center;
            padding: 50px;
        }
        .button {
            background-color: #4A90E2;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #357ABD;
        }
    </style>
</head>
<body>
    <div class="content">
        <h1 class="hover-effect">NESTIFY Home Automation System</h1>
        <p>This project is built with a technology stack of:</p>
        <ul>
            <li>React.js</li>
            <li>Node.js</li>
            <li>MongoDB</li>
        </ul>
        <h2>API Routes</h2>
        <p>List of API routes will be here.</p>
        <h2>Setup Instructions</h2>
        <p>Instructions on how to set up the project will be provided here.</p>
        <h2>Contributing Guidelines</h2>
        <p>Guidelines for contributing to the project will be outlined here.</p>
        <button class="button">Learn More</button>
    </div>
</body>
</html>
