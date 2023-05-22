# microsoft_office
Installing Microsoft Office

Пошаговая установка:
Для начало нужно выполнилть обход российского геоблока, для этого сделаем след. шаги :
1) Откроем командную строку от имени администратора >> меню "Пуск" >> вводим "cmd" >> кликаем правой кнопкой мыши >> запуск от имени администратора
2) В командной строку вставляем следубщую команду >> reg add "HKCU\Software\Microsoft\Office\16.0\Common\ExperimentConfigs\Ecs" /v "CountryCode" /t REG_SZ /d "std::wstring|US" /f


