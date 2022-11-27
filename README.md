# Bot_testing
   Тестирование бота Имя в телеграме @QAP_Convertbot

- При первом запуске теста Телеграм-бота вышли ошибки:

Traceback (most recent call last):

File "C:\Users\mvideo-\PycharmProjects\pythonProject13\exp\app1.py", line 3, in <module> from extensions1 import ExchangeException, Exchange
File "C:\Users\mvideo-\PycharmProjects\pythonProject13\exp\extensions1.py", line 3, in <module> from config import ModuleNotFoundError: No module named 'config'
  
Были исправлены ошибки в вкладке extensions и исправлена строчка на «from config1 import keys». Установлен пакет в PyCharm requests и PyTelegramBotAPI.

- Телеграм-бот запустился. При переводе валюты «доллар рубль 1», вышла ошибка «Что-то пошло не так с 'ЮэСДэ'». В вкладке «config» ошибки в названии валюты. Ошибка исправлена и бот показывает данные «доллар рубль 1».
  
- Проверен бот на ошибки. При вводе «рубль доллар 1 2 3» бот выводит «Ошибка пользователя. Введите команду или 3 параметра».
  
При вводе в боте «доллар доллар 1», выходит «Ошибка пользователя. Нельзя перевести одинаковые валюты доллар».
  
Бот работает. При некорректном вводе данных бот выводит сообщение, который указывает ошибки.  

 

