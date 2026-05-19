
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Приглашение на свадьбу | Юрий и Виктория</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
 <!-- Подключены шрифты: Great Vibes для имен и остальные для общего дизайна -->
    <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Montserrat:wght@100;200;300;400;500&display=swap" rel="stylesheet">
    <style>
        :root {
            --olive: #7d8463;
            --olive-light: #e6ebd9;
            --beige: #f6f3ed;
            --dark: #373a2f;
            --gold: #c5a059;
        }

        body {
            margin: 0;
            padding: 0;
            font-family: 'Montserrat', sans-serif;
            background-color: var(--beige);
            color: var(--dark);
            overflow-x: hidden;
            min-height: 100vh;
        }

        .serif {
            font-family: 'Playfair Display', serif;
        }

        /* Особый каллиграфический стиль для имен жениха и невесты */
        .calligraphy {
            font-family: 'Great Vibes', cursive;
            line-height: 0.85;
            padding-bottom: 12px;
        }

        /* Фоновый холст для лепестков */
        #petal-canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 1;
            pointer-events: none;
        }

        /* 3D Сцена Конверта */
        .envelope-stage {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 50;
            background: radial-gradient(circle, #fbfaf8 0%, #e2e6d6 100%);
            transition: opacity 1.5s cubic-bezier(0.25, 1, 0.5, 1), visibility 1.5s;
            perspective: 1000px;
        }

        .envelope-stage.opened {
            opacity: 0;
            visibility: hidden;
            pointer-events: none;
        }

        .envelope-wrapper {
            position: relative;
            width: 320px;
            height: 220px;
            cursor: pointer;
            transform-style: preserve-3d;
            transition: transform 0.5s ease;
        }

        .envelope-wrapper:hover {
            transform: scale(1.03);
        }

        /* Стороны конверта */
        .envelope-back {
            position: absolute;
            width: 100%;
            height: 100%;
            background: #cbd3b6;
            border-radius: 4px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.1);
        }

        .envelope-paper {
            position: absolute;
            width: 90%;
            height: 85%;
            background: white;
            left: 5%;
            top: 10%;
            border-radius: 4px;
            padding: 15px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            transition: transform 1.2s cubic-bezier(0.25, 1, 0.5, 1);
            z-index: 2;
        }

        .envelope-wrapper.open .envelope-paper {
            transform: translateY(-110px) scale(1.05);
        }

        .envelope-front-left {
            position: absolute;
            width: 0;
            height: 0;
            border-top: 110px solid transparent;
            border-bottom: 110px solid transparent;
            border-left: 160px solid #cbd3b6;
            z-index: 3;
            bottom: 0;
            left: 0;
        }

        .envelope-front-right {
            position: absolute;
            width: 0;
            height: 0;
            border-top: 110px solid transparent;
            border-bottom: 110px solid transparent;
            border-right: 160px solid #cbd3b6;
            z-index: 3;
            bottom: 0;
            right: 0;
        }

        .envelope-front-bottom {
            position: absolute;
            width: 0;
            height: 0;
            border-left: 160px solid transparent;
            border-right: 160px solid transparent;
            border-bottom: 110px solid #bdc7a5;
            z-index: 4;
            bottom: 0;
            left: 0;
        }

        .envelope-flap {
            position: absolute;
            width: 0;
            height: 0;
            border-left: 160px solid transparent;
            border-right: 160px solid transparent;
            border-top: 110px solid #aeb896;
            z-index: 5;
            top: 0;
            left: 0;
            transform-origin: top;
            transition: transform 0.6s ease;
        }

        .envelope-wrapper.open .envelope-flap {
            transform: rotateX(180deg);
            z-index: 1;
        }

        /* Сургучная печать */
        .wax-seal {
            position: absolute;
            width: 60px;
            height: 60px;
            background: radial-gradient(circle, #d9b46c 0%, #b89045 100%);
            border-radius: 50%;
            top: 80px;
            left: 130px;
            z-index: 10;
            box-shadow: 0 4px 10px rgba(0,0,0,0.15), inset 0 2px 4px rgba(255,255,255,0.3);
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Playfair Display', serif;
            color: white;
            font-weight: bold;
            font-size: 1.2rem;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.3);
            transition: all 0.5s ease;
        }

        .wax-seal::after {
            content: '';
            position: absolute;
            width: 50px;
            height: 50px;
            border: 1px dashed rgba(255,255,255,0.4);
            border-radius: 50%;
        }

        .envelope-wrapper.open .wax-seal {
            transform: scale(0);
            opacity: 0;
        }

        .pulse-ring {
            position: absolute;
            width: 80px;
            height: 80px;
            border: 2px solid var(--gold);
            border-radius: 50%;
            top: 70px;
            left: 120px;
            z-index: 9;
            animation: pulse 2s infinite;
            pointer-events: none;
        }

        @keyframes pulse {
            0% { transform: scale(0.8); opacity: 0.8; }
            100% { transform: scale(1.4); opacity: 0; }
        }

        /* Главная карточка */
        .glass-container {
            position: relative;
            z-index: 10;
            background: rgba(255, 255, 255, 0.45);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.6);
            box-shadow: 0 30px 60px rgba(74, 80, 61, 0.08);
            border-radius: 50px;
            transition: all 1s ease;
        }

        /* Кнопки управления вверху справа */
        .control-panel {
            position: fixed;
            top: 20px;
            right: 20px;
            display: flex;
            gap: 10px;
            z-index: 100;
        }

        .control-btn {
            width: 45px;
            height: 45px;
            background: white;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .music-btn.playing {
            animation: rotate 6s linear infinite;
        }

        @keyframes rotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }

        /* Секретная панель настроек */
        .settings-modal {
            position: fixed;
            top: 80px;
            right: 20px;
            background: white;
            border-radius: 20px;
            padding: 20px;
            width: 290px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            z-index: 99;
            border: 1px solid var(--olive-light);
            display: none;
        }

        .settings-modal.active {
            display: block;
        }

        /* Эффект мерцания кнопок */
        .shimmer-btn {
            position: relative;
            overflow: hidden;
            background: var(--dark);
            color: white;
            transition: all 0.3s;
        }

        .shimmer-btn::after {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(to right, transparent, rgba(255,255,255,0.2), transparent);
            transform: rotate(30deg);
            transition: 0.8s;
            opacity: 0;
        }

        .shimmer-btn:hover::after {
            opacity: 1;
            left: 120%;
        }

        .circle-date-badge {
            position: relative;
            width: 140px;
            height: 140px;
            border: 1px solid rgba(125, 132, 99, 0.3);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto;
        }

        .circle-date-badge::before {
            content: '';
            position: absolute;
            width: calc(100% - 10px);
            height: calc(100% - 10px);
            border: 1px dashed rgba(125, 132, 99, 0.2);
            border-radius: 50%;
        }

        .timer-unit {
            min-width: 60px;
        }
    </style>
