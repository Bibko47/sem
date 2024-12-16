# Лабораторная работа №1

![](./Images/maxresdefault.jpg)
### Цель: 


Познакомиться с системой верстки текстов TeX, языком верстки TeX, издательской системой LaTeX.Выполнить вариант индивидуального задания.

### Основные используемые команды:
* `multicols`- для разбиения страницы на части;
![](./Images/multicols.png)

* `itemize` - для создания списка;
![](./Images/itemize.png)

* `textbf, textit` - форматирование текста
![](./Images/textFormatting.png)

* $\coloneqq$` - специальные знаки (в данном случае ':=')


Другие сведения, и команды по работе с LaTeX можно посмотреть [здесь](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)

Пример выполненого задания: 

![](./Images/Снимок%20экрана%202024-11-11%20205035.png)
![](./Images/Снимок%20экрана%202024-11-11%20205110.png)


# Лабораторная работа 3

### Цель: 

Познакомиться с программами git, освоить их программные аргументы.

![](./Images/e1efc28e6b.png)


### Про технологию:

 <b>Git</b> - это распределенное программное обеспечение для управления версиями. Контроль версий - это способ сохранять изменения с течением времени без перезаписи предыдущих версий. Распределение означает, что каждый разработчик, работающий с репозиторием Git, имеет копию всего этого репозитория - каждый фиксацию, каждую ветку, каждый файл.

 [Git](https://git-scm.com/)

 [GitHub](https://github.com/)
 
 ### Основные команды:
 
 1. Проверка стасуса

 ```
 git status
 ```
2. Добавление файлов

```
git add .
```
3. Создание коммита

```
git commit -m "message"
```
4. Загрузка на определенную ветку в GitHub

```
git push origin <название ветки>
```
### Ресурс для обучения командам Git [здесь](https://habr.com/ru/articles/541258/)

### Вывод: 
Мы познакомились с программами Git, освоили их программные аргументы.



# Расчетная работа

## Тема

<strong> Разработка программы решения теоретико-графовой задачи. </strong>

### Цель

Ознакомиться с основами теории графов, способами представления графов, базовыми алгоритмами для работы с разными видами графов.

### Задача
Необходимо определить n-фактор для указанного графа.
Нужно найти колличество входящих рёбер в вершину и выходящих. Граф задается матрицей интидентности, данные которой вводит пользователь. Вывод работы программы выводится в консоль.

![](./Images/graph2(2).png)

#### Это пример ориентированного графа.
### Вариант
5.31 ми, ог (Найти n-фактор для указанного графа)
ми - матрица инцидентности.
ог - ориентированный граф.

## Ключевые понятия

Графовая структура (абсолютное понятие) - это такая одноуровневая реляционная струк-
тура, объекты которой могут играть роль либо вершины, либо связки:
<h3>– Вершина (относительное понятие, ролевое отношение);</h3>
<h1>– Связка (относительное понятие, ролевое отношение).</h1>