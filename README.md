# Homework_L16 - Venv, Poetry и управление зависимостями проекта

- [Ссылка на занятие](https://school.qa.guru/pl/teach/control/lesson/view?id=334954978&editMode=0) 
- [Ссылка на репозиторий](https://github.com/qa-guru/qa_guru_python_4_17) 
- [Конспект лекций](https://github.com/qa-guru/knowledge-base/wiki/15.-Venv,-Poetry-%D0%B8-%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B7%D0%B0%D0%B2%D0%B8%D1%81%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D1%8F%D0%BC%D0%B8-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0) 


## Управление зависимостями проекта
- Что такое виртуальное окружение? Это изолированная среда для Python-проектов, в которой можно устанавливать зависимости (пакеты), не затрагивая глобальную систему Python и другие проекты.
- Что такое пакет? 	
  1.	Библиотека (набор модулей) с определённой функциональностью, которую можно устанавливать и использовать.
  2.	Или просто директория с файлом __init__.py, если говорить о структуре кода.
- Как Python управляет зависимостями?

## Виртуальные окружения
- pip - ставим пакеты
- venv - виртуальное окружение из коробки
- virtualenv - часть его стала venv. https://virtualenv.pypa.io/en/latest/index.html
- pipenv - объединяем virtualenv и pip
- https://github.com/pypa официальные инструменты для управления зависимостями

## Poetry
- https://python-poetry.org/
- pyproject.toml https://peps.python.org/pep-0621/

## Домашка
Создайте проект используя poetry. Заполните минимальную мета-информацию в pyproject.toml
В зависимостях должны быть: pytest, selene
В dev-зависимостях должен быть pylint

## Дополнительно
- https://github.com/pyenv/pyenv - управляем питонами
- https://pip.pypa.io/en/stable/topics/secure-installs/ - как сделать pip более безопасным
