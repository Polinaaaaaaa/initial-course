# Домашнее задание

1. Пройти весь [курс](https://htmlacademy.ru/courses/38) по разметке текста.
2. Пройти [курс](https://htmlacademy.ru/courses/39) по разметке таблиц.
3. Создать файл __chess.html__ и разметить в нем шахматную доску размером 500х500, используя таблицы и атрибуты таблиц. Доска должна быть правильной, то есть, нижний левый угол для обоих игроков должен быть черным. Для заливки ячейки цветом используется атрибут __bgcolor__ со значением `black`, а для задания ширины и высоты ‒ атрибуты __width__ и __height__ соответственно.
![Внешний вид доски](https://github.com/MaximumStart/initial-course/blob/master/second-lesson/homework/chess.png)
4. Скопировать себе [файл __periodic_table.html__](https://github.com/MaximumStart/initial-course/blob/master/second-lesson/homework/periodic_table.html) и разметить в нем периодическую систему по примеру ниже:
![Внешний вид таблицы](https://github.com/MaximumStart/initial-course/blob/master/second-lesson/homework/periodic.png)

Для создания пустого места в первых трех периодах, рекомендую вспомнить об атрибуте __colspan__.
Цвета уже присутствуют в файле, они выделены в отдельный тег `<style>`. Это просто еще один способ подключения стилей на страницу. Всем цветам присвоены имена (`grey`, `olive`, `blue` и так далее). Для задания цвета элементу таблицы, мы используем атрибут __class__, например:

```html
  <td class="grey">Zn</td>
```
Для пустых элементов присутствует класс `not-an-element`, который используется аналогично. 
Если остались вопросы касательно работы атрибута __class__, то подробности можно посмотреть [здесь](https://webref.ru/html/attr/class).

Таблица цветов:

![Таблица цветов](https://github.com/MaximumStart/initial-course/blob/master/second-lesson/homework/colours_table.png)


---
#### Расчетное время выполнения: 2 - 4 часа.