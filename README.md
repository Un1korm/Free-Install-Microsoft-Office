# Free-Install-Microsoft-Office
В данном репозитории мы подробно рассмотрим и скачаем `приложение-установщик Office(R)tool`, которое `позволяет бесплатно получить любую доступную версию Microsoft Office`. Однако данный метод не подойдет тем, кто предпочитает установить Microsoft Office и забыть о процессе активации, поскольку мы не будем приобретать лицензионный ключ. Вместо этого `мы воспользуемся бесплатной активацией, которую необходимо обновлять каждые 150 дней`. Это не так сложно, как может показаться, и в этом нет ничего страшного — всего лишь небольшая процедура, которую легко выполнить раз в полгода.


## Скачиваем приложение для установки Office(R)tool:
1. Заходим на англоязычный сайт [My Digital Life](https://forums.mydigitallife.net) в статью [Office(R)tool](https://forums.mydigitallife.net/threads/office-r-toolproject.84450/). На территории РФ сайт может быть заблокирован, поэтому стоит заходить с помощью VPN. Также, чтобы статья отображалась в полном ее содержании, нужно зарегистрироваться на сайте. Подробно читаем статью и изучаем ссылки на скачивание.
2. Перед тем как скачивать приложение нужно на время отключить антивирус на вашем ПК (Windows Defender, Kaspersky ...). Так как установка не официальным методом (обход оплаты лицензии Microsoft Office) считается подозрительным в системе вашего компьютера, а точнее антивируса. Разберем на примере Windows Defender (Windows 10):
   - Находим приложение-антивирус: Безопасность Windows -->
   ![](widows_defender/wd_app.jpg)
   - Защита от вирусов и угроз -->
   ![](widows_defender/wd_off_1.png)
   - Параметры защиты от вирусов и угроз (Управление настройками) -->
   ![](widows_defender/wd_off_2.png)
   - Защита в режиме реального времени (Отключить)
   ![](widows_defender/wd_off_3.png)
4. Office(R)tool для скачивания с любого сайта:
   - С моего [репозитория](https://github.com/Un1korm/Free-Install-Microsoft-Office/) ([OfficeRTool.v14.0-2025(2)](OfficeRTool.v14.0-2025(2).rar)), ПАРОЛЬ: `2025`
   - (https://www.mediafire.com/file/6wsko6huw9tbwnz)
   - (https://www.upload.ee/files/15790511/OfficeRTool.7z.html)
5. Скаченный файл (`OfficeRTool.7z` или `OfficeRTool.rar` или ...) находится под паролем. Как правило автор что-то изменяет в своем проекте или что-то добавляет, так что пароль меняет из года в год. Внимательно читаем раздел статьи `Read me` и находим глазками слово `Password`, рядом с ним должен находиться пароль от файла.
6. Какие пароли были раньше (по годам):
   - В 2023 пароль был: `2023`
   - ...
   - В 2025 пароль был: `2025`
   - ...
   - Уловили суть?
7. На компьютере создаем пустую папку, называем её `OfficeRtool` (в названии папки не должно быть никаких специальных символов и пробелов), в эту папку мы разархивируем `rar-архив`, который вы скачали ранее с вышеперечисленных сайтов. Теперь в этой папке будут храниться все файлы связанные с `Office(R)tool`.
8. Создаём пустую подпапку в папке `OfficeRtool` под названием `Office*` (где `*` — это год microsot office, который мы хотим себе установить. Например: Office2021). 
9. После того как скачали `rar-архив` и распаковали его в папку `OfficeRtool`, заносим папку в `белый список`/`исключение` нашего антивируса (Windows Defender, Kaspersky ...), чтобы антивирус не ругался на данную папку с приложением. Разберем на примере Windows Defender (Windows 10):
   - Находим приложение-антивирус: Безопасность Windows -->
   - Защита от вирусов и угроз -->
   - Параметры защиты от вирусов и угроз (Управление настройками) -->
   - Исключения (Добавление или удаление исключений) -->
   ![](widows_defender/wd_ignor_1.png)
   - Добавить исключение (Выбираем папку с файлом `Office(R)tool`)
   ![](widows_defender/wd_ignor_2.jpg)
10. В скаченном `rar-архиве` (с моего репозитория) после распаковки должен быть файл `Readme.pdf`, в котором рассказывается процесс установки `Office(R)tool` на английском языке. Вы можете воспользоваться им (файлом с инструкцией), используя встроенные переводчик выделенных слов в файле, или же продолжить дальше читать мою статью:
![](other/pdf_file_translate.png)


## Выбор и установка Microsoft Office:
1. Откройте файл в папке `OfficeRtool` под названием `OfficeRTool.cmd`
2. Ждём пока идёт загрузка...
3. Взаимодействие пользователя с приложение происходит исключительно на английском языке, поэтому стоит переключить клавиатуру с `русского` на `английский язык`.
4. После загрузки `приложение OfficeRtool` запросит согласие на её использование, нажимаем `да` = английскую букву `A`.
5. После это откроется главное меню приложения (на скриншоте представлена версия 2023 года):
   ![](other/install_activ_menu.png)
6. Набираем на клавиатуре букву `D` (выбираем пункт под буквой `D`) и нажимаем `Enter`:
    > "[D] DOWNLOAD OFFICE OFFLINE INSTALL PACKAGE" / "[D] Загрузить пакет для автономной установки Office" 
      ```cmd
      DownloadPath: "C:\Users\Admin\Downloads\OfficeRtool\Office2021" 
      Channel-ID: not set 
      Office build: not set 
      Language: ru-ru (Russian) 
      Architecture: x64 
      ________________________________________________________________ 
      Set new Office Package download path or press return for 
      Set Office Package Download Path = "C:\Downloads>
      ```
    - Переходим в проводник, где у нас находится главная папка `Office(R)tool`, и копируем путь к папке `Office*` (где `*` — это год приложения Microsoft Office, который мы хотим себе установить)
    - Вставляем этот путь сразу (без пробелов). Пример:
      ``` cmd
      Set Office Package Download Path = "C:\Downloads>C:\Users\Admin\Downloads\OfficeRtool\Office2021
      ```
    - Идёт процесс загрузки - загружается таблица со значениями:
      ```cmd
      Download path saved. 
      "Public known" standard distribution channels 
      Channel Name - Internal Naming Index-# 
      ________________________________________________________________ 
      Current (Retail/RTM) - (Production::CC) (1) 
      CurrentPreview (Office Insider SLOW) - (Insiders::CC) (2) 
      BetaChannel (Office Insider FAST) - (Insiders::DEVMAIN) (3) 
      MonthlyEnterprise - (Production::MEC) (4) 
      SemiAnnual (Business) - (Production::DC) (5) 
      SemiAnnualPreview (Business Insider) - (Insiders::FRDC) (6) 
      PerpetualVL2019 - (Production:LTSC) (7) 
      PerpetualVL2021 - (Production:LTSC2021) (8) 
      Manual_Override (set identifier for Channel-ID's not public known) (M) 
      Exit to Main Menu (X) 
      Set Channel-Index-# (1,2,3,4,5,6,7,8,M) or X or press return for Current >
      ```
    - Выбираем Microsoft Office, который нас интересует, и сразу пишем цифру, которая соответствует нашему выбору. Пример:
      ```cmd
      Set Channel-Index-# (1,2,3,4,5,6,7,8,M) or X or press return for Current >8
      ```
    - Высвечивается новая строка:
      ```cmd
      Set Office Build - or press return for 16.0.14332.20582>
      ```
    - Нажимаем `ENTER` (соглашаемся и подтверждаем) 
    - Пишем интересующий язык нашего интерфейса или нажимаем `ENTER` (подтверждаем предложенный выбор - `ru-ru / Russian`):
      ```cmd
      Set language[s] Value[s] - or press return for ru-ru>
      ```
    - Выбираем сколько разрядная операционная система у нашего компьютера (х64 или х86). Данную характеристику можно посмотреть в (Настройках Windows --> Система --> О программе)
    - Начнется загрузка, которая продлится 10-20 минут
    - После полной загрузки вас выбросит автоматически на главное меню приложения Office(R)tool
  
   
## Загрузка выбранных компонентов нашего Microsoft Office:
1. Набираем на клавиатуре букву `I` (выбираем пункт под буквой `I`) и нажимаем `Enter`:
   > "[I] INSTALL OFFICE FROM OFFLINE INSTALL PACKAGE-IMAGE" / "[I] Установить Office из оффлайн установить пакет-изображений"
   - Нам высвечивается ранее созданные нами офисы (по порядку 1 2 3 ...):
     ```cmd
     Set Office Package Download Path = "C:\Users\Admin\Downloads\OfficeRtool\Office2021"
     > 
     List of available installation packages 
     1 ru-ru_Office_PerpetualVL2021_x64_v16.0.14332.20582 
     Enter package number >
     ```
   - Выбираем офис, которые нас интересует, и напишем его цифру (Например, вводим цифру: `1`):
     ```cmd
     Set Office Package Download Path = "C:\Users\Admin\Downloads\OfficeRtool\Office2021"
     > 
     List of available installation packages 
     1 ru-ru_Office_PerpetualVL2021_x64_v16.0.14332.20582 
     Enter package number >1
     ```
   - Выбираем версию нашего офиса и пишем цифру (Например: `Office Professional Plus 2021 Volume`)
   - Выбираем, что нам нужно установить. Если хотим загрузить данный компонент офиса, то нажимаем `ENTER`. Если не хотим загружать данный компонент офиса, то нажимаем английскую букву `D`. Пример:
     ```cmd
     Disable Word install> "нажали ENTER" (БУДЕТ загружено) 
     Disable Excel install> D (НЕ БУДЕТ загружено)
     ```
 - После этого высвечивается таблица того, что мы выбрали и от чего мы отказались
 - Появляется надпись: 
   ```cmd
   "(ENTER) to install, (C) create an installation package, (R) start installation, (E) exit to the main menu >"
   "(ENTER) для установки, (C) создать пакет установки, (R) начать установку, (E) выйти в главное меню >"
   ```
 - Нажимаем/пишем `ENTER` (произойдет установка всех компонентов офиса, которые мы выбрали) 
 - Идёт загрузка...
 - После полной загрузки вас выбросит автоматически на главное меню приложения Office(R)tool


## Первая или повторная активация Microsoft Office:
1. Набираем на клавиатуре букву `K` (выбираем пункт под буквой `K`) и нажимаем `Enter`:
   > "[K] START OR RENEW KMS ACTIVATION" / "[K] Начать или продлить активацию KMS"
3. После загрузки Microsoft Office активирован и готов к работе
2. По истечению 150-и дней заходим в приложение и обновляем активацию этой же командой: `[K] START OR RENEW KMS ACTIVATION`
