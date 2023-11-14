# LR6
## Лабораторная работа №6 Система контроля версий 
### Цель лабораторной работы: изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.
### 1. Клонирование в личный удалённый репозиторий

![image](Screenshots/1.png)

Рисунок 1 - Клонирование репозитория 

### 2. Добавление файла через интерфейс GitHub.
![image](Screenshots/2.png)

Рисунок 2 - Подтягивание изменений  

### 3. Получение истории операций для каждой из веток
![image](Screenshots/3.jpg)

Рисунок 3 - Получение истории операций 

### 4. Последние изменения
![image](Screenshots/4.jpg)

Рисунок 4 - Последние изменения

### 5. Слияние в ветку master, разрешив конфликт
![image](Screenshots/5.jpg)

Рисунок 5 - Слияние веток

Возник конфлик из-за файла с разным содержанием. Были внесены изменения в файл mergefile.txt для решения конфликта. 
![image](Screenshots/6.jpg)

Рисунок 6 - Содержимое конфликтующего файла

### 6. Удаление побочной ветки после успешного слияния.
![image](Screenshots/7.jpg)

Рисунок 7 - Удаление ветки 

### 7. Зафиксированные изменения
![image](Screenshots/8.jpg)

Рисунок 8 - Коммит изменения файла merdefile

![image](Screenshots/9.jpg)

Рисунок 9 - Коммит добавление важной информации

![image](Screenshots/10.jpg)

Рисунок 10 - Содержимое файла merdefile

![image](Screenshots/11.jpg)

Рисунок 11 - Коммит с исправлением слова 

### 8. Откат коммита
![image](Screenshots/12.jpg)

Рисунок 12 - Откат коммита 

![image](Screenshots/13.jpg)

Рисунок 13 - Получение истории операций в форматированном виде  

### 9. Создание ветки для отчета
![image](Screenshots/14.jpg)

Рисунок 14 - Создание ветки для отчета

### 10. Лог команд
1. git clone - Выполняет клонирование репозитория на компьютер;
2. git log - Просмотр истории коммитов;
3. git push - Используется для выгрузки содержимого локального репозитория в удаленный репозиторий;
4. git commit -m - Фиксирует изменения;
5. git pull - Выполняет выборку, а затем слияние или повторную базу для интеграции фиксаций в текущую локальную ветвь;
6. git add . - Сохраняет снимок текущего состояния проекта в истории коммитов;
7. git log --pretty=format:"%h - %ad | %an | %s" -  Выводит историю операций в форматированном виде;
8. git branch report - Создает новую ветку;
9. git checkout report - Используется для переключения ветки;
10. git show - Показывает последний сделанный коммит.

