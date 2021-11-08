# Cтуденческий конкурс (хакатон) МГТУ им. Н.Э.Баумана по разработке ускорителей вычислений на платформе Xilinx Alveo 

---

# Организаторы хакатона


|   <img src="assets/aleksei_popov.png" width="150"> |  <img src="assets/stanislav_ibragimov.plus.png" width="150">  |  <img src="assets/egor_dubrovin.png" width="150">  |
|: --------------------------------------- :|: --------------------------------------- :|
|   [Алексей Попов](mailto:alexpopov@bmstu.ru), <br> *МГТУ им. Н.Э.Баумана*   |   [Станислав  Ибрагимов](mailto:ibragimov@bmstu.ru)  <br>  *МГТУ им. Н.Э.Баумана*    |   [Егор Дубровин](mailto:dubrovin.en@ya.ru)  <br>  *МГТУ им. Н.Э.Баумана*    |
 

---
	

# Аннотация <a name="0"></a>

> Всем участникам предоставляется доступ к серверной платформе для реализации прототипа ускорителя вычислений. 

В ходе проведения практикума студенты знакомятся с различными аспектами разработки ускорителей вычислений на ПЛИС: знакомятся с методологией разработки ускорителей и архитектурой аппаратной платформы Xilinx Alveo U200, выполняют разработку проектов по индивидуальным вариантам, выполняют верификацию проектов как с помощью средств эмуляции, так и на аппаратном устройстве. Доступ к платформе Xilinx Alveo осуществляется через сервер разработки, на котором установлено все необходимое программное и аппаратное обеспечение.

Практикум состоит из трех этапов:

**Лабораторная работа №1** **Методологи****я** **разработки и верификации ускорителей вычислений на платформе Xilinx Alveo**

**Лабораторная работа №2. Разработка ускорителей вычислений средствами САПР высокоуровневого синтеза Xilinx Vitis HLS**

**Хакатон. Командная разработка концепции ускорителя вычислений**


## Содержание
	- [Лабраторная работа №1. Методология разработки и верификации ускорителей вычислений на  платформе Xilinx Alveo ](#1)
		- [Технология разработки ускорителей вычислений на модулей Xilinx Alveo](#1_1)
		- [Описание архитектуры разрабатываемого ускорителя](#1_2)
		- [Практическая часть](#1_3)
			- [Подключение к серверу Alveo](#1_3_1)
			- [Создание проекта VINC](#1_3_2)
			- [Сборка проекта](#1_3_3)
			- [Запуск программного обеспечения на хост-системе](#1_3_4)
			- [Индивидуальные задания](#1_3_5)
		- [Содержание отчета](#1_4)
		- [Контрольные вопросы](#1_5)
		- [Ссылки на дополнительную литературу](#1_6)
	- [Лабраторная работа №2. Разработка ускорителей вычислений средствами САПР высокоуровневого синтеза Xilinx Vitis HLS](#2)
		- [Методология ускорения вычислений на основе ПЛИС](#2_1)
		- [Разработка устройств ускорения на языке С/C++](#2_2)
		- [Описание ядра ускорителя на языке C/C++](#2_3)
		- [Оптимизация времени обработки и пропускной способности](#2_4)
			- [Конвейерная обработка циклов](#2_4_1)
			- [Разворачивание циклов](#2_4_2)
			- [Потоковая обработка](#2_4_3)
		- [Практическая часть](#2_5)
			- [Задание](#2_5_1)
			- [Подключение к серверу Alveo](#2_5_2)
			- [Создание проекта](#2_5_3)
			- [Сборка и отладка проекта в режиме программной эмуляции (Emulation-SW)](#2_5_4)
			- [Сборка и отладка проекта в режиме аппаратной эмуляции (Emulation-HW)](#2_5_5)
			- [Сборка и отладка проекта в режиме аппаратного исполнения (Hardware)](#2_5_6)
			- [Индивидуальные задания](#2_5_7)
		- [Содержание отчета](#2_6)
		- [Контрольные вопросы](#2_7)
		- [Ссылки на дополнительную литературу](#2_8)