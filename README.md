<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Charles Jordan Condez - Portfolio</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: #f4f4f4;
            font-family: 'Arial', sans-serif;
            color: #333;
            padding-top: 120px; /* Space for fixed header and nav */
            padding-bottom: 50px; /* Space for fixed footer */
        }

        header {
            background: #222;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000; /* Ensures header stays above other content */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        nav {
            background: #444;
            position: fixed;
            width: 100%;
            top: 80px; /* Adjusted to sit below the header */
            left: 0;
            z-index: 1000; /* Ensures nav stays above other content */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }

        nav li {
            margin: 0 15px;
        }

        nav a {
            text-decoration: none;
            color: #fff;
            font-weight: bold;
            padding: 10px 15px;
            display: block;
            transition: background 0.3s;
        }

        nav a:hover {
            background: #666;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .intro {
            text-align: center;
            padding: 50px 0;
        }

        .intro h1 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .intro p {
            font-size: 1.2em;
            margin-bottom: 40px;
        }

        .section-title {
            text-align: center;
            margin: 50px 0 30px;
            font-size: 2em;
        }

        .video-section, .design-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .video-section iframe, .design-section img {
            max-width: 100%;
            height: auto;
            border: 2px solid #ddd;
            border-radius: 5px;
            transition: transform 0.3s;
        }

        .video-section iframe:hover, .design-section img:hover {
            transform: scale(1.05);
        }

        footer {
            background: #222;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            z-index: 1000; /* Ensures footer stays above other content */
        }

        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
            }

            .intro h1 {
                font-size: 2em;
            }

            .intro p {
                font-size: 1em;
            }
        }
    </style>
</head>

<body>
    <header>
        
        <h1>Charles Jordan Condez - Social Media Manager & Customer Support</h1>
    </header>
    
    <nav>
        <ul>
            <li><a href="./homepage.html">Home</a></li>
            <li><a href="./About.html">About</a></li>
            <li><a href="./Certificates.html">Certificates</a></li>
            <li><a href="./Services.html">Services</a></li>
            <li><a href="./Contact.html">Contact</a></li>
        </ul>
    </nav>
    
    <div class="container">
        <div class="intro">
            <h1>Welcome to My Portfolio</h1>
            <p>Discover my journey and experience in social media management and customer support.</p>
        </div>
        
        <div class="section-title">Sample Videos</div>
        <div class="video-section">
            <iframe src="https://www.youtube.com/embed/4Qqttx5ZtCc?si=bxYveW-Yfhru9WBx" title="YouTube video player" allowfullscreen></iframe>
            <iframe src="https://www.youtube.com/embed/9ihiIpGxaOs?si=4V3ISbOH0jgygVJH" title="YouTube video player" allowfullscreen></iframe>
            <iframe src="https://www.youtube.com/embed/GuuvLnUkvWQ?si=GpWeH3qdp56hy8sX" title="YouTube video player" allowfullscreen></iframe>
            <iframe src="https://www.youtube.com/embed/ie-Wzhce1pQ?si=9a13acr_Vhr-IL65" title="YouTube video player" allowfullscreen></iframe>
            <iframe src="https://www.youtube.com/embed/Crf7VeKdVqc?si=nfd0T3SzMMMlg27s" title="YouTube video player" allowfullscreen></iframe>
            <iframe src="https://www.youtube.com/embed/PYEKONfsCEs?si=X0vmPz4SmQNYcAyZ" title="YouTube video player" allowfullscreen></iframe>
        </div>
        
        <div class="section-title">Graphic Designs</div>
        <div class="design-section">
            <img src="path_to_design1.jpg" alt="Graphic Design 1">
            <img src="path_to_design2.jpg" alt="Graphic Design 2">
            <img src="path_to_design3.jpg" alt="Graphic Design 3">
            <img src="path_to_design4.jpg" alt="Graphic Design 4">
            <img src="path_to_design5.jpg" alt="Graphic Design 5">
            <img src="path_to_design6.jpg" alt="Graphic Design 6">
        </div>
    </div>
    
    <footer>
        &copy; 2024 Charles Jordan Condez. All Rights Reserved.
    </footer>
</body>

</html>
