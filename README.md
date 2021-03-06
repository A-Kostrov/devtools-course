# Спецкурс "Инструменты разработки"

Нижегородский Государственный Университет им. Н.И. Лобачевского  
Факультет ВМК, каф. МО ЭВМ

**License:** Creative Commons Attribution-Share Alike 3.0 
([CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0/))

## Ресурсы

 - [Таблица успеваемости](https://docs.google.com/spreadsheet/ccc?key=0AsBBkrQIoSbjdEdTUFRsaUw3LV92eVhwXzYtb0tZNHc#gid=5)
 - [Google-группа](<https://groups.google.com/forum/?hl=ru#!forum/devtools-course>)
 - Документация: <https://devtools.readthedocs.org>
 - Отчеты о построении: <https://travis-ci.org/UNN-VMK-Software/devtools-course>
 - Литература:
  - Дейв Томас, Энди Хант "Программист-прагматик"
  - Нил Форд "Продуктивный программист" 
    ([pdf](http://www.books.ru/books/produktivnyi-programmist-kak-sdelat-slozhnoe-prostym-a-nevozmozhnoe--vozmozhnym-fail-pdf-646592/?show=1))
  - Гудлиф "Ремесло программиста"
    ([pdf](http://www.books.ru/books/remeslo-programmista-praktika-napisaniya-khoroshego-koda-fail-pdf-646106/?show=1))
  - Стив Макконнелл "Совершенный код"
  - Kernighan & Pike, The Practice of Programming, Addison-Wesley, 1999, ISBN 020161586X
 - Дополнительная литература:
   - Джеффри Фридл "Регулярные выражения", 3-е издание
     ([pdf](http://www.books.ru/books/regulyarnye-vyrazheniya-3-e-izdanie-fail-pdf-626982/?show=1))
   - Ян Гойвертс, С. Левитан "Регулярные выражения. Сборник рецептов"
     ([pdf](http://www.books.ru/books/regulyarnye-vyrazheniya-sbornik-retseptov-fail-pdf-714878/?show=1))

## Описание лабораторных работ

  1. [Настройка окружения](#%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-1-%D0%9D%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-%D0%BE%D0%BA%D1%80%D1%83%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F)
  1. [Проектирование](#%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-2-%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)

### Лабораторная работа #1, "Настройка окружения"

  1. Вступите в группу [devtools-course](https://groups.google.com/forum/?hl=ru#!forum/devtools-course),
     которую мы будем использовать для общения. По всем вопросам необходимо
     обращаться туда. 
  1. Выберите себе тему из
     [списка](https://docs.google.com/spreadsheet/ccc?key=0AsBBkrQIoSbjdEdTUFRsaUw3LV92eVhwXzYtb0tZNHc#gid=3), 
     вписав свое имя.
  1. Зарегистрируйтесь на GitHub, предпочтительно использования аккаунта, из
     котого понятно ваше имя (опционально).
  1. Создайте форк нашего проекта: <https://github.com/UNN-VMK-Software/devtools-course>,
     клонируйте репозиторий к себе на рабочую машину. Все необходимые инструкции
     можно найти [здесь](https://help.github.com/articles/fork-a-repo).
  1. В подпапке `code` заведите папку со своим именем (`name-surname`), и
     поместите туда файл `README.md`. Это будет ваша wiki страничка в формате
     Markdown со всеми деталями о вашем проекте.
  1. Заполните свой `README.md` информацией, чтобы там были заголовки, списки и 
     желательно ссылки и стили (жирный, курсив). Стоит написать свое имя,
     тему лабораторной работы, раскрыть постановку задачи (предлагается сделать
     это самостоятельно). Просьба следить за грамматикой, файлы с ошибками
     будут возвращаться на доработку. Также просьба следить за корректностью 
     [синтаксиса Markdown](https://help.github.com/articles/github-flavored-markdown).
  1. Когда все будет готово, стоит проверить, правильно ли генерируется html
     на основе вашего Markdown. Для этого можно воспользоваться утилитой pandoc,
     или например текстовым редактором, который умеет рендерить html.
  1. После того как вы убедились, что файл выглядит хорошо, нужно будет
     сделать локальный коммит в Git, затем сделать push изменений в ваш форк на 
     GitHub.
  1. Когда ваши коммиты попадут на GitHub, нужно будет сделать 
     [pull-request](https://help.github.com/articles/using-pull-requests) в
     [центральный репозиторий](https://github.com/UNN-VMK-Software/devtools-course).
     Большая просьба в названии pull-request указать свою фамилию и номер
     лабораторной, например _"Корняков - Лабораторная работа #0"_.
  1. Если будут замечания к вашему коду, вы можете просто добавлять коммиты в
     свою ветку `master`, и пулл-реквест будет автоматически обновляться.

### Лабораторная работа #2, "Проектирование"

  1. Создайте в своей директории подпапки, подобно тому как это сделано 
     [здесь](https://github.com/UNN-VMK-Software/devtools-course/tree/master/code/kirill-kornyakov).
     В дальнейшем нужно будет строго придерживаться подобной раскладки файлов.
  1. Разработайте интерфейс класса (hpp-файл), и поместите его в папку
     `include`. 
     - Постарайтесь избегать лишних зависимостей в своем заголовочном файле.
       Также желательно предоставлять минималистичный интерфейс, позволяющий
       решить задачу, а все остальное поместить в `protected` и `private` секции
       класса.
     - Реализацию на этом этапе писать не нужно, вы можете это сделать чтобы
       проверить "жизнеспособность" API. В таком случае cpp-файл можно положить
       в директорию `src`, но ничего больше.
  1. Задокументируйте свой класс в стиле Sphinx, см. заготовку:
     [исходник](https://raw.github.com/UNN-VMK-Software/devtools-course/master/code/kirill-kornyakov/docs/simplecalc.rst),
     [результат](https://devtools.readthedocs.org/ru/latest/code/kirill-kornyakov/docs/simplecalc.html).
     - Необходимо создать rst-файл и поместить его в свою директорию `docs`.
     - Необходимо заполнить его, подробно описав (1) назначение класса, (2)
       сигнатуры публичных методов, (3) приведя примеры использования класса
       в пользовательском С++ коде.
     - Когда файл будет готов, его нужно будет включить в 
       [корневой файл](https://raw.github.com/UNN-VMK-Software/devtools-course/master/docs/source/index.rst)
       с документацией.
  1. Проверить корректность построения документации можно двумя способами:
     - Локально. Вам нужно будет [установить Sphinx](http://sphinx-doc.org/latest/install.html),
       после чего построить документацию,
       пользуясь файлами из директории 
       [docs](https://github.com/UNN-VMK-Software/devtools-course/tree/master/docs).
     - Онлайн. Вы можете индивидуально 
       [подключить](https://read-the-docs.readthedocs.org/en/latest/getting_started.html#import-your-docs)
       свой репозиторий к сервису ReadTheDocs. Тогда вы сможете увидеть свою
       документацию подобно тому, как это сделано для всего проекта
       [devtools](https://devtools.readthedocs.org).
  1. Когда заголовочный файл класса, и документация на него будут готовы, нужно
     снова прислать пулл-реквест. Большая просьба в названии указать свою
     фамилию и номер лабораторной, например _"Лабораторная работа #2"_.
