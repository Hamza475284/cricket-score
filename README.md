<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Live Cricket Scores</title>
    <style>
        /* Reset and global styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background-color: #0275d8;
            color: white;
            text-align: center;
            padding: 20px;
        }
        header h1 {
            font-size: 28px;
            margin: 0;
        }
        nav {
            background-color: #0056b3;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            font-size: 16px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .section {
            margin-bottom: 30px;
        }
        .section h2 {
            font-size: 22px;
            color: #0275d8;
            margin-bottom: 15px;
            border-bottom: 2px solid #0275d8;
            padding-bottom: 5px;
        }
        iframe {
            width: 100%;
            border: none;
            border-radius: 5px;
            overflow: hidden;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #0056b3;
            color: white;
            text-align: center;
            padding: 15px;
            font-size: 14px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Live Cricket Scores</h1>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="#live">Live Scores</a>
        <a href="#upcoming">Upcoming Matches</a>
        <a href="#completed">Completed Matches</a>
    </nav>

    <!-- Main Container -->
    <div class="container">
        <!-- Live Matches Section -->
        <div class="section" id="live">
            <h2>Live Matches</h2>
            <iframe 
                src="https://www.espncricinfo.com/live-cricket-score" 
                frameborder="0" 
                scrolling="no" 
                height="400px">
            </iframe>
        </div>

        <!-- Upcoming Matches Section -->
        <div class="section" id="upcoming">
            <h2>Upcoming Matches</h2>
            <iframe 
                src="https://www.espncricinfo.com/schedule" 
                frameborder="0" 
                scrolling="no" 
                height="400px">
            </iframe>
        </div>

        <!-- Completed Matches Section -->
        <div class="section" id="completed">
            <h2>Completed Matches</h2>
            <iframe 
                src="https://www.espncricinfo.com/results" 
                frameborder="0" 
                scrolling="no" 
                height="400px">
            </iframe>
        </div>
    </div>

    <!-- Footer Section -->
    <footer>
        &copy; 2024 Live Cricket Updates | Powered by ESPN
    </footer>
</body>
</html>
