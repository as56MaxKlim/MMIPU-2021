             
              Министерство образования Республики Беларусь
                          Учреждение образования 
            «Брестский государственный технический университет»
                            Кафедра ИИТ




                           Лабораторная работа №1 
                           Знакомство с Simulink


	                                	Выполнил:
                                                студент 3 курса
                                                группы АС-56
                                                Климович М. В.

                                                Проверил:
                                                Иванюк Д.С.



                                 Брест 2021

Цель: освоить основные операции, используемые при построении модели Simulink (перенос блоков, соединение, настройка параметров, запуск), построить модель вычислительного процесса на примере оценки суммы ряда.

Пример 1:

![Screenshot](../src/1.jpg)
Пример 2:

![Screenshot](../src/2.jpg)

1. В модели присутствуют 3 блока Memory. Указать их назначение и основные настройки.
Блок memory используется для хранения предыдущей переменной для расчета по формуле.
2. Что отображают блоки Display1 и Display2?
Display1 отображает последнюю переменную a(i)
Display2 отображает наше количество итераций – i
3. Предложить модель Simulink для расчета суммы ряда

![Screenshot](../src/3.jpg)
![Screenshot](../src/4.jpg)

Вывод: освоил основные оперции, используемые при построении модели Simulink, а так же построил модель для определенного случая. 
