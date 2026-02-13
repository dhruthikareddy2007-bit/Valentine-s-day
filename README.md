<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valentine's Day for Amit</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #ff3366 0%, #ff6b9d 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        
        .container {
            background: white;
            border-radius: 20px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.3);
            max-width: 600px;
            padding: 40px;
            animation: fadeIn 1s ease-in;
        }
        
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        h1 {
            color: #ff3366;
            font-size: 2.5em;
            margin-bottom: 10px;
            animation: heartbeat 1.5s ease-in-out infinite;
        }
        
        @keyframes heartbeat {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.1);
            }
        }
        
        .subtitle {
            color: #ff6b9d;
            font-size: 1.2em;
            margin-bottom: 30px;
        }
        
        .message {
            background: linear-gradient(135deg, #ffe0e6 0%, #fff0f5 100%);
            padding: 20px;
            margin: 20px 0;
            border-left: 5px solid #ff3366;
            border-radius: 10px;
            text-align: left;
            font-size: 1.1em;
            line-height: 1.6;
            color: #333;
            animation: slideIn 0.8s ease-out;
        }
        
        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateX(-20px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }
        
        .heart {
            color: #ff3366;
            font-size: 1.5em;
            margin: 0 10px;
        }
        
        .footer {
            margin-top: 40px;
            color: #999;
            font-size: 0.9em;
        }
        
        .emoji {
            font-size: 3em;
            margin: 20px 0;
            animation: float 3s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% {
                transform: translateY(0px);
            }
            50% {
                transform: translateY(-20px);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1><span class="heart">💕</span> Happy Valentine's Day <span class="heart">💕</span></h1>
        <p class="subtitle">For the one and only - Amit</p>
        
        <div class="emoji">💝</div>
        
        <div class="message">
            <strong>Message 1:</strong> Amit, you are the most wonderful person in my life.Every moment with you is a gift that I cherish forever. Happy Valentine's Day! <span class="heart">❤️</span>
        </div>
        
        <div class="message">
            <strong>Message 2:</strong> Your smile brightens my darkest days, and your love gives me strength. You are my reason to believe in true love. <span class="heart">❤️</span>
        </div>
        
        <div class="message">
            <strong>Message 3:</strong> In your eyes, I found my home. In your arms, I found my peace. In your heart, I found my love. Forever grateful to have you, Amit. <span class="heart">❤️</span>
        </div>
        
        <div class="message">
            <strong>Message 4:</strong> You are not just my love, but my best friend, my soulmate, and my everything. Here's to the love we share, today and always. <span class="heart">❤️</span>
        </div>
        
        <div class="emoji">🌹</div>
        
        <div class="footer">
            <p>Made with love by dhruthikareddy2007-bit 💕</p>
            <p>Happy Valentine's Day!</p>
        </div>
    </div>
</body>
</html>