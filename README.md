# Летняя практика 2го курса 2022

## Статус

| ### | 02.06 | 04.06 | 06.06 | 08.06 | 10.06 | 02.06 |
| --- | ----- | ----- | ----- | ----- | ----- | ----- |
|  1  |       |       |       |       |       |       |
|  2  |       |       |       |       |       |       |
|  3  |       |       |       |       |       |       |

## Команды

| ###                                                           | C1             | C2         | C3         | Задача                                           |
| ------------------------------------------------------------- | -------------- | ---------- | ----------- | ------------------------------------------------ |
| [1](https://github.com/PodoprigoraIvan/Bridges_in_graph_Java) | Подопригора 3  | Пенкин 3   | Позолотин 3 | Поиск мостов в графе                             |
| [2](https://github.com/lexapech/sort-visualizer)              | Ибатов 5       | Печеркин 5 | Котов 5     | Сортировки: quicksort, bubble sort, bitonic sort |
| [3](https://github.com/karinotc/prim_algo_visualizer)         | Александрович  | Парфенов   | Куртова     | Минимальное остовное дерево: алгоритм Прима      |

Позолотин Котов Ибатов вопросы по Java

## План работы

- [x] **30.06** -- Вводное задание; Обсуждение проектов
- [ ] **02.07** -- Начало работы, согласование спецификации
  - [ ] Создан файл отчёта; 
  - [ ] Создан maven-проект;
  - [ ] В отчёте:
    - [ ] Заполнен титульный лист с постановкой задачи и сроками
    - [ ] Предоставлена постановка задачи
    - [ ] Описана команда и роли участников с разбиением задач
    - [ ] Написан раздел спецификацией с диаграммой сценариев использования
- [ ] **04.07** -- Прототип интерфейса
  - [ ] В отчёте:
    - [ ] Предоставлен скриншот интерфейса с подробным описанием возможных взаимодействий с ним на основании сделанной ранее диаграммы сценариев использования
    - [ ] Предоставлена диаграмма классов с отображением основных сущностей связанных с интерфейсом, структуре данных, алгоритму и взаимодействию между ними.
    - [ ] К диаграмме классов прилагается описание сущностей: какая за что отвечает, почему такие отношения, какие паттерны использованы.
  - [ ] В проекте:
    - [ ] Реализован интерфейс приложения на заглушках
    - [ ] Реализована структура данных и требующийся алгоритм
    - [ ] Реализованы тесты для структуры данных и алгоритму
- [ ] **06.07** -- Рабочий прототип
  - [ ] В отчёте:
    - [ ] Предоставлена диаграмма последовательности, отображающая процесс взаимодействия объектов интерфейса (например, канвы) с объектами структуры данных, алгоритма, включая промежуточные объекты.
    - [ ] К диаграмме прилагается пояснение: как и почему взамодействия именно такие, в какой момент происходят.
    - [ ] Описаны тестовые случаи: какие множества значений какие результаты ожидаются; негативные тесты, положительные тесты; обоснование полноты проведённого тестирования.
  - [ ] В проекте:
    - [ ] Реализована генерация данных: из файла, случайная, при помощи графического интерфейса.
    - [ ] Реализована кнопка "Показать результат" с выполнением и отображением итогового результата работы алгоритма.
- [ ] **08.07** -- Реализация пошагового  исполнения
  - [ ] В отчёте:
    - [ ] В отчёте представлена диаграмма состояний, описывающая процесс пошагового исполнения алгоритма.
    - [ ] К диаграмме прилагается пояснение: какие сущности меняются при переходах между состояниями, подробнее какие условия перехода между состояниями существуют.
    - [ ] Описаны тестовые случаи для сущностей, относящихся к сохранению состояний выполнения алгоритма, аналогично предыдущим.
    - [ ] Описан интерфейс взаимодействия с пошаговым выполнением алгоритма.
  - [ ] В проекте:
    - [ ] Элементы графического интерфейса, отвечающие за пошаговое выполнение (кнопки, лог) -- реализованы и корректно работают.
    - [ ] Реализованы структуры данных, отвечающие за пошаговое выполнение алгоритма.
    - [ ] Реализованы тесты структур данных, отвечающих за пошаговое выполнение алгоритма.
- [ ] **10.07** -- Итоговый отчёт, сборка проекта в jar архив
  - [ ] В отчёте написано заключение, всё пожелания исправлены
  - [ ] Программа работает корректно, собирается в исполняемый jar-архив при помощи maven из консоли.
- [ ] **12.07** -- Запасной день для защиты

## Технологии

- Java JDK 17
- Swing для GUI
- JUnit для тестирования
- Maven для сборки проекта
- IntelliJ IDEA в качетсве IDE

## Полезные книги

- "Java: The Complete Reference, Twelfth Edition 12th Edition" Herbert Schildt -- справочник по последнему JDK.
- "Core Java т.1 Основы" Кей Хорстманн -- хорошее и понятное описание использования Swing API для GUI.
- "Java Concurency in Practice" Brian Goetz -- многопоточное программирование на Java.
- "Modern Java in Action" Raoul-Gabriel Urma и др. -- описание некоторых новых возможностей последней Java.
- "Java Performance In-Depth Advice for Tuning and Programming" Scott Oaks -- детали работы JVM, JIT, профилирование и повышене производительности программ на Java.

## Важные ньюансы по репозиторию

- Настройте .gitignore: в репозитории только pdf отчёта в корне проекта, java-файлы исходников и pom.xml мавена. Никаких iml файлов IDEA, .class-файлов из out и прочего.