</head>
<body class="p-4 md:p-8 flex items-center justify-center">

    <!-- Интерактивный листопад листьев на фоне -->
    <canvas id="petal-canvas"></canvas>

   

    <!-- Аудиоплеер -->
    <audio id="bg-audio" loop>
        <source id="audio-source" src="mot_namek_na_nas.mp3" type="audio/mpeg">
        <source src="https://videotourl.com/audio/1779183515989-55ead8c4-1eaa-4126-b368-a5cdbc73b41b.mp3" type="audio/mpeg">
    </audio>

    <!-- ЭКРАН 1: Интерактивный 3D-конверт -->
    <div class="envelope-stage" id="envelope-stage">
        <div class="text-center">
            <p class="serif italic text-[#7d8463] text-xl mb-12 tracking-wide animate-pulse">Вам отправлено послание</p>
            
            <div class="envelope-wrapper" id="envelope" onclick="openEnvelope()">
                <div class="envelope-back"></div>
                <div class="envelope-paper text-center flex flex-col justify-center items-center">
                    <span class="serif text-xs uppercase tracking-widest text-[#7d8463] mb-1">Приглашение</span>
                    <span class="serif text-lg font-light text-slate-700">Юрий & Виктория</span>
                </div>
                <div class="envelope-front-left"></div>
                <div class="envelope-front-right"></div>
                <div class="envelope-front-bottom"></div>
                <div class="envelope-flap"></div>
                <div class="wax-seal">Ю&В</div>
                <div class="pulse-ring"></div>
            </div>
            
            <p class="text-xs uppercase tracking-[0.3em] text-[#7d8463]/80 mt-12">Нажмите на печать, чтобы открыть</p>
        </div>
    </div>

    <!-- ЭКРАН 2: Главное свадебное приглашение -->
    <main class="w-full max-w-xl mx-auto my-auto relative z-10 py-8 opacity-0 transition-opacity duration-1000" id="main-content">
        <div class="glass-container py-16 px-6 md:px-12 text-center">
            
            <!-- Заголовок -->
            <p class="text-xs uppercase tracking-[0.4em] text-[#7d8463] mb-6 font-medium">Свадебное Приглашение</p>
            
            <!-- Роскошная каллиграфия для имен -->
            <h1 class="calligraphy text-7xl md:text-8xl text-slate-800">Юрий</h1>
            <p class="serif text-2xl font-light italic my-2 text-[#7d8463]">&</p>
            <h1 class="calligraphy text-7xl md:text-8xl text-slate-800">Виктория</h1>
            
            <div class="w-12 h-[1px] bg-[#7d8463]/40 mx-auto my-4"></div>

            <!-- Раздел получателя (Имя адресата) -->
            <div class="my-6 px-4">
                <span class="text-[9px] uppercase tracking-[0.3em] text-slate-400 block mb-2">Приглашаем Вас:</span>
                <p class="serif italic text-3xl md:text-4xl text-[#7d8463]" id="guest-display">Дорогие гости!</p>
            </div>

            <div class="w-12 h-[1px] bg-[#7d8463]/40 mx-auto my-4"></div>

            <!-- Ваша цитата -->
            <p class="serif italic text-lg md:text-xl text-[#4a503d] leading-relaxed max-w-md mx-auto mb-10">
                «Наша безграничная любовь дала повод собрать родных и близких вместе»
            </p>

            <!-- Круг Дата -->
            <div class="my-10">
                <div class="circle-date-badge">
                    <div class="text-center">
                        <span class="block text-[10px] uppercase tracking-widest text-[#7d8463] mb-1">Воскресенье</span>
                        <span class="block serif text-4xl text-slate-800">07 . 06</span>
                        <span class="block text-xs font-light text-slate-500 mt-1">2026 года</span>
                    </div>
                </div>
                <p class="text-sm uppercase tracking-wider text-slate-600 mt-4">Начало торжества в <span class="font-medium text-slate-800">17:00</span></p>
            </div>

            <!-- Интерактивный таймер обратного отсчета -->
            <div class="bg-white/50 border border-white/60 rounded-3xl p-6 max-w-sm mx-auto my-8 backdrop-blur-sm">
                <p class="text-[10px] uppercase tracking-[0.2em] text-[#7d8463] mb-4 font-semibold">До события осталось:</p>
                <div class="flex justify-around text-slate-800 font-light" id="countdown">
                    <div class="timer-unit">
                        <span class="serif text-3xl md:text-4xl block font-light" id="days">00</span>
                        <span class="text-[9px] uppercase tracking-wider text-slate-500">дней</span>
                    </div>
                    <div class="timer-unit">
                        <span class="serif text-3xl md:text-4xl block font-light" id="hours">00</span>
                        <span class="text-[9px] uppercase tracking-wider text-slate-500">часов</span>
                    </div>
                    <div class="timer-unit">
                        <span class="serif text-3xl md:text-4xl block font-light" id="minutes">00</span>
                        <span class="text-[9px] uppercase tracking-wider text-slate-500">минут</span>
                    </div>
                    <div class="timer-unit">
                        <span class="serif text-3xl md:text-4xl block font-light text-[#7d8463]" id="seconds">00</span>
                        <span class="text-[9px] uppercase tracking-wider text-[#7d8463]">секунд</span>
                    </div>
                </div>
            </div>

            <!-- Пожелание о подарках -->
            <div class="max-w-md mx-auto my-8 px-4">
                <div class="w-8 h-[1px] bg-[#7d8463]/30 mx-auto mb-4"></div>
                <p class="serif italic text-sm md:text-base text-[#4a503d]/90 leading-relaxed">
                    «Мы не хотим обременять вас выбором подарка. Если решите нас поздравить, будем рады любому символу внимания в конверте».
                </p>
                <div class="w-8 h-[1px] bg-[#7d8463]/30 mx-auto mt-4"></div>
            </div>

            <div class="w-12 h-[1px] bg-[#7d8463]/40 mx-auto my-6"></div>

            <!-- Место проведения -->
            <div class="my-8">
                <p class="text-xs uppercase tracking-[0.3em] text-[#7d8463] mb-4">Локация</p>
                <p class="serif text-3xl text-slate-800 mb-1">Пихтулино</p>
                <p class="text-sm font-light text-slate-600 mb-2 leading-relaxed">
                    ул. Садовая 131<br>
                    <span class="text-xs italic text-[#7d8463]">(напротив мкр. Новый город)</span>
                </p>
                
                <a href="https://yandex.ru/maps/?text=Пихтулино+Садовая+131" target="_blank" class="shimmer-btn inline-block px-10 py-4 rounded-full text-xs uppercase tracking-[0.2em] mt-6 shadow-lg">
                    Посмотреть на карте
                </a>
            </div>

            <!-- Подпись -->
            <div class="mt-16 pt-8 border-t border-slate-200/50">
                <p class="serif italic text-2xl text-[#7d8463] mb-2">Ждем вас!</p>
                <p class="text-[10px] uppercase tracking-[0.4em] text-slate-400">С любовью, Юрий и Виктория</p>
            </div>
            
        </div>
    </main>

    <script>
        // Инициализация Canvas лепестков/листьев
        const canvas = document.getElementById('petal-canvas');
        const ctx = canvas.getContext('2d');

        let width = canvas.width = window.innerWidth;
        let height = canvas.height = window.innerHeight;

        window.addEventListener('resize', () => {
            width = canvas.width = window.innerWidth;
            height = canvas.height = window.innerHeight;
        });

        class Petal {
            constructor() {
                this.x = Math.random() * width;
                this.y = Math.random() * height - height;
                this.r = Math.random() * 6 + 4;
                this.d = Math.random() * 1 + 0.5;
                this.swing = Math.random() * 2;
                this.swingSpeed = Math.random() * 0.02 + 0.005;
                this.opacity = Math.random() * 0.6 + 0.2;
                this.color = Math.random() > 0.4 ? 'rgba(125, 132, 99, ' : 'rgba(212, 175, 55, ';
                this.rotation = Math.random() * Math.PI;
                this.rotationSpeed = Math.random() * 0.02 - 0.01;
            }

            draw() {
                ctx.save();
                ctx.translate(this.x, this.y);
                ctx.rotate(this.rotation);
                ctx.beginPath();
                ctx.ellipse(0, 0, this.r, this.r * 1.8, 0, 0, Math.PI * 2);
                ctx.fillStyle = this.color + this.opacity + ')';
                ctx.fill();
                ctx.restore();
            }

            update() {
                this.y += this.d;
                this.x += Math.sin(this.swing);
                this.swing += this.swingSpeed;
                this.rotation += this.rotationSpeed;

                if (this.y > height) {
                    this.y = -20;
                    this.x = Math.random() * width;
                }
            }
        }

        const petals = Array.from({ length: 35 }, () => new Petal());

        function animate() {
            ctx.clearRect(0, 0, width, height);
            petals.forEach(p => {
                p.update();
                p.draw();
            });
            requestAnimationFrame(animate);
        }

        // Логика чтения и подстановки имени гостя из URL
        function parseGuestName() {
            const urlParams = new URLSearchParams(window.location.search);
            const guest = urlParams.get('to');
            const guestDisplay = document.getElementById('guest-display');
            const guestInput = document.getElementById('guest-input');

            if (guest) {
                const formattedName = decodeURIComponent(guest);
                guestDisplay.innerText = formattedName;
                guestInput.value = formattedName;
                updateUrlPreview(formattedName);
            } else {
                guestDisplay.innerText = "Дорогие гости!";
                guestInput.value = "Дорогие гости!";
                updateUrlPreview("Дорогие гости!");
            }
        }

        // Изменение имени гостя в панели настроек
        function updateGuestName(name) {
            const guestDisplay = document.getElementById('guest-display');
            guestDisplay.innerText = name || "Дорогие гости!";
            updateUrlPreview(name || "Дорогие гости!");
        }

        // Генерация превью персональной ссылки
        function updateUrlPreview(name) {
            const baseUrl = window.location.origin + window.location.pathname;
            const encoded = encodeURIComponent(name);
            const fullUrl = `${baseUrl}?to=${encoded}`;
            document.getElementById('guest-url-preview').innerText = `Ссылка: ${fullUrl}`;
            document.getElementById('guest-url-preview').title = fullUrl;
        }

        window.onload = function() {
            animate();
            parseGuestName();
            
            // Загрузка ранее сохраненного URL песни из локальной памяти браузера
            const savedUrl = localStorage.getItem('wedding-audio-url');
            if (savedUrl) {
                document.getElementById('audio-url').value = savedUrl;
                handleUrlSelect(savedUrl);
            }
        };

        // Открытие конверта
        function openEnvelope() {
            const envelope = document.getElementById('envelope');
            const stage = document.getElementById('envelope-stage');
            const mainContent = document.getElementById('main-content');
            const audio = document.getElementById('bg-audio');
            const musicBtn = document.getElementById('music-toggle');

            envelope.classList.add('open');
            
            audio.play().then(() => {
                musicBtn.classList.add('playing');
            }).catch((err) => {
                console.log('Требуется жест пользователя для включения аудио:', err);
            });

            setTimeout(() => {
                stage.classList.add('opened');
                mainContent.classList.remove('opacity-0');
                mainContent.classList.add('opacity-100');
            }, 1200);
        }

        // Логика аудио
        function toggleMusic() {
            const audio = document.getElementById('bg-audio');
            const btn = document.getElementById('music-toggle');
            if (audio.paused) {
                audio.play();
                btn.classList.add('playing');
            } else {
                audio.pause();
                btn.classList.remove('playing');
            }
        }

        // Панель настроек
        function toggleSettings() {
            const panel = document.getElementById('settings-panel');
            panel.classList.toggle('active');
        }

        // Настройка из локального файла
        function handleFileSelect(event) {
            const file = event.target.files[0];
            if (file) {
                const url = URL.createObjectURL(file);
                updateAudioSource(url);
            }
        }

        // Настройка по URL-ссылке
        function handleUrlSelect(url) {
            if (url.trim() !== "") {
                localStorage.setItem('wedding-audio-url', url);
                updateAudioSource(url);
            }
        }

        // Обновление источника в плеере
        function updateAudioSource(src) {
            const audio = document.getElementById('bg-audio');
            audio.src = src;
            audio.load();
            
            const stage = document.getElementById('envelope-stage');
            if (stage.classList.contains('opened')) {
                audio.play();
                document.getElementById('music-toggle').classList.add('playing');
            }
        }

        // Таймер обратного отсчета до 7 июня 2026 17:00
        const weddingDate = new Date("Jun 7, 2026 17:00:00").getTime();

        const timer = setInterval(() => {
            const now = new Date().getTime();
            const distance = weddingDate - now;

            const days = Math.floor(distance / (1000 * 60 * 60 * 24));
            const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((distance % (1000 * 60)) / 1000);

            document.getElementById("days").innerText = days.toString().padStart(2, '0');
            document.getElementById("hours").innerText = hours.toString().padStart(2, '0');
            document.getElementById("minutes").innerText = minutes.toString().padStart(2, '0');
            document.getElementById("seconds").innerText = seconds.toString().padStart(2, '0');

            if (distance < 0) {
                clearInterval(timer);
                document.getElementById("countdown").innerHTML = "<p class='serif text-xl text-center text-[#7d8463] w-full'>День свадьбы настал!</p>";
            }
        }, 1000);
    </script>
</body>
</html>


