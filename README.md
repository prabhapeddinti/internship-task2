<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basics of Web Development</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #00b4db, #0083b0);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            width: 80%;
            max-width: 800px;
            background: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
            text-align: center;
        }

        h1 {
            color: #00695c;
            margin-bottom: 20px;
            font-size: 40px;
        }

        p {
            font-size: 20px;
            color: #444;
            line-height: 1.7;
            margin-bottom: 25px;
        }

        img {
            width: 250px;
            margin-bottom: 25px;
            transition: 0.4s;
        }

        img:hover {
            transform: scale(1.05);
        }

        button {
            background: #00796b;
            color: white;
            padding: 14px 30px;
            border: none;
            border-radius: 10px;
            font-size: 18px;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background: #004d40;
            transform: scale(1.05);
        }

        .footer {
            margin-top: 30px;
            color: gray;
            font-size: 15px;
        }
    </style>
</head>

<body>

    <div class="container">

        <h1>Basics of Web Development</h1>

        <p>
            This webpage is created using HTML, CSS, and JavaScript
            as part of my internship task project.
        </p>

        <img src="https://cdn-icons-png.flaticon.com/512/1055/1055687.png"
            alt="Web Development">

        <br>

        <button onclick="showMessage()">
            Click Me
        </button>

        <div class="footer">
            Internship Task - ApexPlanet Software Pvt Ltd
        </div>

    </div>

    <script>

        function showMessage() {
            alert("Hello! JavaScript is working successfully.");
        }

    </script>

</body>

</html>
