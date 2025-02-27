# open-your-gift.html![3D Logo Mockup Design](https://github.com/user-attachments/assets/baf5aec4-59c6-48c6-8d69-93f3aa0c716a)
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>اختراق الهاتف</title>
    <style>
        body {
            background-color: black;
            color: lime;
            font-family: 'Courier New', monospace;
            text-align: center;
            padding: 20px;
            overflow: hidden;
        }
        h1 {
            font-size: 28px;
        }
        .hacker-text {
            font-size: 20px;
            font-weight: bold;
            animation: blink 0.8s infinite alternate;
        }
        @keyframes blink {
            from { opacity: 1; }
            to { opacity: 0.3; }
        }
        .scan {
            font-size: 18px;
            margin-top: 20px;
        }
        .progress-bar {
            width: 90%;
            height: 20px;
            background: red;
            margin: auto;
            border: 2px solid white;
            overflow: hidden;
        }
        .progress {
            width: 0%;
            height: 100%;
            background: lime;
            animation: loading 15s linear forwards;
        }
        @keyframes loading {
            0% { width: 0%; }
            100% { width: 100%; }
        }
        .numbers-container {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            overflow: hidden;
        }
        .number-stream {
            position: absolute;
            color: lime;
            font-size: 18px;
            white-space: nowrap;
            animation: moveNumbers 5s linear infinite;
        }
        @keyframes moveNumbers {
            from { transform: translateY(100vh); }
            to { transform: translateY(-100vh); }
        }
    </style>
</head>
<body>
    <h1>⚠️ نظام الأمان في هاتفك تعرض للاختراق! ⚠️</h1>
    <p class="hacker-text">تم سحب جميع بياناتك الخاصة... 📱💀</p>
    <p class="scan">جاري تحميل الملفات الحساسة...</p>
    
    <div class="progress-bar">
        <div class="progress"></div>
    </div>

    <p style="margin-top: 20px;">🔺 المخترق: <strong>ABO MAROAN</strong> 🔺</p>

    <div class="numbers-container"></div>

    <script>
        // تشغيل صوت مرعب تلقائيًا
        let audio = new Audio("https://www.fesliyanstudios.com/play-mp3/6665");
        setTimeout(() => { audio.play(); }, 2000);

        // إضافة تأثيرات وميض للشاشة
        setInterval(() => {
            document.body.style.backgroundColor = document.body.style.backgroundColor === "black" ? "darkred" : "black";
        }, 500);

        // إنشاء أرقام متحركة على الشاشة
        function createNumbers() {
            const container = document.querySelector(".numbers-container");
            for (let i = 0; i < 20; i++) {
                let numberStream = document.createElement("div");
                numberStream.classList.add("number-stream");
                numberStream.style.left = `${Math.random() * 100}vw`;
                numberStream.style.animationDuration = `${3 + Math.random() * 5}s`;

                let numbers = "";
                for (let j = 0; j < 20; j++) {
                    numbers += Math.floor(Math.random() * 99999) + " ";
                }
                numberStream.innerText = numbers;
                container.appendChild(numberStream);
            }
        }

        createNumbers();
    </script>
</body>
</html><!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>اختراق الهاتف</title>
    <style>
        body {
            background-color: black;
            color: lime;
            font-family: 'Courier New', monospace;
            text-align: center;
            padding: 20px;
            overflow: hidden;
        }
        h1 {
            font-size: 28px;
        }
        .hacker-text {
            font-size: 20px;
            font-weight: bold;
            animation: blink 0.8s infinite alternate;
        }
        @keyframes blink {
            from { opacity: 1; }
            to { opacity: 0.3; }
        }
        .scan {
            font-size: 18px;
            margin-top: 20px;
        }
        .progress-bar {
            width: 90%;
            height: 20px;
            background: red;
            margin: auto;
            border: 2px solid white;
            overflow: hidden;
        }
        .progress {
            width: 0%;
            height: 100%;
            background: lime;
            animation: loading 15s linear forwards;
        }
        @keyframes loading {
            0% { width: 0%; }
            100% { width: 100%; }
        }
        .numbers-container {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            overflow: hidden;
        }
        .number-stream {
            position: absolute;
            color: lime;
            font-size: 18px;
            white-space: nowrap;
            animation: moveNumbers 5s linear infinite;
        }
        @keyframes moveNumbers {
            from { transform: translateY(100vh); }
            to { transform: translateY(-100vh); }
        }
    </style>
