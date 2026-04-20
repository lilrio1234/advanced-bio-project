<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Research Portal</title>
    <style>
        :root {
            --bg: #ffffff;
            --text: #333333;
            --accent: #4a90e2;
            --card-bg: #f4f7f6;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background-color: var(--bg);
            color: var(--text);
            margin: 0;
            padding: 0;
        }

        nav {
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #eee;
        }

        .search-bar {
            width: 100%;
            max-width: 500px;
            margin: 2rem auto;
            display: block;
            padding: 12px;
            border-radius: 25px;
            border: 1px solid #ddd;
            font-size: 16px;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 20px;
        }

        .card {
            background: var(--card-bg);
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            text-decoration: none;
            color: var(--text);
            transition: all 0.2s;
            border: 1px solid transparent;
        }

        .card:hover {
            border-color: var(--accent);
            background: #fff;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }

        .card h3 { margin: 10px 0 0 0; font-size: 1.1rem; }
        
        .badge {
            background: #e2e8f0;
            padding: 4px 8px;
            border-radius: 4px;
            font-size: 0.7rem;
            text-transform: uppercase;
        }
    </style>
</head>
<body>

<nav>
    <div style="font-weight: bold; color: #777;">My Portfolio v1.4</div>
    <div>April 2026</div>
</nav>

<div class="container">
    <input type="text" class="search-bar" placeholder="Search my links...">

    <div class="grid">
        <a href="https://example-mirror-1.github.io" class="card" target="_blank">
            <span class="badge">Logic</span>
            <h3>Strategic Move</h3>
        </a>

        <a href="https://example-mirror-2.vercel.app" class="card" target="_blank">
            <span class="badge">Sim</span>
            <h3>Physics Lab</h3>
        </a>

        <a href="https://example-mirror-3.netlify.app" class="card" target="_blank">
            <span class="badge">Classic</span>
            <h3>Retro Engine</h3>
        </a>

        </div>
</div>

</body>
</html>
