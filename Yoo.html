<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MishOlya Bank - Банковская система</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            color: #333;
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background: linear-gradient(to right, #1a2980, #26d0ce);
            color: white;
            padding: 25px 0;
            border-radius: 0 0 15px 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .logo i {
            font-size: 2.5rem;
            color: #FFD700;
        }

        h1 {
            font-size: 2.2rem;
            font-weight: 700;
        }

        .tagline {
            font-style: italic;
            opacity: 0.9;
            margin-top: 5px;
        }

        .user-info {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .user-avatar {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background-color: rgba(255, 255, 255, 0.2);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2rem;
        }

        .user-name {
            font-weight: 600;
        }

        .user-role {
            font-size: 0.9rem;
            opacity: 0.9;
        }

        .btn-logout {
            background: rgba(255, 255, 255, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.3);
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            cursor: pointer;
            transition: all 0.3s;
            font-weight: 600;
        }

        .btn-logout:hover {
            background: rgba(255, 255, 255, 0.3);
        }

        /* Стили для форм входа/регистрации */
        .auth-container {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 70vh;
        }

        .auth-box {
            background-color: white;
            border-radius: 12px;
            padding: 40px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 500px;
        }

        .auth-title {
            color: #1a2980;
            text-align: center;
            margin-bottom: 30px;
            font-size: 1.8rem;
        }

        .auth-tabs {
            display: flex;
            margin-bottom: 30px;
            border-bottom: 2px solid #eee;
        }

        .auth-tab {
            flex: 1;
            text-align: center;
            padding: 15px;
            background: none;
            border: none;
            font-size: 1.1rem;
            font-weight: 600;
            color: #777;
            cursor: pointer;
            transition: all 0.3s;
            position: relative;
        }

        .auth-tab.active {
            color: #1a2980;
        }

        .auth-tab.active::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 100%;
            height: 3px;
            background-color: #26d0ce;
        }

        .auth-form {
            display: none;
        }

        .auth-form.active {
            display: block;
        }

        .form-group {
            margin-bottom: 20px;
        }

        label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            color: #444;
        }

        input, select {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-size: 1rem;
            transition: border 0.3s;
        }

        input:focus, select:focus {
            border-color: #26d0ce;
            outline: none;
            box-shadow: 0 0 0 2px rgba(38, 208, 206, 0.2);
        }

        .btn {
            background: linear-gradient(to right, #1a2980, #26d0ce);
            color: white;
            border: none;
            padding: 14px 25px;
            border-radius: 8px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            width: 100%;
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 7px 14px rgba(0, 0, 0, 0.1);
        }

        .btn-secondary {
            background: linear-gradient(to right, #6a11cb, #2575fc);
        }

        .btn-danger {
            background: linear-gradient(to right, #ff416c, #ff4b2b);
        }

        /* Основной контент */
        .main-content {
            display: none;
        }

        .section {
            background-color: white;
            border-radius: 12px;
            padding: 25px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
            transition: transform 0.3s ease;
            margin-bottom: 30px;
        }

        .section:hover {
            transform: translateY(-5px);
        }

        .section-title {
            color: #1a2980;
            border-bottom: 2px solid #26d0ce;
            padding-bottom: 10px;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .section-title i {
            color: #26d0ce;
        }

        .form-row {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
        }

        .search-box {
            display: flex;
            gap: 10px;
            margin-bottom: 25px;
        }

        .search-input {
            flex-grow: 1;
        }

        .search-btn {
            padding: 0 25px;
        }

        .client-list, .document-list {
            max-height: 400px;
            overflow-y: auto;
            border: 1px solid #eee;
            border-radius: 8px;
            padding: 5px;
        }

        .client-item, .document-item {
            background-color: #f9f9f9;
            border-radius: 8px;
            padding: 15px;
            margin-bottom: 10px;
            border-left: 4px solid #26d0ce;
            transition: background-color 0.2s;
        }

        .client-item:hover, .document-item:hover {
            background-color: #f0f8ff;
        }

        .client-name {
            font-weight: 700;
            color: #1a2980;
            margin-bottom: 5px;
        }

        .client-details {
            display: flex;
            justify-content: space-between;
            font-size: 0.9rem;
            color: #666;
            margin-bottom: 8px;
        }

        .client-actions {
            display: flex;
            gap: 10px;
            margin-top: 10px;
        }

        /* Документ */
        .document-container {
            display: none;
            margin-top: 30px;
            background-color: white;
            border-radius: 12px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        .document-header {
            text-align: center;
            margin-bottom: 30px;
            border-bottom: 2px solid #1a2980;
            padding-bottom: 20px;
        }

        .document-title {
            font-size: 2rem;
            color: #1a2980;
            margin-bottom: 10px;
        }

        .document-body {
            line-height: 1.6;
            margin-bottom: 30px;
        }

        .document-data {
            margin-bottom: 20px;
        }

        .data-row {
            display: flex;
            justify-content: space-between;
            margin-bottom: 8px;
            padding-bottom: 8px;
            border-bottom: 1px dashed #eee;
        }

        .data-label {
            font-weight: 600;
            color: #555;
        }

        .data-value {
            color: #333;
        }

        .document-footer {
            display: flex;
            justify-content: space-between;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 2px solid #eee;
        }

        .signature {
            width: 200px;
        }

        .signature-line {
            border-top: 1px solid #333;
            margin-top: 40px;
            width: 100%;
        }

        .signature-text {
            margin-top: 5px;
            font-size: 0.9rem;
        }

        .bank-seal {
            width: 180px;
            height: 180px;
            border: 3px solid #1a2980;
            border-radius: 50%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 15px;
            position: relative;
            background-color: white;
        }

        .seal-inner {
            border: 2px solid #ff0000;
            border-radius: 50%;
            width: 140px;
            height: 140px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 10px;
        }

        .seal-title {
            font-weight: 700;
            color: #ff0000;
            font-size: 1.1rem;
            margin-bottom: 5px;
        }

        .seal-text {
            font-size: 0.8rem;
            color: #333;
        }

        .document-actions {
            display: flex;
            gap: 15px;
            justify-content: center;
            margin-top: 30px;
        }

        /* Уведомления */
        .notification {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #4CAF50;
            color: white;
            padding: 15px 25px;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            display: none;
            z-index: 1000;
            animation: slideIn 0.5s ease;
        }

        @keyframes slideIn {
            from { transform: translateX(100%); opacity: 0; }
            to { transform: translateX(0); opacity: 1; }
        }

        .notification.error {
            background-color: #f44336;
        }

        .empty-message {
            text-align: center;
            color: #888;
            font-style: italic;
            padding: 30px 0;
        }

        footer {
            text-align: center;
            margin-top: 40px;
            color: #666;
            font-size: 0.9rem;
        }

        .role-badge {
            display: inline-block;
            padding: 3px 10px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 600;
            margin-left: 10px;
        }

        .role-employee {
            background-color: #1a2980;
            color: white;
        }

        .role-client {
            background-color: #26d0ce;
            color: white;
        }

        /* Сетка для сотрудника */
        .employee-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
        }

        @media (max-width: 768px) {
            .employee-grid {
                grid-template-columns: 1fr;
            }
            
            .header-content {
                flex-direction: column;
                gap: 15px;
            }
        }
    </style>
</head>
<body>
    <!-- Шапка сайта -->
    <header id="site-header">
        <div class="container">
            <div class="header-content">
                <div class="logo">
                    <i class="fas fa-university"></i>
                    <div>
                        <h1>MishOlya Bank</h1>
                        <p class="tagline">Надежный партнер в мире финансов</p>
                    </div>
                </div>
                <div class="user-info" id="user-info" style="display: none;">
                    <div class="user-avatar">
                        <i class="fas fa-user"></i>
                    </div>
                    <div>
                        <div class="user-name" id="user-display-name">Иван Иванов</div>
                        <div class="user-role">
                            <span id="user-role">Клиент</span>
                            <span class="role-badge" id="role-badge"></span>
                        </div>
                    </div>
                    <button class="btn-logout" id="btn-logout">
                        <i class="fas fa-sign-out-alt"></i> Выйти
                    </button>
                </div>
            </div>
        </div>
    </header>

    <!-- Контейнер для авторизации -->
    <div class="container" id="auth-container">
        <div class="auth-container">
            <div class="auth-box">
                <h2 class="auth-title">Вход в систему MishOlya Bank</h2>
                
                <div class="auth-tabs">
                    <button class="auth-tab active" data-tab="login">Вход</button>
                    <button class="auth-tab" data-tab="register-client">Регистрация клиента</button>
                    <button class="auth-tab" data-tab="register-employee">Регистрация сотрудника</button>
                </div>
                
                <!-- Форма входа -->
                <form id="login-form" class="auth-form active">
                    <div class="form-group">
                        <label for="login-username">Логин (email)</label>
                        <input type="text" id="login-username" placeholder="Введите ваш email" required>
                    </div>
                    <div class="form-group">
                        <label for="login-password">Пароль</label>
                        <input type="password" id="login-password" placeholder="Введите ваш пароль" required>
                    </div>
                    <button type="submit" class="btn">
                        <i class="fas fa-sign-in-alt"></i> Войти
                    </button>
                </form>
                
                <!-- Форма регистрации клиента -->
                <form id="register-client-form" class="auth-form">
                    <div class="form-group">
                        <label for="reg-client-fullname">ФИО</label>
                        <input type="text" id="reg-client-fullname" placeholder="Иванов Иван Иванович" required>
                    </div>
                    <div class="form-group">
                        <label for="reg-client-email">Email (будет использоваться как логин)</label>
                        <input type="email" id="reg-client-email" placeholder="example@mail.ru" required>
                    </div>
                    <div class="form-group">
                        <label for="reg-client-password">Пароль</label>
                        <input type="password" id="reg-client-password" placeholder="Придумайте надежный пароль" required>
                    </div>
                    <div class="form-row">
                        <div class="form-group">
                            <label for="reg-client-birthdate">Дата рождения</label>
                            <input type="date" id="reg-client-birthdate" required>
                        </div>
                        <div class="form-group">
                            <label for="reg-client-passport">Номер паспорта</label>
                            <input type="text" id="reg-client-passport" placeholder="4510 123456" required>
                        </div>
                    </div>
                    <button type="submit" class="btn">
                        <i class="fas fa-user-plus"></i> Зарегистрироваться как клиент
                    </button>
                </form>
                
                <!-- Форма регистрации сотрудника -->
                <form id="register-employee-form" class="auth-form">
                    <div class="form-group">
                        <label for="reg-employee-code">Код регистрации сотрудника</label>
                        <input type="text" id="reg-employee-code" placeholder="Введите код qwerty12345" required>
                    </div>
                    <div class="form-group">
                        <label for="reg-employee-fullname">ФИО</label>
                        <input type="text" id="reg-employee-fullname" placeholder="Петров Петр Петрович" required>
                    </div>
                    <div class="form-group">
                        <label for="reg-employee-email">Email (будет использоваться как логин)</label>
                        <input type="email" id="reg-employee-email" placeholder="employee@misholya.ru" required>
                    </div>
                    <div class="form-group">
                        <label for="reg-employee-password">Пароль</label>
                        <input type="password" id="reg-employee-password" placeholder="Придумайте надежный пароль" required>
                    </div>
                    <button type="submit" class="btn">
                        <i class="fas fa-user-tie"></i> Зарегистрироваться как сотрудник
                    </button>
                </form>
            </div>
        </div>
    </div>

    <!-- Основной контент (показывается после входа) -->
    <div class="container" id="main-content" style="display: none;">
        <!-- Интерфейс для сотрудника -->
        <div id="employee-interface" style="display: none;">
            <div class="employee-grid">
                <div class="section">
                    <h2 class="section-title"><i class="fas fa-search"></i> Поиск клиентов</h2>
                    <div class="search-box">
                        <input type="text" id="search-input" class="search-input" placeholder="Введите ФИО, паспорт или email...">
                        <button id="search-btn" class="btn search-btn"><i class="fas fa-search"></i> Найти</button>
                    </div>
                    <div class="client-list" id="client-list">
                        <div class="empty-message">Начните поиск клиентов</div>
                    </div>
                </div>

                <div class="section">
                    <h2 class="section-title"><i class="fas fa-plus-circle"></i> Создание кредитного документа</h2>
                    <form id="credit-form">
                        <h3 style="color: #1a2980; margin-bottom: 15px;">Данные клиента</h3>
                        <div class="form-group">
                            <label for="client-select">Выберите клиента</label>
                            <select id="client-select">
                                <option value="">Выберите клиента из списка</option>
                            </select>
                        </div>
                        <div class="form-group">
                            <label for="full-name">Или введите ФИО клиента</label>
                            <input type="text" id="full-name" placeholder="Иванов Иван Иванович">
                        </div>
                        <div class="form-row">
                            <div class="form-group">
                                <label for="birth-date">Дата рождения</label>
                                <input type="date" id="birth-date">
                            </div>
                            <div class="form-group">
                                <label for="passport">Номер паспорта</label>
                                <input type="text" id="passport" placeholder="4510 123456">
                            </div>
                        </div>
                        
                        <h3 style="color: #1a2980; margin: 25px 0 15px;">Условия кредита</h3>
                        <div class="form-group">
                            <label for="loan-amount">Сумма кредита (руб.)</label>
                            <input type="number" id="loan-amount" placeholder="100000" min="1000" max="10000000" required>
                        </div>
                        <div class="form-row">
                            <div class="form-group">
                                <label for="return-date">Дата возврата</label>
                                <input type="date" id="return-date" required>
                            </div>
                            <div class="form-group">
                                <label for="interest-rate">Процентная ставка (%)</label>
                                <input type="number" id="interest-rate" placeholder="12.5" min="1" max="50" step="0.1" required>
                            </div>
                        </div>
                        
                        <div class="form-group" style="margin-top: 25px;">
                            <button type="submit" class="btn" style="width: 100%;">
                                <i class="fas fa-file-contract"></i> Создать кредитный документ
                            </button>
                        </div>
                    </form>
                </div>
            </div>

            <div class="section" style="margin-top: 30px;">
                <h2 class="section-title"><i class="fas fa-file-invoice"></i> Все кредитные документы</h2>
                <div class="document-list" id="document-list">
                    <div class="empty-message">Кредитные документы будут отображаться здесь</div>
                </div>
            </div>
        </div>

        <!-- Интерфейс для клиента -->
        <div id="client-interface" style="display: none;">
            <div class="employee-grid">
                <div class="section">
                    <h2 class="section-title"><i class="fas fa-user-circle"></i> Мои данные</h2>
                    <div id="client-personal-info">
                        <!-- Данные клиента загружаются здесь -->
                        <div class="empty-message">Загрузка данных...</div>
                    </div>
                </div>

                <div class="section">
                    <h2 class="section-title"><i class="fas fa-file-contract"></i> Создать заявку на кредит</h2>
                    <form id="client-credit-form">
                        <div class="form-group">
                            <label for="client-loan-amount">Сумма кредита (руб.)</label>
                            <input type="number" id="client-loan-amount" placeholder="100000" min="1000" max="10000000" required>
                        </div>
                        <div class="form-row">
                            <div class="form-group">
                                <label for="client-return-date">Желаемая дата возврата</label>
                                <input type="date" id="client-return-date" required>
                            </div>
                            <div class="form-group">
                                <label for="client-interest-rate">Желаемая процентная ставка (%)</label>
                                <input type="number" id="client-interest-rate" placeholder="12.5" min="1" max="50" step="0.1" required>
                            </div>
                        </div>
                        
                        <div class="form-group" style="margin-top: 25px;">
                            <button type="submit" class="btn" style="width: 100%;">
                                <i class="fas fa-file-contract"></i> Отправить заявку на кредит
                            </button>
                        </div>
                    </form>
                </div>
            </div>

            <div class="section" style="margin-top: 30px;">
                <h2 class="section-title"><i class="fas fa-file-invoice"></i> Мои кредитные документы</h2>
                <div class="document-list" id="client-document-list">
                    <div class="empty-message">Ваши кредитные документы будут отображаться здесь</div>
                </div>
            </div>
        </div>

        <!-- Документ (общий для всех) -->
        <div class="document-container" id="document-container">
            <div class="document-header">
                <h2 class="document-title">КРЕДИТНЫЙ ДОГОВОР</h2>
                <p>г. Москва</p>
                <p id="document-date"></p>
            </div>
            
            <div class="document-body">
                <p>Настоящий кредитный договор заключен между:</p>
                <p><strong>Банк "MishOlya Bank"</strong>, именуемый в дальнейшем "Кредитор", с одной стороны, и</p>
                <p><strong id="document-client-name"></strong>, именуемый в дальнейшем "Заемщик", с другой стороны, о нижеследующем:</p>
                
                <div class="document-data">
                    <h3 style="color: #1a2980; margin: 20px 0 15px;">1. Данные Заемщика</h3>
                    <div class="data-row">
                        <span class="data-label">ФИО:</span>
                        <span class="data-value" id="doc-full-name"></span>
                    </div>
                    <div class="data-row">
                        <span class="data-label">Дата рождения:</span>
                        <span class="data-value" id="doc-birth-date"></span>
                    </div>
                    <div class="data-row">
                        <span class="data-label">Паспорт:</span>
                        <span class="data-value" id="doc-passport"></span>
                    </div>
                    
                    <h3 style="color: #1a2980; margin: 20px 0 15px;">2. Условия кредита</h3>
                    <div class="data-row">
                        <span class="data-label">Сумма кредита:</span>
                        <span class="data-value" id="doc-loan-amount"></span>
                    </div>
                    <div class="data-row">
                        <span class="data-label">Дата возврата:</span>
                        <span class="data-value" id="doc-return-date"></span>
                    </div>
                    <div class="data-row">
                        <span class="data-label">Процентная ставка:</span>
                        <span class="data-value" id="doc-interest-rate"></span>
                    </div>
                    <div class="data-row">
                        <span class="data-label">Общая сумма к возврату:</span>
                        <span class="data-value" id="doc-total-amount"></span>
                    </div>
                </div>
                
                <p style="margin-top: 25px;">Настоящий договор вступает в силу с момента его подписания и действует до полного исполнения обязательств Заемщиком.</p>
            </div>
            
            <div class="document-footer">
                <div class="signature">
                    <p><strong>Заемщик:</strong></p>
                    <div class="signature-line"></div>
                    <p class="signature-text">Подпись</p>
                </div>
                
                <div class="bank-seal">
                    <div class="seal-inner">
                        <div class="seal-title">MishOlya Bank</div>
                        <div class="seal-text">Печать банка</div>
                        <div class="seal-text" style="margin-top: 10px; font-size: 0.7rem;">Действительно до: <span id="seal-date"></span></div>
                    </div>
                </div>
                
                <div class="signature">
                    <p><strong>Представитель Банка:</strong></p>
                    <div class="signature-line"></div>
                    <p class="signature-text">Подпись</p>
                </div>
            </div>
            
            <div class="document-actions">
                <button id="print-document" class="btn"><i class="fas fa-print"></i> Печать документа</button>
                <button id="close-document" class="btn btn-secondary"><i class="fas fa-times"></i> Закрыть</button>
            </div>
        </div>
    </div>

    <footer>
        <div class="container">
            <p>© 2023 MishOlya Bank. Все права защищены. Данные хранятся локально в вашем браузере.</p>
            <p style="margin-top: 10px; font-size: 0.8rem;">Это демонстрационная система. Все данные клиентов и документов являются вымышленными.</p>
        </div>
    </footer>

    <div class="notification" id="notification"></div>

    <script>
        // Код для регистрации сотрудника
        const EMPLOYEE_REGISTRATION_CODE = "qwerty12345";
        
        // Инициализация данных в localStorage при первой загрузке
        document.addEventListener('DOMContentLoaded', function() {
            // Инициализация хранилищ, если они пусты
            if (!localStorage.getItem('mishOlyaUsers')) {
                localStorage.setItem('mishOlyaUsers', JSON.stringify([]));
            }
            
            if (!localStorage.getItem('mishOlyaClients')) {
                localStorage.setItem('mishOlyaClients', JSON.stringify([]));
            }
            
            if (!localStorage.getItem('mishOlyaDocuments')) {
                localStorage.setItem('mishOlyaDocuments', JSON.stringify([]));
            }
            
            // Проверяем, есть ли текущий пользователь в sessionStorage
            const currentUser = JSON.parse(sessionStorage.getItem('currentUser'));
            if (currentUser) {
                // Пользователь уже вошел, показываем основной контент
                showMainContent(currentUser);
            } else {
                // Показываем форму авторизации
                showAuthForm();
            }
            
            // Инициализация переключения вкладок авторизации
            initAuthTabs();
            
            // Инициализация форм авторизации
            initAuthForms();
            
            // Инициализация кнопки выхода
            document.getElementById('btn-logout').addEventListener('click', logout);
            
            // Установка минимальных дат
            const today = new Date().toISOString().split('T')[0];
            const birthDateInputs = document.querySelectorAll('input[type="date"][id*="birth"]');
            birthDateInputs.forEach(input => {
                input.setAttribute('max', today);
            });
            
            const tomorrow = new Date();
            tomorrow.setDate(tomorrow.getDate() + 1);
            const returnDateInputs = document.querySelectorAll('input[type="date"][id*="return"]');
            returnDateInputs.forEach(input => {
                input.setAttribute('min', tomorrow.toISOString().split('T')[0]);
            });
        });
        
        // Инициализация переключения вкладок авторизации
        function initAuthTabs() {
            const tabs = document.querySelectorAll('.auth-tab');
            tabs.forEach(tab => {
                tab.addEventListener('click', function() {
                    const tabId = this.getAttribute('data-tab');
                    
                    // Убираем активный класс у всех вкладок и форм
                    tabs.forEach(t => t.classList.remove('active'));
                    document.querySelectorAll('.auth-form').forEach(form => {
                        form.classList.remove('active');
                    });
                    
                    // Добавляем активный класс текущей вкладке и форме
                    this.classList.add('active');
                    document.getElementById(`${tabId}-form`).classList.add('active');
                });
            });
        }
        
        // Инициализация форм авторизации
        function initAuthForms() {
            // Форма входа
            document.getElementById('login-form').addEventListener('submit', function(e) {
                e.preventDefault();
                const email = document.getElementById('login-username').value.trim();
                const password = document.getElementById('login-password').value.trim();
                
                loginUser(email, password);
            });
            
            // Форма регистрации клиента
            document.getElementById('register-client-form').addEventListener('submit', function(e) {
                e.preventDefault();
                const fullName = document.getElementById('reg-client-fullname').value.trim();
                const email = document.getElementById('reg-client-email').value.trim();
                const password = document.getElementById('reg-client-password').value.trim();
                const birthDate = document.getElementById('reg-client-birthdate').value;
                const passport = document.getElementById('reg-client-passport').value.trim();
                
                registerClient(fullName, email, password, birthDate, passport);
            });
            
            // Форма регистрации сотрудника
            document.getElementById('register-employee-form').addEventListener('submit', function(e) {
                e.preventDefault();
                const code = document.getElementById('reg-employee-code').value.trim();
                const fullName = document.getElementById('reg-employee-fullname').value.trim();
                const email = document.getElementById('reg-employee-email').value.trim();
                const password = document.getElementById('reg-employee-password').value.trim();
                
                registerEmployee(code, fullName, email, password);
            });
        }
        
        // Вход пользователя
        function loginUser(email, password) {
            const users = JSON.parse(localStorage.getItem('mishOlyaUsers')) || [];
            const user = users.find(u => u.email === email && u.password === password);
            
            if (user) {
                // Сохраняем текущего пользователя в sessionStorage
                sessionStorage.setItem('currentUser', JSON.stringify(user));
                
                // Показываем основной контент
                showMainContent(user);
                showNotification('Вход выполнен успешно!');
            } else {
                showNotification('Неверный email или пароль', true);
            }
        }
        
        // Регистрация клиента
        function registerClient(fullName, email, password, birthDate, passport) {
            const users = JSON.parse(localStorage.getItem('mishOlyaUsers')) || [];
            const clients = JSON.parse(localStorage.getItem('mishOlyaClients')) || [];
            
            // Проверяем, существует ли уже пользователь с таким email
            const existingUser = users.find(u => u.email === email);
            if (existingUser) {
                showNotification('Пользователь с таким email уже существует', true);
                return;
            }
            
            // Создаем нового пользователя (клиента)
            const newUser = {
                id: 'user_' + Date.now(),
                fullName,
                email,
                password,
                role: 'client',
                registrationDate: new Date().toISOString()
            };
            
            // Создаем запись клиента
            const newClient = {
                id: 'client_' + Date.now(),
                userId: newUser.id,
                fullName,
                email,
                birthDate,
                passport,
                registrationDate: new Date().toISOString()
            };
            
            // Сохраняем пользователя и клиента
            users.push(newUser);
            clients.push(newClient);
            
            localStorage.setItem('mishOlyaUsers', JSON.stringify(users));
            localStorage.setItem('mishOlyaClients', JSON.stringify(clients));
            
            // Автоматически входим под новым пользователем
            sessionStorage.setItem('currentUser', JSON.stringify(newUser));
            showMainContent(newUser);
            showNotification('Регистрация клиента прошла успешно!');
        }
        
        // Регистрация сотрудника
        function registerEmployee(code, fullName, email, password) {
            // Проверяем код регистрации
            if (code !== EMPLOYEE_REGISTRATION_CODE) {
                showNotification('Неверный код регистрации сотрудника', true);
                return;
            }
            
            const users = JSON.parse(localStorage.getItem('mishOlyaUsers')) || [];
            
            // Проверяем, существует ли уже пользователь с таким email
            const existingUser = users.find(u => u.email === email);
            if (existingUser) {
                showNotification('Пользователь с таким email уже существует', true);
                return;
            }
            
            // Создаем нового пользователя (сотрудника)
            const newUser = {
                id: 'user_' + Date.now(),
                fullName,
                email,
                password,
                role: 'employee',
                registrationDate: new Date().toISOString()
            };
            
            // Сохраняем пользователя
            users.push(newUser);
            localStorage.setItem('mishOlyaUsers', JSON.stringify(users));
            
            // Автоматически входим под новым пользователем
            sessionStorage.setItem('currentUser', JSON.stringify(newUser));
            showMainContent(newUser);
            showNotification('Регистрация сотрудника прошла успешно!');
        }
        
        // Выход из системы
        function logout() {
            sessionStorage.removeItem('currentUser');
            showAuthForm();
            showNotification('Вы вышли из системы');
        }
        
        // Показать форму авторизации
        function showAuthForm() {
            document.getElementById('auth-container').style.display = 'block';
            document.getElementById('main-content').style.display = 'none';
            document.getElementById('user-info').style.display = 'none';
            document.getElementById('site-header').style.display = 'block';
            
            // Очищаем формы
            document.getElementById('login-form').reset();
            document.getElementById('register-client-form').reset();
            document.getElementById('register-employee-form').reset();
        }
        
        // Показать основной контент
        function showMainContent(user) {
            document.getElementById('auth-container').style.display = 'none';
            document.getElementById('main-content').style.display = 'block';
            document.getElementById('user-info').style.display = 'flex';
            document.getElementById('site-header').style.display = 'block';
            
            // Отображаем информацию о пользователе
            document.getElementById('user-display-name').textContent = user.fullName;
            document.getElementById('user-role').textContent = user.role === 'employee' ? 'Сотрудник банка' : 'Клиент банка';
            
            const roleBadge = document.getElementById('role-badge');
            roleBadge.textContent = user.role === 'employee' ? 'Сотрудник' : 'Клиент';
            roleBadge.className = 'role-badge ' + (user.role === 'employee' ? 'role-employee' : 'role-client');
            
            // Показываем соответствующий интерфейс
            if (user.role === 'employee') {
                document.getElementById('employee-interface').style.display = 'block';
                document.getElementById('client-interface').style.display = 'none';
                initEmployeeInterface();
            } else {
                document.getElementById('employee-interface').style.display = 'none';
                document.getElementById('client-interface').style.display = 'block';
                initClientInterface(user);
            }
            
            // Обновляем счетчики
            updateCounters();
        }
        
        // Инициализация интерфейса сотрудника
        function initEmployeeInterface() {
            // Загрузка всех клиентов и документов
            loadAllClients();
            loadAllDocuments();
            
            // Заполняем выпадающий список клиентов
            populateClientSelect();
            
            // Инициализация поиска клиентов
            document.getElementById('search-btn').addEventListener('click', searchClients);
            document.getElementById('search-input').addEventListener('keyup', function(e) {
                if (e.key === 'Enter') {
                    searchClients();
                }
            });
            
            // Инициализация формы создания кредитного документа
            document.getElementById('credit-form').addEventListener('submit', function(e) {
                e.preventDefault();
                createCreditDocument();
            });
            
            // Инициализация выбора клиента из списка
            document.getElementById('client-select').addEventListener('change', function() {
                const selectedClientId = this.value;
                if (selectedClientId) {
                    const clients = JSON.parse(localStorage.getItem('mishOlyaClients')) || [];
                    const client = clients.find(c => c.id === selectedClientId);
                    if (client) {
                        document.getElementById('full-name').value = client.fullName;
                        document.getElementById('birth-date').value = client.birthDate;
                        document.getElementById('passport').value = client.passport;
                    }
                }
            });
        }
        
        // Инициализация интерфейса клиента
        function initClientInterface(user) {
            // Загрузка данных клиента
            loadClientData(user);
            
            // Загрузка документов клиента
            loadClientDocuments(user.id);
            
            // Инициализация формы создания заявки на кредит
            document.getElementById('client-credit-form').addEventListener('submit', function(e) {
                e.preventDefault();
                createClientCreditRequest(user);
            });
        }
        
        // Загрузка данных клиента
        function loadClientData(user) {
            const clients = JSON.parse(localStorage.getItem('mishOlyaClients')) || [];
            const client = clients.find(c => c.userId === user.id);
            
            if (client) {
                const clientInfoDiv = document.getElementById('client-personal-info');
                clientInfoDiv.innerHTML = `
                    <div class="client-item">
                        <div class="client-name">${client.fullName}</div>
                        <div class="client-details">
                            <span><i class="far fa-calendar"></i> Дата рождения: ${formatDate(client.birthDate)}</span>
                            <span><i class="far fa-envelope"></i> Email: ${client.email}</span>
                        </div>
                        <div class="client-details">
                            <span><i class="far fa-id-card"></i> Паспорт: ${client.passport}</span>
                            <span><i class="far fa-calendar-check"></i> Клиент с: ${formatDate(client.registrationDate)}</span>
                        </div>
                    </div>
                `;
            }
        }
        
        // Загрузка всех клиентов (для сотрудника)
        function loadAllClients() {
            const clients = JSON.parse(localStorage.getItem('mishOlyaClients')) || [];
            displayClients(clients);
        }
        
        // Загрузка документов клиента
        function loadClientDocuments(userId) {
            const clients = JSON.parse(localStorage.getItem('mishOlyaClients')) || [];
            const client = clients.find(c => c.userId === userId);
            
            if (!client) return;
            
            const documents = JSON.parse(localStorage.getItem('mishOlyaDocuments')) || [];
            const clientDocuments = documents.filter(doc => doc.clientId === client.id);
            displayClientDocuments(clientDocuments);
        }
        
        // Загрузка всех документов (для сотрудника)
        function loadAllDocuments() {
            const documents = JSON.parse(localStorage.getItem('mishOlyaDocuments')) || [];
            displayDocuments(documents);
        }
        
        // Отображение списка клиентов
        function displayClients(clients) {
            const clientList = document.getElementById('client-list');
            
            if (clients.length === 0) {
                clientList.innerHTML = '<div class="empty-message">Клиенты не найдены</div>';
                return;
            }
            
            clientList.innerHTML = '';
            
            clients.forEach(client => {
                const clientItem = document.createElement('div');
                clientItem.className = 'client-item';
                
                clientItem.innerHTML = `
                    <div class="client-name">${client.fullName}</div>
                    <div class="client-details">
                        <span><i class="far fa-calendar"></i> ${formatDate(client.birthDate)}</span>
                        <span><i class="far fa-id-card"></i> ${client.passport}</span>
                    </div>
                    <div class="client-details">
                        <span><i class="far fa-envelope"></i> ${client.email}</span>
                        <span><i class="far fa-calendar-check"></i> ${formatDate(client.registrationDate)}</span>
                    </div>
                    <div class="client-actions">
                        <button class="btn btn-secondary" onclick="createDocumentForClient('${client.id}')" style="padding: 8px 12px; font-size: 0.9rem;">
                            <i class="fas fa-file-contract"></i> Создать договор
                        </button>
                    </div>
                `;
                
                clientList.appendChild(clientItem);
            });
        }
        
        // Отображение списка документов (для сотрудника)
        function displayDocuments(documents) {
            const documentList = document.getElementById('document-list');
            
            if (documents.length === 0) {
                documentList.innerHTML = '<div class="empty-message">Документы не найдены</div>';
                return;
            }
            
            documentList.innerHTML = '';
            
            documents.forEach(doc => {
                const documentItem = document.createElement('div');
                documentItem.className = 'document-item';
                
                // Рассчитываем общую сумму к возврату
                const totalAmount = calculateTotalAmount(doc.loanAmount, doc.interestRate);
                
                documentItem.innerHTML = `
                    <div class="client-name">${doc.clientName}</div>
                    <div class="client-details">
                        <span><i class="far fa-money-bill-alt"></i> Сумма: ${formatCurrency(doc.loanAmount)} руб.</span>
                        <span><i class="far fa-calendar-check"></i> Возврат: ${formatDate(doc.returnDate)}</span>
                    </div>
                    <div class="client-details">
                        <span><i class="fas fa-percentage"></i> Ставка: ${doc.interestRate}%</span>
                        <span><i class="far fa-calendar"></i> Дата договора: ${formatDate(doc.contractDate)}</span>
                    </div>
                    <div class="client-details">
                        <span><i class="fas fa-user"></i> Клиент: ${doc.clientName}</span>
                        <span><i class="fas fa-file-signature"></i> Общая сумма: ${formatCurrency(totalAmount)} руб.</span>
                    </div>
                    <div class="client-actions">
                        <button class="btn" onclick="viewDocument('${doc.id}')" style="padding: 8px 12px; font-size: 0.9rem;">
                            <i class="fas fa-eye"></i> Просмотр
                        </button>
                        <button class="btn btn-danger" onclick="deleteDocument('${doc.id}')" style="padding: 8px 12px; font-size: 0.9rem;">
                            <i class="fas fa-trash"></i> Удалить
                        </button>
                    </div>
                `;
                
                documentList.appendChild(documentItem);
            });
        }
        
        // Отображение документов клиента
        function displayClientDocuments(documents) {
            const documentList = document.getElementById('client-document-list');
            
            if (documents.length === 0) {
                documentList.innerHTML = '<div class="empty-message">У вас пока нет кредитных документов</div>';
                return;
            }
            
            documentList.innerHTML = '';
            
            documents.forEach(doc => {
                const documentItem = document.createElement('div');
                documentItem.className = 'document-item';
                
                // Рассчитываем общую сумму к возврату
                const totalAmount = calculateTotalAmount(doc.loanAmount, doc.interestRate);
                
                documentItem.innerHTML = `
                    <div class="client-name">Кредитный договор №${doc.id.substring(0, 8)}</div>
                    <div class="client-details">
                        <span><i class="far fa-money-bill-alt"></i> Сумма: ${formatCurrency(doc.loanAmount)} руб.</span>
                        <span><i class="far fa-calendar-check"></i> Возврат: ${formatDate(doc.returnDate)}</span>
                    </div>
                    <div class="client-details">
                        <span><i class="fas fa-percentage"></i> Ставка: ${doc.interestRate}%</span>
                        <span><i class="far fa-calendar"></i> Дата договора: ${formatDate(doc.contractDate)}</span>
                    </div>
                    <div class="client-details">
                        <span><i class="fas fa-file-signature"></i> Общая сумма: ${formatCurrency(totalAmount)} руб.</span>
                        <span><i class="fas fa-check-circle"></i> Статус: ${doc.status || 'Активен'}</span>
                    </div>
                    <div class="client-actions">
                        <button class="btn" onclick="viewDocument('${doc.id}')" style="padding: 8px 12px; font-size: 0.9rem;">
                            <i class="fas fa-eye"></i> Просмотр
                        </button>
                    </div>
                `;
                
                documentList.appendChild(documentItem);
            });
        }
        
        // Заполнение выпадающего списка клиентов
        function populateClientSelect() {
            const clients = JSON.parse(localStorage.getItem('mishOlyaClients')) || [];
            const clientSelect = document.getElementById('client-select');
            
            // Очищаем список, оставляя только первый элемент
            while (clientSelect.options.length > 1) {
                clientSelect.remove(1);
            }
            
            // Добавляем клиентов в список
            clients.forEach(client => {
                const option = document.createElement('option');
                option.value = client.id;
                option.textContent = `${client.fullName} (${client.passport})`;
                clientSelect.appendChild(option);
            });
        }
        
        // Поиск клиентов
        function searchClients() {
            const searchTerm = document.getElementById('search-input').value.toLowerCase();
            const clients = JSON.parse(localStorage.getItem('mishOlyaClients')) || [];
            
            if (!searchTerm.trim()) {
                displayClients(clients);
                return;
            }
            
            const filteredClients = clients.filter(client => 
                client.fullName.toLowerCase().includes(searchTerm) ||
                client.passport.toLowerCase().includes(searchTerm) ||
                client.email.toLowerCase().includes(searchTerm)
            );
            
            displayClients(filteredClients);
        }
        
        // Создание кредитного документа (для сотрудника)
        function createCreditDocument() {
            const currentUser = JSON.parse(sessionStorage.getItem('currentUser'));
            if (!currentUser || currentUser.role !== 'employee') return;
            
            // Получение данных из формы
            const clientSelect = document.getElementById('client-select');
            const selectedClientId = clientSelect.value;
            
            let client;
            const clients = JSON.parse(localStorage.getItem('mishOlyaClients')) || [];
            
            if (selectedClientId) {
                // Используем выбранного клиента
                client = clients.find(c => c.id === selectedClientId);
            } else {
                // Создаем нового клиента на основе введенных данных
                const fullName = document.getElementById('full-name').value;
                const birthDate = document.getElementById('birth-date').value;
                const passport = document.getElementById('passport').value;
                
                if (!fullName || !birthDate || !passport) {
                    showNotification('Заполните данные клиента или выберите существующего', true);
                    return;
                }
                
                // Проверяем, существует ли уже клиент с таким паспортом
                const existingClient = clients.find(c => c.passport === passport);
                
                if (existingClient) {
                    client = existingClient;
                } else {
                    // Создаем нового клиента
                    const newClient = {
                        id: 'client_' + Date.now(),
                        userId: null, // У клиента нет аккаунта
                        fullName,
                        email: '',
                        birthDate,
                        passport,
                        registrationDate: new Date().toISOString()
                    };
                    
                    clients.push(newClient);
                    localStorage.setItem('mishOlyaClients', JSON.stringify(clients));
                    client = newClient;
                }
            }
            
            const creditDetails = {
                loanAmount: parseFloat(document.getElementById('loan-amount').value),
                returnDate: document.getElementById('return-date').value,
                interestRate: parseFloat(document.getElementById('interest-rate').value)
            };
            
            // Создание документа
            const documentId = 'doc-' + Date.now();
            const contractDate = new Date().toISOString();
            
            const creditDocument = {
                id: documentId,
                clientId: client.id,
                clientName: client.fullName,
                clientPassport: client.passport,
                clientBirthDate: client.birthDate,
                ...creditDetails,
                contractDate: contractDate,
                createdBy: currentUser.id,
                createdByName: currentUser.fullName,
                status: 'Активен'
            };
            
            // Сохранение документа
            const documents = JSON.parse(localStorage.getItem('mishOlyaDocuments')) || [];
            documents.push(creditDocument);
            localStorage.setItem('mishOlyaDocuments', JSON.stringify(documents));
            
            // Обновление интерфейса
            loadAllClients();
            loadAllDocuments();
            populateClientSelect();
            
            // Показ созданного документа
            showDocument(creditDocument);
            
            // Очистка формы
            document.getElementById('credit-form').reset();
            clientSelect.value = '';
            
            // Показать уведомление
            showNotification('Кредитный документ успешно создан!');
        }
        
        // Создание заявки на кредит (для клиента)
        function createClientCreditRequest(user) {
            const clients = JSON.parse(localStorage.getItem('mishOlyaClients')) || [];
            const client = clients.find(c => c.userId === user.id);
            
            if (!client) {
                showNotification('Ошибка: данные клиента не найдены', true);
                return;
            }
            
            const creditDetails = {
                loanAmount: parseFloat(document.getElementById('client-loan-amount').value),
                returnDate: document.getElementById('client-return-date').value,
                interestRate: parseFloat(document.getElementById('client-interest-rate').value)
            };
            
            // Создание заявки (документа со статусом "Заявка")
            const documentId = 'req-' + Date.now();
            const contractDate = new Date().toISOString();
            
            const creditRequest = {
                id: documentId,
                clientId: client.id,
                clientName: client.fullName,
                clientPassport: client.passport,
                clientBirthDate: client.birthDate,
                ...creditDetails,
                contractDate: contractDate,
                createdBy: user.id,
                status: 'Заявка'
            };
            
            // Сохранение заявки
            const documents = JSON.parse(localStorage.getItem('mishOlyaDocuments')) || [];
            documents.push(creditRequest);
            localStorage.setItem('mishOlyaDocuments', JSON.stringify(documents));
            
            // Обновление интерфейса
            loadClientDocuments(user.id);
            
            // Показ созданной заявки
            showDocument(creditRequest);
            
            // Очистка формы
            document.getElementById('client-credit-form').reset();
            
            // Показать уведомление
            showNotification('Заявка на кредит успешно отправлена! Ожидайте решения банка.');
        }
        
        // Создание документа для выбранного клиента
        function createDocumentForClient(clientId) {
            const clients = JSON.parse(localStorage.getItem('mishOlyaClients')) || [];
            const client = clients.find(c => c.id === clientId);
            
            if (client) {
                // Устанавливаем выбранного клиента в списке
                document.getElementById('client-select').value = clientId;
                
                // Заполняем поля данными клиента
                document.getElementById('full-name').value = client.fullName;
                document.getElementById('birth-date').value = client.birthDate;
                document.getElementById('passport').value = client.passport;
                
                // Прокручиваем к форме
                document.getElementById('loan-amount').scrollIntoView({ behavior: 'smooth' });
                document.getElementById('loan-amount').focus();
                
                showNotification('Данные клиента загружены в форму. Заполните условия кредита.');
            }
        }
        
        // Просмотр документа
        function viewDocument(documentId) {
            const documents = JSON.parse(localStorage.getItem('mishOlyaDocuments')) || [];
            const doc = documents.find(d => d.id === documentId);
            
            if (doc) {
                showDocument(doc);
            }
        }
        
        // Отображение документа
        function showDocument(docData) {
            // Рассчитываем общую сумму к возврату
            const totalAmount = calculateTotalAmount(docData.loanAmount, docData.interestRate);
            
            // Заполнение данных в документе
            document.getElementById('document-client-name').textContent = docData.clientName;
            document.getElementById('document-date').textContent = `Дата составления: ${formatDate(docData.contractDate)}`;
            
            document.getElementById('doc-full-name').textContent = docData.clientName;
            document.getElementById('doc-birth-date').textContent = formatDate(docData.clientBirthDate);
            document.getElementById('doc-passport').textContent = docData.clientPassport;
            document.getElementById('doc-loan-amount').textContent = formatCurrency(docData.loanAmount) + ' руб.';
            document.getElementById('doc-return-date').textContent = formatDate(docData.returnDate);
            document.getElementById('doc-interest-rate').textContent = docData.interestRate + '%';
            document.getElementById('doc-total-amount').textContent = formatCurrency(totalAmount) + ' руб.';
            
            // Установка даты для печати (год от текущей даты)
            const sealDate = new Date();
            sealDate.setFullYear(sealDate.getFullYear() + 1);
            document.getElementById('seal-date').textContent = sealDate.toLocaleDateString('ru-RU');
            
            // Показываем документ
            document.getElementById('document-container').style.display = 'block';
            document.getElementById('document-container').scrollIntoView({ behavior: 'smooth' });
        }
        
        // Закрытие документа
        document.getElementById('close-document').addEventListener('click', function() {
            document.getElementById('document-container').style.display = 'none';
        });
        
        // Печать документа
        document.getElementById('print-document').addEventListener('click', function() {
            window.print();
        });
        
        // Удаление документа
        function deleteDocument(documentId) {
            if (confirm('Вы уверены, что хотите удалить этот документ?')) {
                let documents = JSON.parse(localStorage.getItem('mishOlyaDocuments')) || [];
                documents = documents.filter(doc => doc.id !== documentId);
                localStorage.setItem('mishOlyaDocuments', JSON.stringify(documents));
                
                // Обновляем интерфейс в зависимости от роли пользователя
                const currentUser = JSON.parse(sessionStorage.getItem('currentUser'));
                if (currentUser.role === 'employee') {
                    loadAllDocuments();
                } else {
                    loadClientDocuments(currentUser.id);
                }
                
                showNotification('Документ удален');
            }
        }
        
        // Обновление счетчиков
        function updateCounters() {
            const clients = JSON.parse(localStorage.getItem('mishOlyaClients')) || [];
            const documents = JSON.parse(localStorage.getItem('mishOlyaDocuments')) || [];
            
            // Можно добавить отображение счетчиков в интерфейсе
        }
        
        // Вспомогательные функции
        function formatDate(dateStr) {
            try {
                const date = new Date(dateStr);
                return date.toLocaleDateString('ru-RU');
            } catch {
                return dateStr;
            }
        }
        
        function formatCurrency(amount) {
            return amount.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g, ' ');
        }
        
        function calculateTotalAmount(loanAmount, interestRate) {
            const interest = loanAmount * (interestRate / 100);
            return loanAmount + interest;
        }
        
        function showNotification(message, isError = false) {
            const notification = document.getElementById('notification');
            notification.textContent = message;
            notification.className = 'notification' + (isError ? ' error' : '');
            notification.style.display = 'block';
            
            setTimeout(() => {
                notification.style.display = 'none';
            }, 3000);
        }
    </script>
</body>
</html>