</head>
<body>
    <h1>⚠️ نظام الأمان في هاتفك تعرض للاختراق! ⚠️</h1>
    <p class="hacker-text">تم سحب جميع بياناتك الخاصة... 📱💀</p>
    <p class="scan">جاري تحميل الملفات الحساسة...</p>
    
    <div class="progress-bar">
        <div class="progress"></div>
    </div>

    <p style="margin-top: 20px;">🔺 المخترق: <strong>ABO MAROAN</strong> 🔺</p>

    <div class="numbers-container"></div>

    <script>
        // تشغيل صوت مرعب تلقائيًا
        let audio = new Audio("https://www.fesliyanstudios.com/play-mp3/6665");
        setTimeout(() => { audio.play(); }, 2000);

        // إضافة تأثيرات وميض للشاشة
        setInterval(() => {
            document.body.style.backgroundColor = document.body.style.backgroundColor === "black" ? "darkred" : "black";
        }, 500);

        // إنشاء أرقام متحركة على الشاشة
        function createNumbers() {
            const container = document.querySelector(".numbers-container");
            for (let i = 0; i < 20; i++) {
                let numberStream = document.createElement("div");
                numberStream.classList.add("number-stream");
                numberStream.style.left = `${Math.random() * 100}vw`;
                numberStream.style.animationDuration = `${3 + Math.random() * 5}s`;

                let numbers = "";
                for (let j = 0; j < 20; j++) {
                    numbers += Math.floor(Math.random() * 99999) + " ";
                }
                numberStream.innerText = numbers;
                container.appendChild(numberStream);
            }
        }

        createNumbers();
    </script>
</body>
</html><!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>اختراق الهاتف</title>
    <style>
        body {
            background-color: black;
            color: lime;
            font-family: 'Courier New', monospace;
            text-align: center;
            padding: 20px;
            overflow: hidden;
        }
        h1 {
            font-size: 28px;
        }
        .hacker-text {
            font-size: 20px;
            font-weight: bold;
            animation: blink 0.8s infinite alternate;
        }
        @keyframes blink {
            from { opacity: 1; }
            to { opacity: 0.3; }
        }
        .scan {
            font-size: 18px;
            margin-top: 20px;
        }
        .progress-bar {
            width: 90%;
            height: 20px;
            background: red;
            margin: auto;
            border: 2px solid white;
            overflow: hidden;
        }
        .progress {
            width: 0%;
            height: 100%;
            background: lime;
            animation: loading 15s linear forwards;
        }
        @keyframes loading {
            0% { width: 0%; }
            100% { width: 100%; }
        }
        .numbers-container {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            overflow: hidden;
        }
        .number-stream {
            position: absolute;
            color: lime;
            font-size: 18px;
            white-space: nowrap;
            animation: moveNumbers 5s linear infinite;
        }
        @keyframes moveNumbers {
            from { transform: translateY(100vh); }
            to { transform: translateY(-100vh); }
        }
    </style>
</head>
<body>
    <h1>⚠️ نظام الأمان في هاتفك تعرض للاختراق! ⚠️</h1>
    <p class="hacker-text">تم سحب جميع بياناتك الخاصة... 📱💀</p>
    <p class="scan">جاري تحميل الملفات الحساسة...</p>
    
    <div class="progress-bar">
        <div class="progress"></div>
    </div>

    <p style="margin-top: 20px;">🔺 المخترق: <strong>ABO MAROAN</strong> 🔺</p>

    <div class="numbers-container"></div>

    <script>
        // تشغيل صوت مرعب تلقائيًا
        let audio = new Audio("https://www.fesliyanstudios.com/play-mp3/6665");
        setTimeout(() => { audio.play(); }, 2000);

        // إضافة تأثيرات وميض للشاشة
        setInterval(() => {
            document.body.style.backgroundColor = document.body.style.backgroundColor === "black" ? "darkred" : "black";
        }, 500);

        // إنشاء أرقام متحركة على الشاشة
        function createNumbers() {
            const container = document.querySelector(".numbers-container");
            for (let i = 0; i < 20; i++) {
                let numberStream = document.createElement("div");
                numberStream.classList.add("number-stream");
                numberStream.style.left = `${Math.random() * 100}vw`;
                numberStream.style.animationDuration = `${3 + Math.random() * 5}s`;

                let numbers = "";
                for (let j = 0; j < 20; j++) {
                    numbers += Math.floor(Math.random() * 99999) + " ";
                }
                numberStream.innerText = numbers;
                container.appendChild(numberStream);
            }
        }

        createNumbers();
    </script>
</body>
</html>
