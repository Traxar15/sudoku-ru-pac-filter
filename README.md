# Sudoku-ru-pac-filter
Для использования должны быть установлены следующие компоненты: на сервере ядро sudoku ([скрипт быстрой установки](https://github.com/SUDOKU-ASCII/easy-install)), клиент под андроид ([sudodroid](https://github.com/SUDOKU-ASCII/sudoku-android)) и клиент под windows или любую другую платформу из основного репозитория - [SUDOKU-ASCII](https://github.com/SUDOKU-ASCII/sudoku).

# Pac-фильтр
Ссылка:
```https://raw.githubusercontent.com/Traxar15/sudoku-ru-pac-filter/main/ru-sites.yaml```

<img width="450" height="450" alt="sudoku-ru-sites-qr" src="https://github.com/user-attachments/assets/b1ef8941-e767-4afb-9844-6dfb54abe588" />


# Добавление фильтра на клиент из основного репозитория
После скачивания архива, редактируем файл конфигурации клиента (config.json). По умолчанию там добавлены сайты для пользователей из Китая, поэтому меняем скрипт следующим образом:
![win](https://github.com/user-attachments/assets/4ce61530-ea6b-4996-a63a-547b30f231ef)

# Добавление фильтра на клиент Sudodroid
Установив приложение и добавив новый сервер, заходим в раздел "Proxy Mode" и вставляем ссылку(удобнее всего из qr-code):
![sudodroid](https://github.com/user-attachments/assets/ad521424-6384-4e93-aa96-4e51df57f600)

# Проверка фильтра
В запрет на проксирование специально добавлена сеть [2ip.ru](https://2ip.ru/), то есть при проверке у них ip-адреса должен быть показан ip-адрес вашего провайдера, а не сервера, на котором работает ядро sudoku.

