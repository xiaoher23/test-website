<!DOCTYPE html>
<html>
    <head>
        <title>
            Landing page 
        </title>
        <link rel="stylesheet" href="landing.css" type="text/css">
        <style> 
            body {
                margin: 0;
                padding: 0;
                text-align: center;
                font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
                color: #f4f8fb;
            }
            header {
                padding: 50px 20px;
                background-image: url('stars.jpg');
                background-size: cover;
                background-position: center;
                color: white;
            }
            header h1 {
                font-size: 2.5rem;
                margin-bottom: 20px;
            }
            header p {
                font-size: 1.6rem;
                margin-bottom: 30px;
            }
            .action-button {
                background-color: aqua;
                cursor: pointer;
                padding: 10px 20px;
                color: blueviolet;
                border-radius: 5px;
                border: none;
                transition: background-color 0.3s;
            }
            .action-button:hover {
                background-color: blue;
            }
            .features {
                display: flex;
                padding: 20px;
                justify-content: center;
            }
            .feature {
                background-color: white;
                color: black;
                padding: 20px;
                margin: 10px;
                border-radius: 5px;
                box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
                transition: transform 0.3s ease, box-shadow 0.3s ease;
            }
            .feature:hover {
                transform: scale(1.05);
                box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
            }
            footer {
                background-color: #3843d8;
                color: white;
                text-align: center;
                padding: 10px 0;
            }

            @media (max-width: 600px) {
                .features {
                    flex-direction: column;
                }
            }
        </style>
    </head>
    <body>
        <header>
            <h1>Welcome to Our Service</h1>
            <p>Discover the future of online experience.</p>
            <button class="action-button">Learn More</button>
        </header>
        <section class="features">
            <div class="feature">
                <h2>Feature One</h2>
                <p>Description of Feature One</p>
            </div>
            <div class="feature">
                <h2>Feature Two</h2>
                <p>Description of Feature Two</p>
            </div>
        </section>  
        <footer>
            ©2024 Dynamic Landing Page. All rights reserved.
        </footer>
    </body>
</html>
