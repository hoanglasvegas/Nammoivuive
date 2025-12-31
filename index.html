<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For Ngân 💌</title>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@500&family=Quicksand:wght@300;500&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --bg-color: #fdf2f2;
            --envelope-color: #ffffff;
            --paper-color: #fffaf0;
            --accent-pink: #d4a5a5;
            --text-dark: #5a5a5a;
        }

        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: var(--bg-color);
            font-family: 'Quicksand', sans-serif;
            overflow: hidden;
        }

        /* Nền mờ ảo */
        .bokeh-bg {
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            background: radial-gradient(circle at 20% 30%, #ffdde1 0%, transparent 40%),
                        radial-gradient(circle at 80% 70%, #ee9ca7 0%, transparent 40%);
            filter: blur(60px);
            z-index: -1;
        }

        .container {
            position: relative;
            perspective: 1000px;
        }

        .envelope-wrapper {
            position: relative;
            width: 320px;
            height: 220px;
            background-color: var(--envelope-color);
            box-shadow: 0 10px 40px rgba(0,0,0,0.08);
            cursor: pointer;
            transition: transform 0.6s cubic-bezier(0.4, 0, 0.2, 1);
            border-radius: 2px;
        }

        .envelope-wrapper:hover {
            transform: translateY(-5px);
        }

        /* Nắp phong bì */
        .flap {
            position: absolute;
            top: 0; left: 0; width: 100%; height: 100%;
            background-color: #fff;
            clip-path: polygon(0 0, 50% 65%, 100% 0);
            z-index: 3;
            transition: transform 0.7s cubic-bezier(0.4, 0, 0.2, 1);
            transform-origin: top;
            box-shadow: inset 0 -2px 10px rgba(0,0,0,0.02);
            border-top: 1px solid #f0f0f0;
        }

        /* Thư bên trong */
        .letter {
            position: absolute;
            bottom: 5px;
            left: 5%;
            width: 90%;
            height: 90%;
            background: var(--paper-color);
            padding: 25px;
            box-sizing: border-box;
            z-index: 2;
            transition: transform 0.8s cubic-bezier(0.4, 0, 0.2, 1);
            box-shadow: 0 2px 15px rgba(0,0,0,0.05);
            border-radius: 2px;
            overflow: hidden;
        }

        .envelope-wrapper.open .flap {
            transform: rotateX(180deg);
            z-index: 1;
        }

        .envelope-wrapper.open .letter {
            transform: translateY(-160px) scale(1.05);
            height: 360px;
            z-index: 4;
        }

        /* Nội dung thư */
        .text {
            font-size: 15px;
            color: var(--text-dark);
            line-height: 1.8;
            opacity: 0;
            transition: opacity 1s ease 0.8s;
        }

        .envelope-wrapper.open .text {
            opacity: 1;
        }

        h2 {
            font-family: 'Dancing Script', cursive;
            font-size: 24px;
            margin-bottom: 15px;
            color: var(--accent-pink);
            text-align: center;
        }

        .signature {
            margin-top: 20px;
            text-align: right;
            font-family: 'Dancing Script', cursive;
            font-size: 20px;
            color: var(--accent-pink);
        }

        /* Dấu sáp niêm phong nhẹ nhàng */
        .stamp {
            position: absolute;
            top: 55%; left: 50%;
            transform: translate(-50%, -50%);
            width: 45px;
            height: 45px;
            background: var(--accent-pink);
            border-radius: 50%;
            z-index: 4;
            transition: opacity 0.4s ease;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-size: 18px;
            box-shadow: 0 4px 10px rgba(212, 165, 165, 0.4);
        }

        .envelope-wrapper.open .stamp {
            opacity: 0;
        }

        /* Cánh hoa rơi rải rác */
        .petal {
            position: fixed;
            background: #ffc0cb;
            border-radius: 150% 0 150% 0;
            opacity: 0.6;
            pointer-events: none;
            z-index: 10;
            animation: fall linear infinite;
        }

        @keyframes fall {
            0% { transform: translateY(-10vh) rotate(0deg); }
            100% { transform: translateY(110vh) rotate(360deg); }
        }
    </style>
</head>
<body>

    <div class="bokeh-bg"></div>

    <audio id="violinMusic" src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-15.mp3" loop></audio>

    <div class="container">
        <div class="envelope-wrapper" onclick="openMessage()">
            <div class="flap"></div>
            <div class="stamp">❤</div>
            <div class="letter">
                <div class="text">
                    <h2>Gửi Ngân</h2>
                    <p id="typed"></p>
                    <div class="signature">Hoàng.</div>
                </div>
            </div>
        </div>
    </div>

    <script>
        const content = "Năm mới này, anh không cầu mong gì hơn ngoài việc thấy em luôn mỉm cười và bình an. Cảm ơn em vì đã là một phần dịu dàng nhất trong cuộc sống của anh. Chúng mình sẽ cùng nhau đi thật xa, Ngân nhé...";
        let index = 0;
        let isStarted = false;

        function typeWriter() {
            if (index < content.length) {
                document.getElementById("typed").innerHTML += content.charAt(index);
                index++;
                setTimeout(typeWriter, 50);
            }
        }

        function openMessage() {
            const wrapper = document.querySelector('.envelope-wrapper');
            const music = document.getElementById('violinMusic');
            
            if (!isStarted) {
                wrapper.classList.add('open');
                music.volume = 0.5;
                music.play();
                
                setTimeout(typeWriter, 1200);
                startPetals();
                isStarted = true;
            }
        }

        function startPetals() {
            for(let i = 0; i < 25; i++) {
                setTimeout(createPetal, i * 200);
            }
        }

        function createPetal() {
            const petal = document.createElement('div');
            petal.className = 'petal';
            const size = Math.random() * 10 + 10 + 'px';
            petal.style.width = size;
            petal.style.height = size;
            petal.style.left = Math.random() * 100 + 'vw';
            petal.style.animationDuration = Math.random() * 3 + 4 + 's';
            document.body.appendChild(petal);
            
            setTimeout(() => petal.remove(), 7000);
        }
    </script>
</body>
</html>
