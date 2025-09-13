<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shadow - README</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(rgba(0, 0, 0, 0.85), rgba(0, 0, 0, 0.95)), 
                        url('https://images.unsplash.com/photo-1536240478700-b869070f9279?ixlib=rb-4.0.3&auto=format&fit=crop&w=1600&q=80');
            background-attachment: fixed;
            background-size: cover;
            color: #e0e0e0;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            background-color: rgba(10, 10, 15, 0.85);
            border-radius: 8px;
            box-shadow: 0 0 20px rgba(100, 65, 165, 0.4);
            margin-top: 30px;
            margin-bottom: 30px;
            border: 1px solid rgba(100, 65, 165, 0.3);
        }
        
        .header {
            text-align: center;
            padding: 30px 0;
            position: relative;
        }
        
        .gif-container {
            position: relative;
            margin: 0 auto;
            width: 600px;
            height: 338px;
            overflow: hidden;
            border-radius: 8px;
            box-shadow: 0 0 15px rgba(100, 65, 165, 0.6);
        }
        
        .typing-text {
            margin: 30px 0;
            position: relative;
        }
        
        .arise-text {
            text-align: center;
            font-size: 32px;
            font-weight: bold;
            color: #8a2be2;
            text-shadow: 0 0 10px rgba(138, 43, 226, 0.7);
            margin: 20px 0;
            letter-spacing: 5px;
            animation: glow 2s infinite alternate;
        }
        
        @keyframes glow {
            from {
                text-shadow: 0 0 5px rgba(138, 43, 226, 0.7);
            }
            to {
                text-shadow: 0 0 20px rgba(138, 43, 226, 0.9), 0 0 30px rgba(138, 43, 226, 0.6);
            }
        }
        
        h1, h2, h3 {
            color: #a78bfa;
        }
        
        h2 {
            border-bottom: 1px solid rgba(100, 65, 165, 0.5);
            padding-bottom: 10px;
        }
        
        a {
            color: #a78bfa;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        a:hover {
            color: #7c3aed;
            text-shadow: 0 0 5px rgba(124, 58, 237, 0.7);
        }
        
        .badges {
            display: flex;
            justify-content: center;
            gap: 10px;
            flex-wrap: wrap;
            margin: 20px 0;
        }
        
        .stats-container {
            display: flex;
            flex-direction: column;
            gap: 20px;
            margin: 30px 0;
        }
        
        .stats-img {
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(100, 65, 165, 0.4);
            transition: transform 0.3s;
        }
        
        .stats-img:hover {
            transform: scale(1.02);
        }
        
        .footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            font-size: 14px;
            color: #888;
        }
        
        /* Responsive design */
        @media (max-width: 768px) {
            .gif-container {
                width: 100%;
                height: auto;
            }
            
            .container {
                margin: 10px;
                padding: 15px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="gif-container">
                <img src="https://media1.tenor.com/m/YmcBY9nlAwsAAAAd/cid-kagenou-eminence-in-shadow.gif" width="600" alt="Shadow" style="width: 100%; height: auto;">
            </div>
            
            <div class="typing-text">
                <img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=900&size=44&pause=1000&center=true&vCenter=true&width=800&lines=Shadow" alt="Shadow Typing SVG" style="max-width: 100%; height: auto;">
                <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMTJxNjhnMHo3ejQyYmR4ZzIwdjJveWt5ZTBzOHBxY3Fzc2ZyczRwbyZlcD12MV9naWZzX3NlYXJjaCZjdD1n/RL1Jl8PnNDqz9hy83b/giphy.gif" width="50" height="50" alt="Hacker Emoji" style="vertical-align: middle;">
            </div>
            
            <div class="arise-text">ARISE</div>
        </div>

        <h2>About Me</h2>
        <p>I'm <strong>Shadow</strong>, a programmer and open-source developer with expertise in Go (Golang) and Python.
        I build automation tools, Discord/Telegram bots, and custom applications that push the limits of efficiency and creativity.
        My work often focuses on combining software development, problem-solving, and system design to create tools that are both practical and powerful.</p>

        <p>My Instagram account : <a href="https://www.instagram.com/shdw" target="_blank">@shdw</a></p>
        <p>My channel : <a href="https://t.me/shdwhim" target="_blank">@shdwhim</a></p>
        <p>My telegram : <a href="https://t.me/ytsof" target="_blank">@ytsof</a></p>

        <h2>Connect with Me</h2>
        <div class="badges">
            <a href="https://instagram.com/shdw" target="_blank"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
            <a href="https://t.me/ytsof" target="_blank"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
            <a href="https://t.me/shdwhim" target="_blank"><img src="https://img.shields.io/badge/Telegram%20Channel-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Channel"></a>
        </div>

        <div class="stats-container">
            <h2>GitHub Stats</h2>
            <img class="stats-img" src="https://github-readme-stats.vercel.app/api?username=9rfm&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats">

            <h2>Most Used Languages</h2>
            <img class="stats-img" src="https://github-readme-stats.vercel.app/api/top-langs/?username=9rfm&layout=compact&theme=tokyonight&hide_border=true" alt="Most Used Languages">

            <h2>Streak Stats</h2>
            <img class="stats-img" src="https://streak-stats.demolab.com?user=9rfm&theme=tokyonight&hide_border=true" alt="GitHub Streak">

            <h2>GitHub Trophies</h2>
            <img class="stats-img" src="https://github-profile-trophy.vercel.app/?username=9rfm&theme=tokyonight&no-frame=true&no-bg=true&margin-w=10&margin-h=10&v=1" alt="GitHub Trophies">
        </div>

        <div class="footer">
            <img src="https://komarev.com/ghpvc/?username=9rfm&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views">
        </div>
    </div>
</body>
</html>
