# Dark-Tools
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FTGM Dark Tools</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #34495e;
            --accent-color: #3498db;
            --text-color: #ecf0f1;
            --card-bg: #1a252f;
            --shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--primary-color);
            color: var(--text-color);
            line-height: 1.6;
        }
        
        header {
            background-color: var(--secondary-color);
            padding: 1.5rem;
            text-align: center;
            box-shadow: var(--shadow);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
            color: var(--accent-color);
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.8;
        }
        
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1.5rem;
        }
        
        .intro {
            text-align: center;
            margin-bottom: 3rem;
            padding: 1.5rem;
            background-color: var(--card-bg);
            border-radius: 8px;
            box-shadow: var(--shadow);
        }
        
        .tools-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 1.5rem;
            margin-top: 2rem;
        }
        
        .tool-card {
            background-color: var(--card-bg);
            border-radius: 8px;
            padding: 1.5rem;
            box-shadow: var(--shadow);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .tool-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
        }
        
        .tool-card h3 {
            color: var(--accent-color);
            margin-bottom: 1rem;
            font-size: 1.4rem;
        }
        
        .tool-card p {
            margin-bottom: 1.5rem;
            opacity: 0.9;
        }
        
        .btn {
            display: inline-block;
            background-color: var(--accent-color);
            color: white;
            padding: 0.7rem 1.5rem;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-weight: 600;
            text-decoration: none;
            transition: background-color 0.3s ease;
        }
        
        .btn:hover {
            background-color: #2980b9;
        }
        
        footer {
            background-color: var(--secondary-color);
            text-align: center;
            padding: 1.5rem;
            margin-top: 3rem;
        }
        
        @media (max-width: 768px) {
            .tools-grid {
                grid-template-columns: 1fr;
            }
            
            h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>FTGM Dark Tools</h1>
        <p class="subtitle">Advanced utilities for cybersecurity and privacy</p>
    </header>
    
    <div class="container">
        <section class="intro">
            <h2>Welcome to FTGM Dark Tools</h2>
            <p>This page has been completely redesigned with a focus on cybersecurity, privacy, and network analysis tools. All previous tools have been removed and replaced with our new Dark Tools collection.</p>
        </section>
        
        <section class="tools-section">
            <h2>Dark Tools Collection</h2>
            <div class="tools-grid">
                <div class="tool-card">
                    <h3>Network Scanner</h3>
                    <p>Scan your network for connected devices, open ports, and potential vulnerabilities.</p>
                    <a href="#" class="btn">Launch Tool</a>
                </div>
                
                <div class="tool-card">
                    <h3>Password Analyzer</h3>
                    <p>Check the strength of your passwords and get recommendations for improvement.</p>
                    <a href="#" class="btn">Launch Tool</a>
                </div>
                
                <div class="tool-card">
                    <h3>Encryption Tool</h3>
                    <p>Encrypt and decrypt files and messages with advanced cryptographic algorithms.</p>
                    <a href="#" class="btn">Launch Tool</a>
                </div>
                
                <div class="tool-card">
                    <h3>VPN Checker</h3>
                    <p>Verify your VPN connection and check for DNS leaks or IP address exposure.</p>
                    <a href="#" class="btn">Launch Tool</a>
                </div>
                
                <div class="tool-card">
                    <h3>Dark Web Monitor</h3>
                    <p>Monitor if your personal information appears on dark web markets and forums.</p>
                    <a href="#" class="btn">Launch Tool</a>
                </div>
                
                <div class="tool-card">
                    <h3>Privacy Audit</h3>
                    <p>Analyze your digital footprint and get personalized privacy recommendations.</p>
                    <a href="#" class="btn">Launch Tool</a>
                </div>
            </div>
        </section>
    </div>
    
    <footer>
        <p>&copy; 2023 FTGM Dark Tools. All rights reserved.</p>
        <p>For educational and ethical use only.</p>
    </footer>
</body>
</html>
