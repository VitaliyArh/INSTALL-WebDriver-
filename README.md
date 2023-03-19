# INSTALL-WebDriver-

Установка драйвера для браузера: Windows

Для установки откройте сайт https://sites.google.com/chromium.org/driver/ (старая версия сайта https://sites.google.com/a/chromium.org/chromedriver/downloads)
и скачайте ту версию ChromeDriver, которая соответствует версии вашего браузера. 
Чтобы узнать версию браузера, откройте новое окно в Chrome, в поисковой строке наберите: chrome://version/ и нажмите Enter. 
В верхней строчке вы увидите информацию про версию браузера.

Скачайте с сайта https://sites.google.com/chromium.org/driver/ (старая версия сайта https://sites.google.com/a/chromium.org/chromedriver/downloads) 
драйвер для вашей версии браузера. Разархивируйте скачанный файл.

Создайте на диске C: папку chromedriver и положите разархивированный ранее файл chromedriver.exe в папку C:\chromedriver.
Добавьте в системную переменную PATH папку C:\chromedriver. 
Как это сделать в разных версиях Windows, описано здесь: https://www.computerhope.com/issues/ch000549.htm. 


Самый простой способ для работы wedriver'а (chromedriver, geckodriver и т.п.), это перенести/скопировать его в папку, где находится python.exe 
(т.е. папку, куда установлен python). Тогда все без проблем работает как глобально, так и в virtualenv. 

PS Данный вариант 100% подходит для Windiws и тем, кто использует python для работы с webdriver.
