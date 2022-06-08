## Part 1. Установка ОС
* Установка Ubuntu 20.04 Server LTS без графического интерфейса 
* Проверяем версию Ubuntu командой `cat /etc/issue`<br>
![Версия Ubuntu](src/screen/part1.png)<br>*Версия Ubuntu*

## Part 2. Создание пользователя
* Создаём нового пользователя командой `sudo adduser new_hsiuayes`<br>
![Создание нового пользователя](src/screen/part2.png)<br>*Создание нового пользователя*
* Вызываем команду `sudo usermod -aG adm new_hsiuayes`<br>
![new_hsiuayes даны права администратора](src/screen/part2_1.png)<br>*new_hsiuayes даны права администратора*
* Вызываем команду `cat /etc/passwd` <br>
![Проверка создания пользователя](src/screen/part2_2.png)<br>*Проверка создания пользователя*