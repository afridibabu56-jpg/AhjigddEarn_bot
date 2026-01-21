<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Mobile Site</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f2f5;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
            text-align: center;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        h1 {
            margin: 0;
            font-size: 24px;
        }
        .container {
            flex: 1;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        .card {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            width: 90%;
            max-width: 400px;
        }
        .btn {
            display: inline-block;
            background-color: #28a745;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 50px;
            font-size: 18px;
            font-weight: bold;
            margin-top: 20px;
            transition: background 0.3s;
        }
        .btn:hover {
            background-color: #218838;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 10px;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome</h1>
    </header>

    <!-- Main Content -->
    <div class="container">
        <div class="card">
            <h2>Get Your File</h2>
            <p>Click the button below to start.</p>
            
            <!-- Button -->
            <a href="#" class="btn">Click Here</a>
        </div>
    </div>

    <!-- আপনার দেওয়া বিজ্ঞাপনের কোডটি এখানে বসানো হয়েছে -->
    <script src='//libtl.com/sdk.js' data-zone='9626169' data-sdk='show_9626169'></script>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 My Website</p>
    </footer>

</body>
</html>
