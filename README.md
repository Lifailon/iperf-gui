# iperf-gui
Internet Performance Graphical User Interface - это графическая (gui WinForms) и руссифицированная (парсинг powershell) версия программы iperf, версии 3.1.3. IPAdmin - это первая версия программы.

Особенности:
Полноценная программа, для установки на компьютер используется пакет SFX с расположением в "program files" и ярлыком на рабочем столе исполняемого файла запуска программы (ps2exe).
Динамическое выпадающие меню списка серверов, при добавлении и удалении внесение изменений производится в файл conf;
Весь вывод программы руссифицирован по средствам Regex с возможностью сохранения вывода в файл txt для его передачи;
Все ключи программы имеют свои значения по умолчанию, которые можно изменить в gui - порт, кол-во потоков, тип передачи, кол-во трафика (тип времи измерения не используется);
Статус бар загрузки (может подвисать);
Удобные подручные средства для программы (открытие портов в локальном windows fw), проверка доступности удаленного сервера (ping) и любого порта (tnc);
Проверка статуса сервера производится по средствам отслеживания службы.

По вопросам и предложениям в Telegram @kup57
