<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Music Platform - README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f8f9fa;
            color: #333;
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }
        h1, h2 {
            color: #007bff;
        }
        .section {
            margin-bottom: 20px;
            padding: 15px;
            background: #ffffff;
            border-radius: 5px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .feature-list {
            list-style: none;
            padding: 0;
        }
        .feature-list li {
            margin: 5px 0;
        }
        .feature-list li::before {
            content: "✅";
            margin-right: 10px;
        }
        .code-block {
            background: #272822;
            color: #f8f8f2;
            padding: 10px;
            border-radius: 5px;
            font-family: monospace;
            white-space: pre-wrap;
        }
        .contact-info a {
            color: #007bff;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <h1>Project: Online Music Platform</h1>
    <p>A dynamic and user-friendly music streaming application</p>

    <div class="section">
        <h2>🛠 Key Features</h2>
        <ul class="feature-list">
            <li>Music Streaming – Play songs directly from the platform</li>
            <li>Playlist Creation – Users can create and manage their custom playlists</li>
            <li>User Authentication – Secure sign-in to access personalized content</li>
            <li>Seamless Navigation – Built with React Router for smooth page transitions</li>
            <li>Fast API Integration – Utilizes Firebase for real-time data handling</li>
            <li>Modern UI/UX – Styled with TailwindCSS for a sleek and responsive design</li>
        </ul>
    </div>

    <div class="section">
        <h2>💻 Tech Stack</h2>
        <ul>
            <li><strong>Front-End:</strong> React, Next.js, TailwindCSS, Firebase</li>
            <li><strong>State Management:</strong> Redux, useState, useEffect</li>
            <li><strong>API Handling:</strong> Firebase, Axios</li>
            <li><strong>Version Control:</strong> Git, GitHub</li>
        </ul>
    </div>

    <div class="section">
        <h2>📂 Installation & Setup</h2>
        <p><strong>Clone the repository and install dependencies:</strong></p>
        <div class="code-block">
            git clone https://github.com/tuanminhphan45/online-music-platform.git<br>
            cd online-music-platform<br>
            npm install
        </div>

        <p><strong>Start the development server:</strong></p>
        <div class="code-block">
            npm start
        </div>
    </div>

    <div class="section contact-info">
        <h2>📩 Let's Connect!</h2>
        <p>👤 <strong>Phan Nguyen Tuan Minh</strong></p>
        <p>📧 Email: <a href="mailto:tuanminhphan45@gmail.com">tuanminhphan45@gmail.com</a></p>
        <p>💻 GitHub: <a href="https://github.com/tuanminhphan45" target="_blank">github.com/tuanminhphan45</a></p>
        <p>📍 Location: Hanoi, Vietnam</p>
    </div>

</body>
</html>
