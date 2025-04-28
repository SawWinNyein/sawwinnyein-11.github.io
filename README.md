<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elegant Page</title>
    <video src="https://github.com/SawWinNyein/sawwinnyein-11.github.io/blob/main/sample-10s.mp4" width="300" height="300" controls></video>
    <style>
        /* Reset and base styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.6;
        }
        
        /* Header styles */
        header {
            background: linear-gradient(135deg, #6e8efb, #a777e3);
            color: white;
            text-align: center;
            padding: 4rem 2rem;
            margin-bottom: 2rem;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
            max-width: 600px;
            margin: 0 auto;
        }
        
        /* Container */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
        }
        
        /* Card styles */
        .card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 2rem;
            margin-bottom: 2rem;
            transition: transform 0.3s ease;
        }
        
        .card:hover {
            transform: translateY(-5px);
        }
        
        .card h2 {
            color: #444;
            margin-bottom: 1rem;
            font-size: 1.5rem;
        }
        
        /* Button styles */
        .btn {
            display: inline-block;
            background: #6e8efb;
            color: white;
            padding: 0.8rem 1.5rem;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
        }
        
        .btn:hover {
            background: #5a7bf0;
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        
        /* Footer styles */
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 2rem;
            margin-top: 3rem;
        }
        
        /* Responsive grid */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin: 2rem 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Beautiful Page</h1>
        <p class="subtitle">A simple, elegant design created with HTML and CSS that works on all devices.</p>
    </header>
    
    <div class="container">
        <div class="grid">
            <div class="card">
                <h2>Clean Design</h2>
                <p>This page features a minimalist design with plenty of white space, making it easy to read and navigate.</p>
                <a href="#" class="btn">Learn More</a>
            </div>
            
            <div class="card">
                <h2>Responsive Layout</h2>
                <p>The layout automatically adjusts to different screen sizes, from mobile phones to desktop computers.</p>
                <a href="#" class="btn">See Demo</a>
            </div>
            
            <div class="card">
                <h2>Modern Effects</h2>
                <p>Subtle hover effects and smooth transitions create an engaging user experience without being distracting.</p>
                <a href="#" class="btn">View Features</a>
            </div>
        </div>
        
        <div class="card">
            <h2>About This Design</h2>
            <p>This simple yet beautiful page was created using only HTML and CSS. It includes:</p>
            <ul style="margin: 1rem 0 1rem 2rem;">
                <li>A gradient header</li>
                <li>Responsive card grid</li>
                <li>Hover animations</li>
                <li>Clean typography</li>
                <li>Mobile-friendly layout</li>
            </ul>
            <p>You can easily customize the colors, fonts, and content to match your brand.</p>
            <a href="#" class="btn">Get Started</a>
        </div>
    </div>
    
    <footer>
        <p>&copy; 2023 Beautiful Page. All rights reserved.</p>
    </footer>
</body>
</html>
