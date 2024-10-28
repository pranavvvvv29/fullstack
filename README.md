<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ruzzain's Resume</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            color: #333;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        h1 {
            text-align: center;
            color: #007acc;
            margin-bottom: 5px;
        }
        h2 {
            color: #007acc;
            margin-bottom: 8px;
        }
        .section {
            margin-bottom: 20px;
        }
        .section-title {
            font-size: 1.2em;
            color: #333;
            border-bottom: 2px solid #007acc;
            padding-bottom: 5px;
            margin-bottom: 15px;
        }
        .info, .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .info div, .skills div {
            flex: 1;
            min-width: 100px;
            color: #333;
        }
        .footer {
            text-align: center;
            font-size: 0.9em;
            color: #777;
            margin-top: 20px;
        }
        form {
            display: flex;
            flex-direction: column;
            gap: 10px;
            margin-top: 10px;
        }
        input, textarea {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 1em;
            color: #333;
        }
        input:focus, textarea:focus {
            border-color: #007acc;
            outline: none;
        }
        textarea {
            font-family: Arial, sans-serif; 
        }
        button {
            background-color: #007acc;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 4px;
            cursor: pointer;
            font-size: 1em;
        }
        button:hover {
            background-color: #005f99;
        }
        .profile-image {
            display: block;
            margin: 0 auto 20px;
            border-radius: 50%; 
            width: 150px; 
            height: 150px; 
            object-fit: cover; 
        }
    </style>
</head>
<body>
    <img src="https://github.com/Percy00765432/htmlres/blob/main/10533.jpg?raw=true" alt="My picture" class="profile-image">
    <div class="container">
        <h1>Ruzzain Jatti</h1>
        <p style="text-align:center; color: #555;">First-Year Engineering Student at RVU</p>
        
        <div class="section">
            <h2 class="section-title">About Me</h2>
            <p>I'm an enthusiastic first-year engineering student passionate about technology and coding. I love playing video games and am eager to learn programming languages and tools like C, HTML, Git, and GitHub to build my coding skills.</p>
        </div>
        
        <div class="section">
            <h2 class="section-title">Education</h2>
            <div class="info">
                <div><strong>University:</strong> RVU</div>
                <div><strong>Year:</strong> First Year</div>
            </div>
        </div>
        
        <div class="section">
            <h2 class="section-title">Skills</h2>
            <div class="skills">
                <div>🔹 C Language (Learning)</div>
                <div>🔹 HTML (Learning)</div>
                <div>🔹 Git & GitHub (Learning)</div>
                <div>🔹 Football</div>
            </div>
        </div>
        
        <div class="section">
            <h2 class="section-title">Contact Me</h2>
            <form action="mailto:ruzzainj999@gmail.com" method="POST" enctype="text/plain">
                <div>
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div>
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div>
                    <label for="message">Message:</label>
                    <textarea id="message" name="message" rows="4" required></textarea>
                </div>
                <button type="submit">Send Message</button>
            </form>
        </div>

        <div class="footer">
            <p>Connect with me on <a href="https://github.com/Percy00765432" target="_blank" style="color: #007acc; text-decoration: none;">GitHub</a>!</p>
        </div>
    </div>
</body>
</html>
