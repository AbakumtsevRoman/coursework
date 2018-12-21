# Курсовая работа по дисциплине "Проектирование информационных систем"  
### Проектирование модели
* Определение требований к модели  
 Формальное определение объекта моделирования (процесса): Визуализация данных при выполнение лабораторной работы.  
 Формальное определение точки зрения: Преподаватель.  
 Формальное определение цели моделирования: Спроектировать процесс связанный с визуализацией данных при выполнение лабораторной работы.  
  
### Разработка диаграмм в RAMUS  
Создание контекстной диаграммы и диаграммы уровня A0 "Визуализация данных в лабораторной работе" c 4 блоками:  
 ![A0](https://github.com/AbakumtsevRoman/coursework/blob/master/Скрины%20программы/01_A0.png)  
 ![IDEF0 A0](https://github.com/AbakumtsevRoman/coursework/blob/master/Скрины%20программы/02_A0.png)  
  
Декомпозиция автоматизируемых блоков до уровня, прямо сопоставляемого с программными модулями, декомпозиция блоков в IDEF0:  
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
![A43](https://github.com/AbakumtsevRoman/coursework/blob/master/Скрины%20программы/08_A43.png)  
 Определение типа каждого блока в DFD (экранная форма, печатная форма, модуль обработки): Так как целью данной работы является показать ход выполнения лабораторной работы, то все продемонстрированные блоки в DFD являются экранными формами.  
 Определение типа каждого хранилища в DFD (файл, таблица БД, структура в памяти, внешний сервис): Основным типом хранилищ в данной работе является структура в памяти компьютера используемого студентом. За исключением хранилищ в которых находятся таблица с данными (файл получаемый в результате работы в MS Excel) и отчета (файл получаемый в результате работы в MS Word).   
  
### Диаграммы UML курсового проекта  
* Завершение идентификации всех потоков:  
Построенная ERD (диаграмма классов без атрибутов) для [всех потоков](https://github.com/AbakumtsevRoman/coursework/blob/master/ERD/потоки.txt)    
![Потоки](https://github.com/AbakumtsevRoman/coursework/blob/master/ERD/потоки.png)
* Завершение идентификации всех ролей:  
Построенная ERD (диаграмма классов без атрибутов) для [всех ролей](https://github.com/AbakumtsevRoman/coursework/blob/master/ERD/роли.txt)  
![Роли](https://github.com/AbakumtsevRoman/coursework/blob/master/ERD/роли.png)
* Завершение идентификации всех модулей:  
Построение ERD (диаграмма классов без атрибутов) для [всех модулей](https://github.com/AbakumtsevRoman/coursework/blob/master/ERD/модули.txt)  
![Модули](https://github.com/AbakumtsevRoman/coursework/blob/master/ERD/модули.png)
Диаграмма последовательностей  
![Последовательность](https://github.com/AbakumtsevRoman/coursework/blob/master/ERD/последовательность.PNG)  
Данная диаграмма последовательностей показывает работу создаваеммой программы.
  
### Расчеты связанные с проектируемой системой   
* Определение числовых показателей для трудозатрат на разработку программных средств  
Определение числа и сложности функциональных точек для модулей и для хранилищ:  
Для последующих расчетов создаваемой программы мы берем во внимание 3 модуля и 3 хранилища.  
Расчет сложности разработки методом FPA/IFPUG:  
![метод FPA/IFPUG](https://github.com/AbakumtsevRoman/coursework/blob/master/Расчет/2.PNG)  
Расчет трудозатрат на разработку "с нуля" методом COCOMO II:  
![метод COCOMO II](https://github.com/AbakumtsevRoman/coursework/blob/master/Расчет/3.PNG)
  
* Расчет эффекта от внедрения проектируемой системы
 Так как проектируемая система будет внедрена в лабораторные работы, то планируется что каждый студен будет пользоваться данной системой 1-2 раза в течении выполнения лабораторной. Примерное количество студентов на данные лабораторные равняется 60 человек.  
 При выполнение задания 60 студентами, было до 50% непонимания, после - 20%, и до 50% ошибок в решениях, после - 20%.  
 Рассмотрим случай когда студент совершил ошибку при выполнение задания, из-за чего у него происходит простой в времени, где только после вмешательства преподавателя он смог исправить возникшую проблему.  
 Без программы это составляло бы 1,5 часа непонимания ошибки + 30 минут проверки преподавателем + 1 час на исправление ошибки. Итого уходило бы лишних 3 часа работы.  
 С программой это примерно будет составлять 1 час непонимания ошибки + 30 минут на исправление. То есть всего 1,5 часа.  
 Разница между задержками выполнения лабораторной без программы и с её использованием равна 1,5 часа. Как следствие внедрение программы снижает время затрачиваемое на исправление ошибок.  

### Завершение оформления курсового проекта  
созданый [документ в формате Word]()  
