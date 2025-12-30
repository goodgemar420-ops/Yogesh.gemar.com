<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Aditya Bhai!</title>
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.5.1/dist/confetti.browser.min.js"></script>
    <style>
        body {
            margin: 0;
            background: black;
            color: #ff69b4;
            font-family: 'Courier New', Courier, monospace;
            /* Scroll allow karega agar content bada ho jaye */
            overflow-x: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        #matrix { 
            position: fixed; 
            top: 0; 
            left: 0; 
            z-index: -1; 
        }

        #start-btn {
            padding: 20px 40px; 
            font-size: 24px; 
            background: #ff69b4; 
            color: black;
            border: none; 
            border-radius: 50px; 
            cursor: pointer; 
            font-weight: bold;
            box-shadow: 0 0 25px #ff69b4; 
            z-index: 10;
        }

        #display-text { 
            display: none; 
            font-size: 80px; /* Bada font size */
            font-weight: bold; 
            text-align: center; 
            text-shadow: 0 0 25px #ff69b4; 
        }

        #message { 
            display: none; 
            text-align: center; 
            padding: 40px 20px;
            animation: fadeIn 1.5s ease-in;
        }

        .main-photo { 
            width: 250px; /* Photo ka size bada kar diya */
            height: 250px; 
            border-radius: 50%; 
            border: 6px solid #ff69b4; 
            object-fit: cover; 
            box-shadow: 0 0 30px #ff69b4; 
            margin-bottom: 25px; 
        }

        h1 { 
            font-size: 60px; /* Bada heading */
            margin: 10px 0; 
            text-shadow: 0 0 20px #ff69b4; 
            letter-spacing: 2px;
        }

        h2 { 
            font-size: 40px; 
            margin: 5px 0; 
            color: white;
        }

        p {
            font-size: 22px;
            margin-top: 15px;
            font-weight: bold;
        }

        /* Mobile ke liye thoda adjust */
        @media (max-width: 600px) {
            #display-text { font-size: 50px; }
            h1 { font-size: 40px; }
            h2 { font-size: 30px; }
            .main-photo { width: 200px; height: 200px; }
        }

        @keyframes fadeIn { from {opacity: 0; transform: translateY(20px);} to {opacity: 1; transform: translateY(0);} }
    </style>
</head>
<body>

    <canvas id="matrix"></canvas>
    <button id="start-btn" onclick="initiate()">Bhai Ke Liye Surprise 🎁</button>
    <div id="display-text"></div>

    <div id="message">
        <img src="https://i.ibb.co/LDGWyXpw/1507288482f1020c18a53adfd690bcd9.jpg" class="main-photo" alt="Aditya">
        <h1>HAPPY BIRTHDAY</h1>
        <h2>ADITYA BHAI</h2>
        <p>✨ Aap jiyo hazaaron saal! ✨</p>
    </div>

    <audio id="bday-song" loop>
        <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
    </audio>

    <script>
        const canvas = document.getElementById('matrix');
        const ctx = canvas.getContext('2d');

        function resize() {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        }
        window.onresize = resize;
        resize();

        const letters = "HAPPY Birthday";
        const fontSize = 15;
        const columns = canvas.width / fontSize;
        const drops = Array(Math.floor(columns)).fill(1);

        function drawMatrix() {
            ctx.fillStyle = "rgba(0, 0, 0, 0.1)";
            ctx.fillRect(0, 0, canvas.width, canvas.height);
            ctx.fillStyle = "#ff69b4";
            ctx.font = fontSize + "px arial";
            drops.forEach((y, i) => {
                const text = letters[Math.floor(Math.random() * letters.length)];
                ctx.fillText(text, i * fontSize, y * fontSize);
                if (y * fontSize > canvas.height && Math.random() > 0.975) drops[i] = 0;
                drops[i]++;
            });
        }
        setInterval(drawMatrix, 35);

        const sequence = ["3", "2", "1", "HAPPY", "BIRTHDAY","To","You", "ADITYA", "BHAI!", "❤️"];
        let step = 0;

        function initiate() {
            document.getElementById('start-btn').style.display = 'none';
            const displayEl = document.getElementById('display-text');
            displayEl.style.display = 'block';
            document.getElementById('bday-song').play();
            
            const timer = setInterval(() => {
                if (step < sequence.length) {
                    displayEl.innerText = sequence[step];
                    step++;
                } else {
                    clearInterval(timer);
                    displayEl.style.display = 'none';
                    document.getElementById('message').style.display = 'block';
                    
                    // Extra Blast Effect
                    var duration = 5 * 1000;
                    var animationEnd = Date.now() + duration;
                    var defaults = { startVelocity: 30, spread: 360, ticks: 60, zIndex: 0 };

                    function randomInRange(min, max) { return Math.random() * (max - min) + min; }

                    var interval = setInterval(function() {
                        var timeLeft = animationEnd - Date.now();
                        if (timeLeft <= 0) return clearInterval(interval);
                        var particleCount = 50 * (timeLeft / duration);
                        confetti(Object.assign({}, defaults, { particleCount, origin: { x: randomInRange(0.1, 0.3), y: Math.random() - 0.2 } }));
                        confetti(Object.assign({}, defaults, { particleCount, origin: { x: randomInRange(0.7, 0.9), y: Math.random() - 0.2 } }));
                    }, 250);
                }
            }, 1000);
        }
    </script>
</body>
</html>
