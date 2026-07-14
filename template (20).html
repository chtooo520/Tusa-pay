<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Туса Пэй | Premium Edition</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- QR Code Generator -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>
    <!-- QR Code Scanner -->
    <script src="https://unpkg.com/html5-qrcode"></script>

    <!-- Firebase SDK Compat -->
    <script src="https://www.gstatic.com/firebasejs/10.8.0/firebase-app-compat.js"></script>
    <script src="https://www.gstatic.com/firebasejs/10.8.0/firebase-firestore-compat.js"></script>

    <style>
        body {
            font-family: 'Inter', sans-serif;
            background: radial-gradient(circle at 50% 50%, #121214 0%, #050506 100%);
            color: #ffffff;
            min-height: 100vh;
            -webkit-tap-highlight-color: transparent;
        }

        /* Эффект матового стекла (Glassmorphism) */
        .glass-panel {
            background: rgba(28, 28, 30, 0.7);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.08);
            border-radius: 1.5rem;
        }

        .action-btn {
            background: rgba(28, 28, 30, 0.6);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.05);
            transition: all 0.2s ease;
        }
        .action-btn:active {
            background: rgba(255, 255, 255, 0.1);
            transform: scale(0.95);
        }

        /* 10 кастомных дизайнов карт */
        .design-1 { background: radial-gradient(circle at 80% 20%, #bbf7d0 0%, #22c55e 100%); color: #062f16; } 
        .design-2 { background: radial-gradient(circle at 80% 20%, #f3e8ff 0%, #7e22ce 100%); color: #2e1065; } 
        .design-3 { background: radial-gradient(circle at 80% 20%, #ffe4e6 0%, #be123c 100%); color: #4c0519; } 
        .design-4 { background: radial-gradient(circle at 80% 20%, #fef08a 0%, #ca8a04 100%); color: #422006; } 
        .design-5 { background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%); color: #f1f5f9; background-image: radial-gradient(rgba(255,255,255,0.15) 1.5px, transparent 1.5px); background-size: 16px 16px; } 
        .design-6 { background: linear-gradient(135deg, #1e1b4b 0%, #311042 100%); color: #f5f3ff; background-image: repeating-linear-gradient(45deg, rgba(255,255,255,0.03) 0px, rgba(255,255,255,0.03) 2px, transparent 2px, transparent 12px); } 
        .design-7 { background: radial-gradient(circle at 50% 50%, #06b6d4 0%, #155e75 100%); color: #ecfeff; } 
        .design-8 { background: linear-gradient(135deg, #ec4899 0%, #e11d48 100%); color: #fff1f2; background-image: linear-gradient(to right, rgba(255,255,255,0.1) 1px, transparent 1px), linear-gradient(to bottom, rgba(255,255,255,0.1) 1px, transparent 1px); background-size: 20px 20px; } 
        .design-9 { background: linear-gradient(135deg, #111827 0%, #030712 100%); color: #9ca3af; border: 1px solid rgba(255, 255, 255, 0.1); } 
        .design-10 { background: radial-gradient(circle at 10% 20%, #f97316 0%, #ea580c 100%); color: #fff7ed; } 

        /* Анимация пульсации для Копилки */
        @keyframes pulse-soft {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.7; }
        }
        .pulse-text {
            animation: pulse-soft 2s infinite;
        }

        /* Анимация бегущей строки */
        @keyframes marquee {
            0% { transform: translate3d(100%, 0, 0); }
            100% { transform: translate3d(-100%, 0, 0); }
        }
        .marquee-wrapper {
            display: flex;
            width: 100%;
            overflow: hidden;
        }
        .marquee-content {
            white-space: nowrap;
            padding-left: 10px;
            display: inline-block;
            animation: marquee 14s linear infinite;
        }

        /* Кастомный скроллбар */
        ::-webkit-scrollbar {
            width: 4px;
        }
        ::-webkit-scrollbar-track {
            background: transparent;
        }
        ::-webkit-scrollbar-thumb {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
        }

        @media print {
            body { background: #ffffff !important; color: #000000 !important; }
            body * { visibility: hidden; }
            #print-zone, #print-zone * { visibility: visible; }
            #print-zone { position: absolute; left: 0; top: 0; width: 100%; display: flex !important; flex-wrap: wrap !important; gap: 20px !important; justify-content: center !important; }
            .print-card { page-break-inside: avoid !important; -webkit-print-color-adjust: exact !important; print-color-adjust: exact !important; border: 2px solid #000000 !important; }
        }
    </style>
</head>
<body class="flex justify-center items-start md:py-8">

    <!-- Главный контейнер телефона -->
    <div class="w-full max-w-md min-h-screen md:min-h-[850px] md:rounded-[40px] md:border-8 md:border-neutral-800 bg-[#0b0b0d] relative overflow-hidden flex flex-col shadow-2xl">
        
        <!-- ================= БЕГУЩАЯ СТРОКА СВЕРХУ ВСЕГО ================= -->
        <div id="ticker-banner" class="w-full bg-gradient-to-r from-indigo-600 via-purple-600 to-indigo-600 text-white py-2 text-[11px] font-bold tracking-wide shadow-md border-b border-white/10 z-20 hidden">
            <div class="marquee-wrapper">
                <div id="ticker-text" class="marquee-content">Загрузка важного объявления... 🔥</div>
            </div>
        </div>

        <!-- ================= ЭКРАН 1: ВХОД ПО ПИН-КОДУ ================= -->
        <div id="screen-login" class="flex-1 flex flex-col justify-between p-6 pt-12 z-10">
            <div class="flex justify-between items-center">
                <div class="flex items-center gap-1.5">
                    <span class="text-2xl font-black italic tracking-tight text-white">Туса <span class="bg-white text-black px-1.5 py-0.5 rounded-md not-italic font-extrabold text-lg">Пэй</span></span>
                </div>
                <button onclick="openAdminModal()" class="flex items-center gap-1.5 bg-red-600/10 hover:bg-red-600/20 py-2 px-3 rounded-full border border-red-500/20 active:scale-95 transition">
                    <i class="fa-solid fa-user-shield text-red-400 text-xs"></i>
                    <span class="text-xs font-semibold text-red-400">Админка</span>
                </button>
            </div>

            <div class="text-center my-auto space-y-6">
                <div class="flex justify-center gap-5">
                    <div id="dot-0" class="w-3.5 h-3.5 rounded-full border-2 border-neutral-600 transition-all duration-150"></div>
                    <div id="dot-1" class="w-3.5 h-3.5 rounded-full border-2 border-neutral-600 transition-all duration-150"></div>
                    <div id="dot-2" class="w-3.5 h-3.5 rounded-full border-2 border-neutral-600 transition-all duration-150"></div>
                    <div id="dot-3" class="w-3.5 h-3.5 rounded-full border-2 border-neutral-600 transition-all duration-150"></div>
                </div>
                <p class="text-sm text-neutral-400">Введите код для входа</p>
                <p id="login-error" class="text-red-500 text-xs font-medium hidden"></p>
            </div>

            <div class="grid grid-cols-3 gap-y-6 gap-x-12 max-w-xs mx-auto pb-8">
                <button onclick="pressPin('1')" class="text-3xl font-normal py-3 active:text-neutral-400 transition">1</button>
                <button onclick="pressPin('2')" class="text-3xl font-normal py-3 active:text-neutral-400 transition">2</button>
                <button onclick="pressPin('3')" class="text-3xl font-normal py-3 active:text-neutral-400 transition">3</button>
                <button onclick="pressPin('4')" class="text-3xl font-normal py-3 active:text-neutral-400 transition">4</button>
                <button onclick="pressPin('5')" class="text-3xl font-normal py-3 active:text-neutral-400 transition">5</button>
                <button onclick="pressPin('6')" class="text-3xl font-normal py-3 active:text-neutral-400 transition">6</button>
                <button onclick="pressPin('7')" class="text-3xl font-normal py-3 active:text-neutral-400 transition">7</button>
                <button onclick="pressPin('8')" class="text-3xl font-normal py-3 active:text-neutral-400 transition">8</button>
                <button onclick="pressPin('9')" class="text-3xl font-normal py-3 active:text-neutral-400 transition">9</button>
                <div class="py-3"></div>
                <button onclick="pressPin('0')" class="text-3xl font-normal py-3 active:text-neutral-400 transition">0</button>
                <button onclick="clearPin()" class="text-2xl py-3 active:text-neutral-400 transition flex items-center justify-center">
                    <i class="fa-solid fa-delete-left"></i>
                </button>
            </div>
        </div>

        <!-- ================= ЭКРАН 2: ДАШБОРД ================= -->
        <div id="screen-dashboard" class="flex-1 flex flex-col p-4 space-y-4 overflow-y-auto hidden pb-24">
            
            <!-- Шапка дашборда -->
            <div class="flex justify-between items-center pb-2">
                <button id="logout-btn" class="w-10 h-10 flex items-center justify-center rounded-full bg-[#1c1c1e] text-neutral-400 hover:text-white active:scale-95 transition">
                    <i class="fa-solid fa-chevron-left text-lg"></i>
                </button>
                <div class="flex items-center gap-2">
                    <span class="text-sm font-semibold text-neutral-400" id="user-header-name">Загрузка...</span>
                    <button class="w-10 h-10 flex items-center justify-center rounded-full bg-[#1c1c1e] text-neutral-400"><i class="fa-solid fa-bell text-sm"></i></button>
                </div>
            </div>

            <!-- Дебетовая карта -->
            <div id="user-debit-card" class="design-1 rounded-[28px] p-5 relative flex flex-col justify-between aspect-[1.58/1] shadow-lg transition-all duration-500 overflow-hidden">
                <div class="flex justify-between items-start">
                    <span class="text-xs font-black tracking-widest uppercase opacity-80 flex items-center gap-1 text-current">
                        <span class="bg-black/10 px-1 rounded text-[10px]">T</span> TUSA CARD
                    </span>
                    <div id="card-qr-holder" class="bg-white p-1 rounded-lg shadow-md"></div>
                </div>

                <div class="my-1">
                    <p class="text-3xl font-black tracking-tight text-current" id="user-balance">0,00 ₽</p>
                </div>

                <div class="flex justify-between items-end text-current">
                    <div>
                        <p class="text-[8px] opacity-60 uppercase tracking-wider">Держатель</p>
                        <p class="text-xs font-bold" id="user-card-name">Имя Фамилия</p>
                    </div>
                    <button onclick="openDesignSelector()" class="bg-white/20 backdrop-blur-md border border-white/10 hover:bg-white/30 text-[11px] font-bold py-1 px-2.5 rounded-full flex items-center gap-1 transition text-current">
                        <i class="fa-solid fa-palette"></i> Дизайн
                    </button>
                </div>
            </div>

            <!-- Виджет общей Копилки -->
            <div id="piggy-bank-widget" class="glass-panel p-4 space-y-3">
                <div class="flex justify-between items-center">
                    <div class="flex items-center gap-2">
                        <span class="text-lg">🍕</span>
                        <div>
                            <h4 class="text-xs font-bold text-white">Общий сбор: <span id="piggy-title">На пиццу</span></h4>
                            <p class="text-[10px] text-neutral-400">Скидываемся всей тусой!</p>
                        </div>
                    </div>
                    <span class="text-xs font-bold text-emerald-400" id="piggy-progress-text">0 / 0 ₽</span>
                </div>
                
                <!-- Прогресс-бар -->
                <div class="w-full bg-neutral-800 h-2.5 rounded-full overflow-hidden">
                    <div id="piggy-progress-bar" class="bg-gradient-to-r from-emerald-500 to-teal-400 h-full rounded-full transition-all duration-500" style="width: 0%"></div>
                </div>

                <div class="flex gap-2">
                    <input id="piggy-donate-amount" type="number" placeholder="Сумма" class="flex-1 bg-[#1c1c1e] border border-white/5 rounded-xl px-3 py-1.5 text-xs text-white focus:outline-none">
                    <button onclick="donateToPiggy()" class="bg-emerald-500 hover:bg-emerald-600 text-black text-xs font-bold px-4 py-1.5 rounded-xl transition">Скинуться</button>
                </div>
            </div>

            <!-- Панель быстрых действий -->
            <div class="grid grid-cols-3 gap-3">
                <button onclick="alert('Для пополнения обратитесь к администратору!')" class="flex flex-col items-center justify-center py-4 rounded-2xl action-btn space-y-1.5">
                    <span class="w-11 h-11 rounded-full bg-neutral-800 flex items-center justify-center text-lg text-white"><i class="fa-solid fa-plus"></i></span>
                    <span class="text-xs font-medium text-neutral-300">Пополнить</span>
                </button>
                <button onclick="toggleTransferPanel()" class="flex flex-col items-center justify-center py-4 rounded-2xl action-btn space-y-1.5">
                    <span class="w-11 h-11 rounded-full bg-neutral-800 flex items-center justify-center text-lg text-white"><i class="fa-solid fa-arrow-up"></i></span>
                    <span class="text-xs font-medium text-neutral-300">Перевести</span>
                </button>
                <button onclick="startScanner('user')" class="flex flex-col items-center justify-center py-4 rounded-2xl action-btn space-y-1.5">
                    <span class="w-11 h-11 rounded-full bg-neutral-800 flex items-center justify-center text-lg text-white"><i class="fa-solid fa-qrcode"></i></span>
                    <span class="text-xs font-medium text-neutral-300">Оплатить</span>
                </button>
            </div>

            <!-- Выезжающая панель перевода -->
            <div id="transfer-panel" class="glass-panel p-5 space-y-4 hidden">
                <div class="flex justify-between items-center">
                    <h3 class="font-bold text-sm text-neutral-200">Перевод участнику</h3>
                    <button onclick="toggleTransferPanel()" class="text-neutral-500 text-xs">закрыть</button>
                </div>
                <div class="space-y-3">
                    <select id="transfer-recipient" class="w-full bg-[#1c1c1e] border border-white/5 rounded-xl p-3 text-xs text-white focus:outline-none">
                        <!-- Из базы -->
                    </select>
                    <input id="transfer-amount" type="number" min="1" placeholder="Сумма (₽)" class="w-full bg-[#1c1c1e] border border-white/5 rounded-xl p-3 text-xs text-white focus:outline-none">
                    <button onclick="sendMoney()" class="w-full bg-green-500 hover:bg-green-600 text-black font-bold py-3 rounded-xl text-xs transition">Отправить</button>
                </div>
            </div>

            <!-- История транзакций пользователя -->
            <div class="glass-panel p-4 space-y-3">
                <h3 class="text-xs font-bold text-neutral-400 uppercase tracking-wider">История операций</h3>
                <div id="user-history-list" class="space-y-2 max-h-48 overflow-y-auto">
                    <p class="text-xs text-neutral-500 text-center py-2">Транзакций пока нет</p>
                </div>
            </div>

        </div>
    </div>

    <!-- Модалка выбора дизайна -->
    <div id="design-selector-modal" class="fixed inset-0 bg-black/80 backdrop-blur-md z-50 flex items-center justify-center p-4 hidden">
        <div class="w-full max-w-sm glass-panel p-6 space-y-4">
            <div class="flex justify-between items-center">
                <h4 class="font-bold text-sm">Выберите узор и дизайн</h4>
                <button onclick="closeDesignSelector()" class="text-neutral-400"><i class="fa-solid fa-times"></i></button>
            </div>
            <div class="grid grid-cols-2 gap-2 max-h-60 overflow-y-auto p-1" id="designs-grid"></div>
        </div>
    </div>

    <!-- Модалка сканера QR-кодов -->
    <div id="scanner-modal" class="fixed inset-0 bg-black/95 z-50 flex flex-col justify-center items-center p-6 hidden">
        <div class="w-full max-w-sm glass-panel p-6 relative">
            <button onclick="stopScanner()" class="absolute top-4 right-4 text-white text-xl hover:text-red-500 transition-colors"><i class="fa-solid fa-times"></i></button>
            <h3 id="scanner-title" class="text-center font-bold mb-4 text-sm text-neutral-200">Наведите камеру</h3>
            <div id="reader" class="rounded-xl overflow-hidden" style="width: 100%;"></div>
        </div>
    </div>

    <!-- ================= МОДАЛКА АДМИН-ПАНЕЛИ (2141) ================= -->
    <div id="admin-modal" class="fixed inset-0 bg-black/90 backdrop-blur-md z-50 flex items-center justify-center p-4 hidden">
        <div class="w-full max-w-3xl glass-panel overflow-hidden max-h-[90vh] flex flex-col">
            
            <div class="p-5 border-b border-white/5 flex justify-between items-center bg-[#16161a]/80">
                <h2 class="text-sm font-bold text-neutral-200"><i class="fa-solid fa-user-shield mr-2 text-red-500"></i>Админка</h2>
                <div class="flex items-center gap-2">
                    <button onclick="startScanner('admin')" class="bg-indigo-600 hover:bg-indigo-700 text-xs text-white font-bold px-3 py-1.5 rounded-xl flex items-center gap-1 transition">
                        <i class="fa-solid fa-qrcode"></i> Скан карты юзера
                    </button>
                    <button onclick="closeAdminModal()" class="text-neutral-400 hover:text-white px-2"><i class="fa-solid fa-times text-lg"></i></button>
                </div>
            </div>

            <div class="p-6 overflow-y-auto space-y-6 flex-1 text-sm">
                
                <!-- Статистика -->
                <div class="grid grid-cols-2 gap-4">
                    <div class="bg-white/5 p-4 rounded-2xl border border-white/5">
                        <p class="text-[10px] text-neutral-400 uppercase">Всего денег в системе</p>
                        <p class="text-xl font-bold text-emerald-400 mt-1" id="stat-total-balance">0,00 ₽</p>
                    </div>
                    <div class="bg-white/5 p-4 rounded-2xl border border-white/5">
                        <p class="text-[10px] text-neutral-400 uppercase">Участников на тусе</p>
                        <p class="text-xl font-bold text-blue-400 mt-1" id="stat-total-users">0</p>
                    </div>
                </div>

                <!-- Управление Бегущей Строкой (Баннер) -->
                <div class="bg-[#1c1c1e]/50 p-4 rounded-2xl border border-white/5 space-y-3">
                    <h3 class="font-bold text-xs text-neutral-400 uppercase">Бегущая строка (Объявления)</h3>
                    <div class="flex gap-2">
                        <input id="admin-ticker-input" type="text" placeholder="Введите объявление (например: Диджей принимает заказы! 💿)" class="flex-1 bg-[#1c1c1e] border border-white/5 rounded-xl p-2.5 text-xs text-white">
                        <button onclick="updateTickerText()" class="bg-indigo-600 hover:bg-indigo-700 text-white font-bold px-4 py-2.5 rounded-xl transition text-xs">Обновить</button>
                    </div>
                    <p class="text-[10px] text-neutral-500">Оставь поле пустым и нажми "Обновить", чтобы скрыть баннер.</p>
                </div>

                <!-- Управление Копилкой -->
                <div class="bg-[#1c1c1e]/50 p-4 rounded-2xl border border-white/5 space-y-3">
                    <h3 class="font-bold text-xs text-neutral-400 uppercase">Управление общей копилкой</h3>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-3">
                        <input id="admin-piggy-title" type="text" placeholder="Цель (напр. На пиццу)" class="bg-[#1c1c1e] border border-white/5 rounded-xl p-2.5 text-xs text-white">
                        <input id="admin-piggy-target" type="number" placeholder="Нужная сумма (₽)" class="bg-[#1c1c1e] border border-white/5 rounded-xl p-2.5 text-xs text-white">
                        <button onclick="updatePiggyBankSettings()" class="bg-indigo-600 hover:bg-indigo-700 text-white font-bold py-2 rounded-xl transition text-xs">Обновить сбор</button>
                    </div>
                </div>

                <!-- Создать тусовщика -->
                <div class="space-y-3">
                    <h3 class="font-bold text-xs text-neutral-400 uppercase tracking-wider">Создать тусовщика</h3>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-3">
                        <input id="create-fio" type="text" placeholder="ФИО" class="bg-[#1c1c1e] border border-white/5 rounded-xl p-3 text-xs text-white">
                        <input id="create-phone" type="text" placeholder="Телефон" class="bg-[#1c1c1e] border border-white/5 rounded-xl p-3 text-xs text-white">
                        <input id="create-pin" type="text" maxlength="4" placeholder="ПИН-код (4 цифры)" class="bg-[#1c1c1e] border border-white/5 rounded-xl p-3 text-xs text-white">
                    </div>
                    <button onclick="createUser()" class="w-full bg-green-500 hover:bg-green-600 text-black font-bold py-2.5 rounded-xl transition text-xs">Добавить в систему</button>
                </div>

                <!-- Участники и счета -->
                <div class="space-y-3">
                    <h3 class="font-bold text-xs text-neutral-400 uppercase tracking-wider">Участники и Счета</h3>
                    <div id="quick-balance-adjust" class="bg-white/5 p-4 rounded-2xl border border-white/5 flex flex-wrap gap-2 items-center justify-between">
                        <div class="text-xs">
                            <span class="text-neutral-400 block">Выбран пользователь:</span>
                            <span id="selected-user-name" class="font-bold text-white">Не выбран</span>
                        </div>
                        <div class="flex gap-2">
                            <input id="adjust-sum-input" type="number" placeholder="Сумма" class="w-24 bg-[#1c1c1e] border border-white/5 rounded-xl p-2 text-xs text-white">
                            <button onclick="modifyBalance('add')" class="bg-green-600 text-white font-bold px-3 py-2 rounded-xl text-xs hover:bg-green-500">Начислить</button>
                            <button onclick="modifyBalance('sub')" class="bg-red-600 text-white font-bold px-3 py-2 rounded-xl text-xs hover:bg-red-500">Списать</button>
                        </div>
                    </div>

                    <div class="overflow-x-auto">
                        <table class="w-full text-left text-xs text-neutral-300">
                            <thead>
                                <tr class="border-b border-white/5 text-neutral-500">
                                    <th class="py-2">Выбор</th>
                                    <th>Тусовщик</th>
                                    <th>Баланс</th>
                                    <th>Статус</th>
                                    <th>Действия</th>
                                </tr>
                            </thead>
                            <tbody id="admin-users-list"></tbody>
                        </table>
                    </div>
                </div>

                <!-- Печать бумажных карт -->
                <div class="p-4 bg-white/5 rounded-2xl border border-white/5 flex justify-between items-center">
                    <div>
                        <h4 class="font-bold text-xs text-neutral-200">Печать бумажных карточек</h4>
                        <p class="text-[10px] text-neutral-400">Выделите галочками пользователей выше для распечатки</p>
                    </div>
                    <button onclick="printSelectedCards()" class="bg-blue-600 hover:bg-blue-700 text-white font-bold px-4 py-2 rounded-xl text-xs transition">
                        <i class="fa-solid fa-print mr-1"></i> Распечатать
                    </button>
                </div>

                <!-- Generator платежных QR -->
                <div class="space-y-3">
                    <h3 class="font-bold text-xs text-neutral-400 uppercase tracking-wider">Создать QR-код на оплату</h3>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-3">
                        <input id="qr-pay-desc" type="text" placeholder="За что оплата (напр. Вход на тусу)" class="bg-[#1c1c1e] border border-white/5 rounded-xl p-3 text-xs text-white">
                        <input id="qr-pay-amount" type="number" placeholder="Сумма списания (₽)" class="bg-[#1c1c1e] border border-white/5 rounded-xl p-3 text-xs text-white">
                    </div>
                    <button onclick="generatePaymentQR()" class="w-full bg-indigo-600 hover:bg-indigo-700 text-white font-bold py-2.5 rounded-xl transition text-xs">Создать QR</button>
                    <div id="admin-qr-container" class="flex flex-col items-center py-4 hidden">
                        <div id="admin-qr-output" class="bg-white p-3 rounded-xl mb-2"></div>
                    </div>
                </div>

                <!-- Логи -->
                <div class="space-y-3">
                    <h3 class="font-bold text-xs text-neutral-400 uppercase tracking-wider">Логи событий</h3>
                    <div class="bg-black/40 rounded-xl p-4 max-h-40 overflow-y-auto text-[11px] font-mono space-y-1.5" id="admin-logs"></div>
                </div>

            </div>
        </div>
    </div>

    <!-- Полноэкранный оверлей успешной оплаты -->
    <div id="success-overlay" class="fixed inset-0 bg-black/90 z-50 flex flex-col items-center justify-center space-y-4 hidden">
        <div class="w-24 h-24 rounded-full bg-emerald-500 flex items-center justify-center text-white text-5xl shadow-[0_0_40px_rgba(16,185,129,0.5)] scale-90 transition-all duration-500" id="success-checkmark">
            <i class="fa-solid fa-check"></i>
        </div>
        <h2 class="text-xl font-bold text-white tracking-wide" id="success-message">Оплата успешно проведена!</h2>
        <p class="text-sm text-neutral-400" id="success-submessage"></p>
    </div>

    <!-- Область печати -->
    <div id="print-zone" class="hidden flex-wrap gap-6 p-10 justify-center"></div>

    <script>
        // ================= ТВОИ НАСТОЯЩИЕ КЛЮЧИ FIREBASE =================
        const firebaseConfig = {
            apiKey: "AIzaSyA1nrHwtnahLaU6FEINNIKM03QYwKhThYo",
            authDomain: "tusa-pay.firebaseapp.com",
            databaseURL: "https://tusa-pay-default-rtdb.firebaseio.com",
            projectId: "tusa-pay",
            storageBucket: "tusa-pay.firebasestorage.app",
            messagingSenderId: "308586374263",
            appId: "1:308586374263:web:71124b3762fbfb8ad59272",
            measurementId: "G-YDYW28NZBG"
        };

        firebase.initializeApp(firebaseConfig);
        const db = firebase.firestore();

        const screenLogin = document.getElementById('screen-login');
        const screenDashboard = document.getElementById('screen-dashboard');

        let currentUser = null;
        let currentPinInput = "";
        let html5QrcodeScanner = null;
        let activeScannerRole = ""; 
        let allUsers = [];
        let selectedAdminUser = null;

        // Звуковые эффекты (Web Audio API)
        const audioCtx = new (window.AudioContext || window.webkitAudioContext)();

        function playSound(type) {
            const osc = audioCtx.createOscillator();
            const gain = audioCtx.createGain();
            osc.connect(gain);
            gain.connect(audioCtx.destination);

            if (type === 'click') {
                osc.type = 'sine';
                osc.frequency.setValueAtTime(600, audioCtx.currentTime);
                gain.gain.setValueAtTime(0.05, audioCtx.currentTime);
                gain.gain.exponentialRampToValueAtTime(0.01, audioCtx.currentTime + 0.05);
                osc.start();
                osc.stop(audioCtx.currentTime + 0.05);
            } else if (type === 'success') {
                osc.type = 'sine';
                osc.frequency.setValueAtTime(523.25, audioCtx.currentTime); 
                osc.frequency.setValueAtTime(659.25, audioCtx.currentTime + 0.1); 
                osc.frequency.setValueAtTime(783.99, audioCtx.currentTime + 0.2); 
                osc.frequency.setValueAtTime(1046.50, audioCtx.currentTime + 0.3); 
                gain.gain.setValueAtTime(0.1, audioCtx.currentTime);
                gain.gain.exponentialRampToValueAtTime(0.01, audioCtx.currentTime + 0.6);
                osc.start();
                osc.stop(audioCtx.currentTime + 0.6);
            } else if (type === 'error') {
                osc.type = 'sawtooth';
                osc.frequency.setValueAtTime(120, audioCtx.currentTime);
                gain.gain.setValueAtTime(0.1, audioCtx.currentTime);
                gain.gain.exponentialRampToValueAtTime(0.01, audioCtx.currentTime + 0.3);
                osc.start();
                osc.stop(audioCtx.currentTime + 0.3);
            }
        }

        // 10 стильных дизайнов
        const cardDesigns = [
            { class: "design-1", name: "Зеленая Мята" },
            { class: "design-2", name: "Неоновый Фиолет" },
            { class: "design-3", name: "Яркий Закат" },
            { class: "design-4", name: "Жидкое Золото" },
            { class: "design-5", name: "Космические Точки" },
            { class: "design-6", name: "Киберпанк Линии" },
            { class: "design-7", name: "Морская Волна" },
            { class: "design-8", name: "Розовый Неон" },
            { class: "design-9", name: "Темный Карбон" },
            { class: "design-10", name: "Огненный Апельсин" }
        ];

        window.addEventListener('DOMContentLoaded', () => {
            loadUsersForTransfer();
            buildDesignSelector();
            listenToPiggyBank();
            listenToTicker();
        });

        // Всплывающее уведомление (Toast)
        function showToast(text, type = "success") {
            const toast = document.createElement('div');
            toast.className = `fixed top-6 left-1/2 transform -translate-x-1/2 z-50 px-5 py-3 rounded-full text-xs font-bold shadow-lg transition-all duration-300 translate-y-[-20px] opacity-0 flex items-center gap-2 ${
                type === 'success' ? 'bg-emerald-500 text-black' : 'bg-red-500 text-white'
            }`;
            toast.innerHTML = `<i class="fa-solid ${type === 'success' ? 'fa-check-circle' : 'fa-exclamation-circle'}"></i> <span>${text}</span>`;
            document.body.appendChild(toast);
            
            setTimeout(() => {
                toast.classList.remove('translate-y-[-20px]', 'opacity-0');
            }, 50);

            setTimeout(() => {
                toast.classList.add('translate-y-[-20px]', 'opacity-0');
                setTimeout(() => toast.remove(), 300);
            }, 3000);
        }

        // Показ анимации успешной оплаты
        function triggerSuccessAnimation(msg, submsg) {
            playSound('success');
            const overlay = document.getElementById('success-overlay');
            const check = document.getElementById('success-checkmark');
            document.getElementById('success-message').textContent = msg;
            document.getElementById('success-submessage').textContent = submsg;

            overlay.classList.remove('hidden');
            setTimeout(() => {
                check.classList.remove('scale-90');
                check.classList.add('scale-110');
            }, 100);

            setTimeout(() => {
                overlay.classList.add('hidden');
                check.classList.remove('scale-110');
                check.classList.add('scale-90');
            }, 3500);
        }

        // Сетка выбора дизайна
        function buildDesignSelector() {
            const grid = document.getElementById('designs-grid');
            grid.innerHTML = "";
            cardDesigns.forEach(d => {
                const btn = document.createElement('button');
                btn.className = `${d.class} h-16 rounded-xl text-xs font-bold transition active:scale-95 flex items-center justify-center p-2 text-center border border-white/10`;
                btn.textContent = d.name;
                btn.onclick = () => selectCardTheme(d.class);
                grid.appendChild(btn);
            });
        }

        // ================= БЕГУЩАЯ СТРОКА =================
        function listenToTicker() {
            db.collection("config").doc("ticker").onSnapshot(doc => {
                const banner = document.getElementById('ticker-banner');
                const tickerText = document.getElementById('ticker-text');
                if (doc.exists) {
                    const data = doc.data();
                    if (data.text && data.text.trim() !== "") {
                        tickerText.textContent = data.text;
                        banner.classList.remove('hidden');
                    } else {
                        banner.classList.add('hidden');
                    }
                } else {
                    banner.classList.add('hidden');
                }
            });
        }

        function updateTickerText() {
            const txt = document.getElementById('admin-ticker-input').value.trim();
            db.collection("config").doc("ticker").set({
                text: txt
            }).then(() => {
                showToast("Бегущая строка обновлена!");
                document.getElementById('admin-ticker-input').value = "";
            }).catch(err => {
                alert("Ошибка сохранения: " + err);
            });
        }

        // ================= ПИН-КОД АВТОРИЗАЦИЯ =================
        function pressPin(num) {
            playSound('click');
            if (currentPinInput.length < 4) {
                currentPinInput += num;
                updatePinDots();
            }
            if (currentPinInput.length === 4) {
                setTimeout(verifyPin, 200);
            }
        }

        function clearPin() {
            playSound('click');
            currentPinInput = currentPinInput.slice(0, -1);
            updatePinDots();
        }

        function updatePinDots() {
            for (let i = 0; i < 4; i++) {
                const dot = document.getElementById(`dot-${i}`);
                if (i < currentPinInput.length) {
                    dot.classList.add('bg-white', 'scale-125');
                    dot.classList.remove('border-neutral-600');
                } else {
                    dot.classList.remove('bg-white', 'scale-125');
                    dot.classList.add('border-neutral-600');
                }
            }
        }

        function verifyPin() {
            document.getElementById('login-error').classList.add('hidden');
            
            db.collection("users").where("pin", "==", currentPinInput).get().then(querySnapshot => {
                if (!querySnapshot.empty) {
                    const userDoc = querySnapshot.docs[0];
                    const userData = userDoc.data();
                    
                    if (userData.blocked) {
                        playSound('error');
                        showLoginError("Карта заблокирована!");
                        resetPinInput();
                        return;
                    }

                    currentUser = { id: userDoc.id, ...userData };
                    setupDashboardListener();
                    setupUserHistoryListener(); 
                    
                    screenLogin.classList.add('hidden');
                    screenDashboard.classList.remove('hidden');
                    resetPinInput();
                    showToast(`Добро пожаловать, ${userData.fio.split(' ')[0]}!`);
                } else {
                    playSound('error');
                    showLoginError("Неверный код доступа");
                    resetPinInput();
                }
            }).catch(err => {
                console.error(err);
                showLoginError("Ошибка сети.");
                resetPinInput();
            });
        }

        function resetPinInput() {
            currentPinInput = "";
            updatePinDots();
        }

        function showLoginError(text) {
            const errEl = document.getElementById('login-error');
            errEl.textContent = text;
            errEl.classList.remove('hidden');
        }

        // Выход
        document.getElementById('logout-btn').addEventListener('click', () => {
            currentUser = null;
            screenDashboard.classList.add('hidden');
            screenLogin.classList.remove('hidden');
        });

        // ================= ДАШБОРД ЮЗЕРА =================
        function setupDashboardListener() {
            if (!currentUser) return;

            db.collection("users").doc(currentUser.id).onSnapshot(doc => {
                if (!doc.exists) return;
                const data = doc.data();
                
                if (data.blocked) {
                    alert("Ваш аккаунт заблокирован!");
                    document.getElementById('logout-btn').click();
                    return;
                }

                document.getElementById('user-balance').textContent = `${data.balance.toLocaleString('ru-RU', { minimumFractionDigits: 2 })} ₽`;
                document.getElementById('user-card-name').textContent = data.fio;
                document.getElementById('user-header-name').textContent = data.fio.split(' ')[0];

                const card = document.getElementById('user-debit-card');
                card.className = `rounded-[28px] p-5 relative flex flex-col justify-between aspect-[1.58/1] shadow-lg transition-all duration-500 overflow-hidden ${data.cardDesign || 'design-1'}`;

                const qrHolder = document.getElementById('card-qr-holder');
                qrHolder.innerHTML = "";
                new QRCode(qrHolder, {
                    text: `tusa_user:${currentUser.id}`,
                    width: 42,
                    height: 42,
                    colorDark: "#000000",
                    colorLight: "#ffffff",
                    correctLevel: QRCode.CorrectLevel.H
                });
            });
        }

        // История операций для пользователя
        function setupUserHistoryListener() {
            if (!currentUser) return;
            
            db.collection("logs").orderBy("timestamp", "desc").onSnapshot(snapshot => {
                const historyBox = document.getElementById('user-history-list');
                historyBox.innerHTML = "";
                
                let count = 0;
                snapshot.forEach(doc => {
                    const d = doc.data();
                    const logText = d.text;
                    const cleanName = currentUser.fio;

                    if (logText.includes(cleanName)) {
                        count++;
                        let amountMatch = logText.match(/(\d+)\s*₽/);
                        let sum = amountMatch ? amountMatch[1] : "";
                        let isPositive = logText.includes("получил") || logText.includes("начислил") || logText.includes(`-> ${cleanName}`);

                        const item = document.createElement('div');
                        item.className = "flex justify-between items-center bg-white/5 p-2.5 rounded-xl text-xs";
                        
                        let displayDesc = logText.replace(cleanName, "Вы");
                        
                        item.innerHTML = `
                            <div class="flex items-center gap-2">
                                <span class="w-7 h-7 rounded-full ${isPositive ? 'bg-emerald-500/10 text-emerald-400' : 'bg-red-500/10 text-red-400'} flex items-center justify-center">
                                    <i class="fa-solid ${isPositive ? 'fa-arrow-down-long' : 'fa-arrow-up-long'}"></i>
                                </span>
                                <div>
                                    <p class="font-medium text-neutral-200 text-[11px] leading-tight">${displayDesc}</p>
                                </div>
                            </div>
                            ${sum ? `<span class="font-bold ${isPositive ? 'text-emerald-400' : 'text-neutral-400'}">${isPositive ? '+' : '-'}${sum} ₽</span>` : ''}
                        `;
                        historyBox.appendChild(item);
                    }
                });

                if (count === 0) {
                    historyBox.innerHTML = `<p class="text-xs text-neutral-500 text-center py-2">Транзакций пока нет</p>`;
                }
            });
        }

        function openDesignSelector() {
            document.getElementById('design-selector-modal').classList.remove('hidden');
        }

        function closeDesignSelector() {
            document.getElementById('design-selector-modal').classList.add('hidden');
        }

        function selectCardTheme(themeClass) {
            if (!currentUser) return;
            db.collection("users").doc(currentUser.id).update({
                cardDesign: themeClass
            }).then(() => {
                closeDesignSelector();
            });
        }

        function toggleTransferPanel() {
            document.getElementById('transfer-panel').classList.toggle('hidden');
        }

        function loadUsersForTransfer() {
            db.collection("users").onSnapshot(snapshot => {
                const select = document.getElementById('transfer-recipient');
                select.innerHTML = '<option value="">Выбери получателя...</option>';
                allUsers = [];
                snapshot.forEach(doc => {
                    const u = doc.data();
                    u.id = doc.id;
                    allUsers.push(u);
                    
                    if (!currentUser || doc.id !== currentUser.id) {
                        const opt = document.createElement('option');
                        opt.value = doc.id;
                        opt.textContent = `${u.fio}`;
                        select.appendChild(opt);
                    }
                });
            });
        }

        // Перевод монет между пользователями
        async function sendMoney() {
            const recipientId = document.getElementById('transfer-recipient').value;
            const amount = parseFloat(document.getElementById('transfer-amount').value);

            if (!recipientId || isNaN(amount) || amount <= 0) {
                playSound('error');
                showToast("Укажите правильного получателя и сумму!", "error");
                return;
            }

            const senderRef = db.collection("users").doc(currentUser.id);
            const receiverRef = db.collection("users").doc(recipientId);

            try {
                await db.runTransaction(async (transaction) => {
                    const senderDoc = await transaction.get(senderRef);
                    const receiverDoc = await transaction.get(receiverRef);

                    if (!senderDoc.exists || !receiverDoc.exists) throw "Пользователь не найден.";

                    const senderBalance = senderDoc.data().balance;
                    if (senderBalance < amount) throw "Недостаточно средств!";

                    transaction.update(senderRef, { balance: senderBalance - amount });
                    transaction.update(receiverRef, { balance: receiverDoc.data().balance + amount });
                    
                    const logRef = db.collection("logs").doc();
                    transaction.set(logRef, {
                        timestamp: firebase.firestore.FieldValue.serverTimestamp(),
                        text: `${senderDoc.data().fio} перевел ${amount} ₽ -> ${receiverDoc.data().fio}`
                    });
                });

                document.getElementById('transfer-amount').value = "";
                toggleTransferPanel();
                triggerSuccessAnimation("Перевод выполнен!", `Получатель: ${allUsers.find(u => u.id === recipientId).fio}`);
            } catch (err) {
                playSound('error');
                showToast("Ошибка перевода: " + err, "error");
            }
        }

        // ================= СКАНИРОВАНИЕ И ОПЛАТА ПО QR =================
        function startScanner(role) {
            activeScannerRole = role; 
            const title = document.getElementById('scanner-title');
            title.textContent = role === 'admin' ? "Отсканируйте карту тусовщика" : "Наведите камеру на QR-код оплаты";

            document.getElementById('scanner-modal').classList.remove('hidden');
            
            // Если сканер уже был создан ранее, используем его, иначе создаем новый
            if (!html5QrcodeScanner) {
                html5QrcodeScanner = new Html5Qrcode("reader");
            }
            
            html5QrcodeScanner.start(
                { facingMode: "environment" },
                { fps: 10, qrbox: 250 },
                onScanSuccess
            ).catch(err => {
                console.error("Камера недоступна:", err);
                alert("Не удалось запустить камеру. Проверьте разрешения.");
                stopScanner();
            });
        }

        async function stopScanner() {
            // МГНОВЕННО скрываем модалку с экрана
            document.getElementById('scanner-modal').classList.add('hidden');
            
            // Безопасно тушим саму камеру на фоне
            if (html5QrcodeScanner) {
                try {
                    if (html5QrcodeScanner.isScanning) {
                        await html5QrcodeScanner.stop();
                    }
                } catch (err) {
                    console.warn("Камера уже была остановлена или произошел сбой при закрытии:", err);
                }
            }
        }

        async function onScanSuccess(decodedText) {
            // Сначала выключаем сканер
            await stopScanner();
            
            if (activeScannerRole === "user") {
                if (decodedText.startsWith("tusa_pay:")) {
                    const parts = decodedText.split(":");
                    const amount = parseFloat(parts[1]);
                    const desc = parts[2];

                    if (isNaN(amount)) {
                        playSound('error');
                        showToast("Некорректный QR!", "error");
                        return;
                    }

                    const confirmPay = confirm(`Оплатить по запросу: "${desc}" на сумму ${amount} ₽?`);
                    if (confirmPay) {
                        const userRef = db.collection("users").doc(currentUser.id);
                        try {
                            await db.runTransaction(async (transaction) => {
                                const userDoc = await transaction.get(userRef);
                                const currentBalance = userDoc.data().balance;
                                if (currentBalance < amount) throw "Недостаточно средств!";
                                
                                transaction.update(userRef, { balance: currentBalance - amount });
                                
                                const logRef = db.collection("logs").doc();
                                transaction.set(logRef, {
                                    timestamp: firebase.firestore.FieldValue.serverTimestamp(),
                                    text: `${userDoc.data().fio} оплатил по QR "${desc}": ${amount} ₽`
                                });
                            });
                            triggerSuccessAnimation("Оплачено!", `${desc}: ${amount} ₽`);
                        } catch (e) {
                            playSound('error');
                            showToast("Ошибка оплаты: " + e, "error");
                        }
                    }
                } else {
                    playSound('error');
                    showToast("Неверный QR-код для оплаты.", "error");
                }
            } 
            else if (activeScannerRole === "admin") {
                if (decodedText.startsWith("tusa_user:")) {
                    const userId = decodedText.split(":")[1];
                    const foundUser = allUsers.find(u => u.id === userId);
                    if (foundUser) {
                        selectUserForAdmin(foundUser.id, foundUser.fio);
                        showToast(`Участник ${foundUser.fio.split(' ')[0]} выбран!`);
                    } else {
                        playSound('error');
                        showToast("Пользователь не найден.", "error");
                    }
                } else {
                    playSound('error');
                    showToast("Это не QR пользователя.", "error");
                }
            }
        }

        // ================= ОБЩАЯ КОПИЛКА =================
        function listenToPiggyBank() {
            db.collection("config").doc("piggyBank").onSnapshot(doc => {
                if (!doc.exists) return;
                const data = doc.data();

                document.getElementById('piggy-title').textContent = data.title;
                document.getElementById('piggy-progress-text').textContent = `${data.current.toLocaleString()} / ${data.target.toLocaleString()} ₽`;
                
                let pct = (data.current / data.target) * 100;
                if (pct > 100) pct = 100;
                document.getElementById('piggy-progress-bar').style.width = `${pct}%`;
            });
        }

        async function donateToPiggy() {
            const amount = parseFloat(document.getElementById('piggy-donate-amount').value);
            if (isNaN(amount) || amount <= 0) {
                playSound('error');
                showToast("Введите сумму!", "error");
                return;
            }

            const userRef = db.collection("users").doc(currentUser.id);
            const piggyRef = db.collection("config").doc("piggyBank");

            try {
                await db.runTransaction(async (transaction) => {
                    const userDoc = await transaction.get(userRef);
                    const piggyDoc = await transaction.get(piggyRef);

                    if (userDoc.data().balance < amount) throw "Недостаточно средств на балансе!";

                    transaction.update(userRef, { balance: userDoc.data().balance - amount });
                    transaction.update(piggyRef, { current: piggyDoc.data().current + amount });

                    const logRef = db.collection("logs").doc();
                    transaction.set(logRef, {
                        timestamp: firebase.firestore.FieldValue.serverTimestamp(),
                        text: `${userDoc.data().fio} скинул в копилку "${piggyDoc.data().title}": ${amount} ₽`
                    });
                });

                document.getElementById('piggy-donate-amount').value = "";
                triggerSuccessAnimation("Спасибо за вклад!", `В копилку внесено: ${amount} ₽`);
            } catch (err) {
                playSound('error');
                showToast("Ошибка: " + err, "error");
            }
        }

        // ================= АДМИНКА (2141) =================
        function openAdminModal() {
            const pwd = prompt("Введите пароль администратора:");
            if (pwd === "2141") {
                document.getElementById('admin-modal').classList.remove('hidden');
                loadAdminData();
            } else {
                playSound('error');
                alert("Неверный пароль!");
            }
        }

        function closeAdminModal() {
            document.getElementById('admin-modal').classList.add('hidden');
        }

        function selectUserForAdmin(id, name) {
            selectedAdminUser = { id, name };
            document.getElementById('selected-user-name').textContent = name;
        }

        function modifyBalance(action) {
            if (!selectedAdminUser) {
                alert("Выберите пользователя!");
                return;
            }
            const val = parseFloat(document.getElementById('adjust-sum-input').value);
            if (isNaN(val) || val <= 0) {
                alert("Введите сумму!");
                return;
            }

            const change = action === 'add' ? val : -val;
            const ref = db.collection("users").doc(selectedAdminUser.id);

            db.runTransaction(async (transaction) => {
                const doc = await transaction.get(ref);
                const currentBalance = doc.data().balance;
                transaction.update(ref, { balance: currentBalance + change });
                
                const logRef = db.collection("logs").doc();
                transaction.set(logRef, {
                    timestamp: firebase.firestore.FieldValue.serverTimestamp(),
                    text: `Админ изменил баланс ${doc.data().fio} на ${change} ₽`
                });
            }).then(() => {
                document.getElementById('adjust-sum-input').value = "";
                playSound('success');
                showToast("Баланс обновлен!");
            }).catch(err => alert("Ошибка: " + err));
        }

        // Управление Копилкой из админки
        function updatePiggyBankSettings() {
            const title = document.getElementById('admin-piggy-title').value.trim();
            const target = parseFloat(document.getElementById('admin-piggy-target').value);

            if (!title || isNaN(target) || target <= 0) {
                alert("Заполните настройки копилки!");
                return;
            }

            db.collection("config").doc("piggyBank").set({
                title: title,
                target: target,
                current: 0 
            }).then(() => {
                showToast("Копилка успешно запущена!");
                document.getElementById('admin-piggy-title').value = "";
                document.getElementById('admin-piggy-target').value = "";
            });
        }

        function loadAdminData() {
            // Подгрузка логов
            db.collection("logs").orderBy("timestamp", "desc").limit(30).onSnapshot(snapshot => {
                const logsBox = document.getElementById('admin-logs');
                logsBox.innerHTML = "";
                snapshot.forEach(doc => {
                    const d = doc.data();
                    let time = d.timestamp ? d.timestamp.toDate().toLocaleTimeString() : "...";
                    logsBox.innerHTML += `<div class="text-neutral-500"><span class="text-indigo-400">[${time}]</span> ${d.text}</div>`;
                });
            });

            // Статистика и список пользователей
            db.collection("users").onSnapshot(snapshot => {
                const list = document.getElementById('admin-users-list');
                list.innerHTML = "";
                
                let totalSum = 0;
                let totalUsers = 0;

                snapshot.forEach(doc => {
                    const u = doc.data();
                    const id = doc.id;
                    totalSum += u.balance;
                    totalUsers++;

                    const statusText = u.blocked ? '<span class="text-red-500">Блок</span>' : '<span class="text-green-500">ОК</span>';
                    const blockBtnText = u.blocked ? 'Разблок' : 'Блок';

                    list.innerHTML += `
                        <tr class="border-b border-white/5 cursor-pointer hover:bg-white/5 transition-colors" onclick="selectUserForAdmin('${id}', '${u.fio}')">
                            <td class="py-2.5" onclick="event.stopPropagation()">
                                <input type="checkbox" class="user-print-checkbox w-4 h-4 rounded border-white/10 bg-[#1c1c1e]" value="${id}">
                            </td>
                            <td class="py-2.5">
                                <div class="font-bold text-white">${u.fio}</div>
                                <div class="text-[10px] text-neutral-500">${u.phone} | ПИН: ${u.pin}</div>
                            </td>
                            <td class="font-mono font-bold text-white">${u.balance.toFixed(2)} ₽</td>
                            <td>${statusText}</td>
                            <td class="space-x-1 py-2.5" onclick="event.stopPropagation()">
                                <button onclick="toggleBlockUser('${id}', ${u.blocked})" class="bg-yellow-500/10 hover:bg-yellow-500 text-yellow-400 hover:text-black text-[10px] font-bold px-2.5 py-1 rounded transition">${blockBtnText}</button>
                            </td>
                        </tr>
                    `;
                });

                document.getElementById('stat-total-balance').textContent = `${totalSum.toLocaleString('ru-RU', { minimumFractionDigits: 2 })} ₽`;
                document.getElementById('stat-total-users').textContent = totalUsers;
            });
        }

        function createUser() {
            const fio = document.getElementById('create-fio').value.trim();
            const phone = document.getElementById('create-phone').value.trim();
            const pin = document.getElementById('create-pin').value.trim();

            if (!fio || !phone || pin.length !== 4) {
                alert("Заполните все поля! ПИН должен состоять из 4 цифр.");
                return;
            }

            db.collection("users").add({
                fio: fio,
                phone: phone,
                pin: pin,
                balance: 0,
                blocked: false,
                cardDesign: "design-1"
            }).then(() => {
                db.collection("logs").add({
                    timestamp: firebase.firestore.FieldValue.serverTimestamp(),
                    text: `Админ зарегистрировал пользователя: ${fio}`
                });
                showToast("Пользователь добавлен!");
                document.getElementById('create-fio').value = "";
                document.getElementById('create-phone').value = "";
                document.getElementById('create-pin').value = "";
            });
        }

        function toggleBlockUser(userId, currentBlockedStatus) {
            db.collection("users").doc(userId).update({
                blocked: !currentBlockedStatus
            });
        }

        function generatePaymentQR() {
            const desc = document.getElementById('qr-pay-desc').value.trim();
            const amount = parseFloat(document.getElementById('qr-pay-amount').value);

            if (!desc || isNaN(amount) || amount <= 0) {
                alert("Заполните описание и сумму!");
                return;
            }

            const payload = `tusa_pay:${amount}:${desc}`;
            const qrContainer = document.getElementById('admin-qr-container');
            const qrOutput = document.getElementById('admin-qr-output');
            
            qrOutput.innerHTML = "";
            qrContainer.classList.remove('hidden');

            new QRCode(qrOutput, {
                text: payload,
                width: 140,
                height: 140,
                colorDark: "#000000",
                colorLight: "#ffffff"
            });
        }

        // ================= ПЕЧАТЬ БУМАЖНЫХ КАРТОЧЕК =================
        function printSelectedCards() {
            const checkedBoxes = document.querySelectorAll('.user-print-checkbox:checked');
            if (checkedBoxes.length === 0) {
                alert("Отметьте галочками тех пользователей, чьи карты вы хотите распечатать!");
                return;
            }

            const printZone = document.getElementById('print-zone');
            printZone.innerHTML = ""; 

            let cardsHtml = "";
            let generatedQrs = [];

            checkedBoxes.forEach((box, index) => {
                const userId = box.value;
                const user = allUsers.find(u => u.id === userId);
                if (user) {
                    const designClass = user.cardDesign || "design-1";
                    const qrId = `print-qr-${index}`;
                    
                    cardsHtml += `
                        <div class="print-card w-[350px] h-[220px] rounded-[24px] p-5 flex flex-col justify-between relative shadow-lg overflow-hidden ${designClass}" style="margin: 15px; display: inline-flex; page-break-inside: avoid; border: 2px solid #000000;">
                            <div class="flex justify-between items-start">
                                <span class="text-xs font-black tracking-widest uppercase text-current">TUSA CARD</span>
                                <div id="${qrId}" class="bg-white p-1 rounded shadow" style="display: block;"></div>
                            </div>
                            <div class="text-current">
                                <p class="text-sm font-extrabold uppercase tracking-wide">${user.fio}</p>
                                <p class="text-[9px] opacity-80 mt-0.5">${user.phone}</p>
                            </div>
                            <div class="flex justify-between items-end text-current">
                                <span class="text-[9px] font-bold uppercase tracking-widest">ПИН-КОД: ${user.pin}</span>
                                <span class="text-[9px] font-black tracking-widest uppercase">TUSA PAY</span>
                            </div>
                        </div>
                    `;
                    
                    generatedQrs.push({ id: qrId, text: `tusa_user:${user.id}` });
                }
            });

            printZone.innerHTML = cardsHtml;
            printZone.classList.remove('hidden');

            setTimeout(() => {
                generatedQrs.forEach(item => {
                    new QRCode(document.getElementById(item.id), {
                        text: item.text,
                        width: 55,
                        height: 55,
                        colorDark: "#000000",
                        colorLight: "#ffffff",
                        correctLevel: QRCode.CorrectLevel.H
                    });
                });
                
                window.print();
                
                setTimeout(() => {
                    printZone.classList.add('hidden');
                }, 1000);
            }, 500);
        }
    </script>
</body>
</html>
