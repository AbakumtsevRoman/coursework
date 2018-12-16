# Курсовая работа по дисциплине "Проектирование информационных систем"  
### Проектирование модели
* Определение требований к модели  
 Формальное определение объекта моделирования (процесса): визуализация данных при выполнение лабораторной работы   
 Формальное определение точки зрения: преподаватель  
 Формальное определение цели моделирования: спроектировать процесс связанный с визуализацией данных при выполнение лабораторной работы  
 Формальное определение темы курсового проекта (наименование информационной системы): -  
  
* Завершение идентификации всех потоков  
Построение ERD (диаграммы классов без атрибутов) для всех потоков    
![Потоки]()
* Завершение идентификации всех ролей  
Построение ERD (диаграммы классов без атрибутов) для всех ролей  
![Роли]()
* Завершение идентификации всех модулей  
Построение ERD (диаграммы классов без атрибутов) для всех модулей  
![Модули]()
  
### Разработка диаграмм в RAMUS  
Создание контекстной диаграммы и диаграммы уровня A0 "Визуализация данных в лабораторной работе" c 4 блоками:  
 ![A0](https://github.com/AbakumtsevRoman/coursework/blob/master/Скрины%20программы/01_A0.png)  
 ![IDEF0 A0](https://github.com/AbakumtsevRoman/coursework/blob/master/Скрины%20программы/02_A0.png)  
  
Декомпозиция автоматизируемых блоков до уровня, прямо сопоставляемого с программными модулями.  
* Представление блока A1 "Определить требования".  
![A1](https://github.com/AbakumtsevRoman/coursework/blob/master/Скрины%20программы/03_A1.png)  
* Представление блока A2 "Сформировать данные".  
![A2](https://github.com/AbakumtsevRoman/coursework/blob/master/Скрины%20программы/04_A2.png)  
* Представление блока A4 "Оформить отчет по лабораторной".  
![A4](https://github.com/AbakumtsevRoman/coursework/blob/master/Скрины%20программы/07_A4.png)    
  
Декомпозиция всех автоматизируемых блоков в DFD:  
* Представление блока A22 "Заполнить таблицу данными".  
В данном блоке показано заполнение таблицы информацией в Excel и сохранение в файл с данными  
![A22](https://github.com/AbakumtsevRoman/coursework/blob/master/Скрины%20программы/05_A22.png)  
* Представление блока A3 "Построить OLAP куб".  
В результате загрузки данных из файла с таблицой на выходе будет изображение OLAP куба на экране  
![A3](https://github.com/AbakumtsevRoman/coursework/blob/master/Скрины%20программы/06_A3.png)  
* Представление блока A43 "Заполнить отчет данными".  
В результате из имеющейся таблицы с данными и построенного OLAP куба, студент заполняет отчет по выполненной лабораторной  
![A3](https://github.com/AbakumtsevRoman/coursework/blob/master/Скрины%20программы/08_A43.png)  
 Определение типа каждого блока в DFD (экранная форма, печатная форма, модуль обработки): Так как целью данной работы является показать ход выполнения лабораторной работы, то все продемонстрированные блоки в DFD являются экранными формами.  
 Определение типа каждого хранилища в DFD (файл, таблица БД, структура в памяти, внешний сервис): Основным типом хранилищ в данной работе является структура в памяти компьютера используемого студентом. За исключением хранилищ в которых находятся таблица с данными (файл получаемый в результате работы в MS Excel) и отчета (файл получаемый в результате работы в MS Word).   
  
### Расчеты связанные с проектируемой модели
* Определение числовых показателей для цели потенциального проекта автоматизации  
формализации показателей качества для автоматизируемых процессов  
определение зависимости показателей качества от степени автоматизированности процессов  
расчет потенциального эффекта от выполнения проекта автоматизации  
  
* Определение числовых показателей для трудозатрат на разработку программных средств  
определение числа и сложности функциональных точек для модулей  
определение числа и сложности функциональных точек для хранилищ  
расчет сложности разработки методом FPA/IFPUG  
расчет трудозатрат на разработку "с нуля" методом COCOMO II  
  
* Завершение оформления курсового проекта  
созданый [документ в формате Word]()  
