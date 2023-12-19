# 🏃‍♂️Модуль фитнес-трекера
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

Программный модуль фитнес-трекера, который обрабатывает данные для трёх видов тренировок: бега, спортивной ходьбы и плавания и отображает результаты тренировок.

### __Возможности модуля__
- принимать от блока датчиков информацию о прошедшей тренировке,
- определять вид тренировки,
- рассчитывать результаты тренировки,
- выводить информационное сообщение о результатах тренировки.
  
### __Информационное сообщение включает данные__
- тип тренировки (бег, ходьба или плавание);
- длительность тренировки;
- дистанция, которую преодолел пользователь, в километрах;
- среднюю скорость на дистанции, в км/ч;
- расход энергии, в килокалориях.


### __Установка на локальном компьютере__
1. Клонируйте репозиторий
```
> git clone git@github.com:Lozhkin-pa/telegram_bot.git
```
2. Установите и активируйте виртуальное окружение
```
> python -m venv venv
> source venv/Scripts/activate  - для Windows
> source venv/bin/activate - для Linux
```
3. Установите зависимости
```
> python -m pip install --upgrade pip
> pip install -r requirements.txt
```
4. Запустите проект
```
> python homework.py
```

### __Технологии__
* [Python 3.2.0](https://www.python.org/doc/)
* [flake8 5.0.4](https://flake8.pycqa.org/en/latest/)
* [pytest 7.1.3](https://docs.pytest.org/en/7.4.x/)

### __Автор__
[Павел Ложкин](https://github.com/Lozhkin-pa)
