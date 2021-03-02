# Сканирование Lua скриптов на запросы к сети.

Данная функция сканирует **Lua** скрипт на наличие любых запросов в сеть по всем сетевым протоколам.

## Как это работает?

Приложение запускает файл с помощью **LuaJIT** в изолированной среде - чтобы скрипту даже обратиться к интернету не удалось.
Если попытка обращения будет - он заблокирует её и выведет в консоль.

## Как использовать?

Перетащите скрипт на файл «scanner.bat» и дождитесь результатов сканирования.
**Важно:** сканировать можно тольео файлы с расширением **.lua** и **.luac**!

![image](https://user-images.githubusercontent.com/79799705/109424675-3480d300-79ed-11eb-9b75-babcb297b6e3.png)

## Где скачать?
[Загрузите архив со приложением](https://github.com/BlastHackRU/anti-download-lua/raw/main/luajit.zip) - его исходный код открыт, вы можете ознакомиться с ним или даже модифицировать в папке **«luajit/jit»**, но это не главное. Распакуйте его в любую удобную для вас папку и воспользуйтесь инструкцией выше.

![image](https://user-images.githubusercontent.com/79799705/109424636-0dc29c80-79ed-11eb-9e22-555ef65020ba.png)
