<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css">
    <title>Pikapikachu!</title>
    <style>
        body {
            background-color: #181818;
            color: #c6c6c6;
        }
        .container {
            max-width: 960px;
            margin: auto;
            padding: 2rem;
        }
        .sidebar {
            background-color: #202020;
            padding: 1rem;
            height: 100vh;
            overflow-y: auto;
        }
        .content {
            background-color: #282828;
            padding: 1rem;
            height: 100vh;
            overflow-y: auto;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li strong {
            color: #4d4d4d;
        }
        nav ul li a {
            color: #9d9d9d;
            text-decoration: none;
        }
        nav ul li a:hover {
            color: white;
        }
        .grid {
            display: grid;
            grid-template-columns: 1fr 3fr;
            grid-gap: 1rem;
        }
        .grid > div {
            background-color: #333;
        }
        h2, h3 {
            color: #fff;
        }
        p, li, small {
            color: #c6c6c6;
        }
        footer {
            background-color: #202020;
            color: #9d9d9d;
            padding: 0.5rem 1rem;
            text-align: center;
        }
        footer a {
            color: #9d9d9d;
            text-decoration: none;
        }
        footer a:hover {
            color: white;
        }
    </style>
</head>
<body>
    <nav class="container-fluid">
        <ul>
            <li><strong>Campaigns</strong></li>
        </ul>
        <ul>
            <li><a href="#">Hoard of the Dragon Queen</a></li>
            <li><a href="#">Lenore Backstory</a></li>
            <li><a href="#" role="button">Lenore Campaign Reference</a></li>
        </ul>
    </nav>
    <main class="container">
        <div class="grid">
            <div class="sidebar">
                <!-- Sidebar content -->
                <h3>Sessions</h3>
                <ul>
                    <li><a href="#">Session Overview</a></li>
                    <li><a href="#">PCs</a></li>
                    <li><a href="#">NPCs</a></li>
                    <li><a href="#">Locations</a></li>
                    <li><a href="#">Handouts</a></li>
                </ul>
                <h3>Overviews</h3>
                <ul>
                    <li><a href="#">Current Session</a></li>
                    <li><a href="#">Previous Sessions</a></li>
                </ul>
                <h3>Conditions</h3>
                <ul>
                    <li><a href="#">Weather Conditions</a></li>
                    <li><a href="#">Travel Conditions</a></li>
                </ul>
            </div>
            <div class="content">
                <!-- Main content -->
                <h2>Lenore Campaign Reference - Primary v1.0.0</h2>
                <h3>Session S01: You meet in a tavern...</h3>
                <p>Session date: 2022-10-09</p>
                <p>Campaign date: Day 1</p>
                <p>Starting notes: Don't die.</p>
                <!-- Add more content as needed -->
            </div>
        </div>
    </main>
    <footer class="container">
        <small><a href="#">About</a> • <a href="#">Contact</a></small>
    </footer>
</body>
</html>



