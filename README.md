# OPI_lab11
16.12.2022 0:50
Букач
Елизавета
Сергеевна
Факултет информационных технологий
ИСИТ
Дисциплина "Технологии разработки программного обеспечения"
курс 1, группа 2, подгруппа 1
МИНЕСТЕРСТВО ОБРАЗОВАНИЯ РЕСПУБЛИКИ БЕЛАРУСЬ
БЕЛОРУССКИЙ ГОСУДАРСТВЕННЫЙ ТЕХНОЛОГИЧЕСКИЙ УНИВЕРСИТЕТ
Факультет Информационных Технологий
Кафедра Информационные системы и технологии







Лабораторная работа №6
Отчёт

                                                                            Букач Елизавета Сергеевна
                                                                             Студентка 1-го курса,
                                                                             Группа 2, подгруппа 1,
                                                                             Дисциплина
                                                                             «Технологии разработки 
                                                                             программного обеспечения»


Минск, 2022
1.Псевдокод
НАЧАЛО
ВВОД Х
ЕСЛИ (Х >= 0x41 && Х <= 0x5D)
{	ТО
ЕСЛИ (х >= 0x61 && х <= 0x7A)
{	ТО
ВЫВОД ‘x’-‘X’
}
	ИНАЧЕ
	{
		ВЫВОД ошибка
	}
}
ИНАЧЕ
{
	ВЫВОД ошибка
}
КОНЕЦ

Словесное описание
1.начало
2.ввод Х
3.если Х >= 0x41 && Х <= 0x5D, то переходим к п.4 иначе переход к п.7
4.ввод х
5.если х >= 0x61 && х <= 0x7A,то переходим к п.6 иначе переходим к п.7
6. вывод ‘х’-‘Х’ и переходим к п.8
7.вывод ошибки и переходим к п.8
8.конец










 
2.Псевдокод
НАЧАЛО
ВВОД Y
ЕСЛИ (Y>='А' && Y<='Я')
{	
	ВВОД у
ЕСЛИ (у>='а' && y<='я')
{
ВЫВОД ‘y’-‘Y’
}
	ИНАЧЕ
	{
		ВЫВОД ошибка
	}
}
ИНАЧЕ
{
	ВЫВОД ошибка
}
КОНЕЦ

Словесное описание
1.начало
2.ввод Y
3.если Y>='А' && Y<='Я', то переходим к п.4 иначе переход к п.7
4.ввод у
5.если у>='а' && y<='я',то переходим к п.6 иначе переходим к п.7
6. вывод ‘y’-‘Y’ и переходим к п.8
7.вывод ошибки и переходим к п.8
8.конец

 
2.Псевдокод
НАЧАЛО
ВВОД  z
ЕСЛИ (z>='А' && z<='Я')
{	
	z >= 0x30 && z <= 0x39
}
ИНАЧЕ
{
	ВЫВОД ошибка
}
КОНЕЦ

Словесное описание
1.начало
2.ввод z
3.если z>='А' && z<='Я', то переходим к п.4 иначе переход к п.5
4. вывод z и переход к п.6
5.вывод ошибки и переход к п.6
6.конец

 
																																																					     					1																																																	     да				нет																													  															    2																					да			нет																			нет			         да																																																																				          да			   нет																																				 													  															 3																																											да			нет																																																																				 													 																											   4																																																															



	
ПСЕВДОКОД
НАЧАЛО
ВВОД S
ЕСЛИ S=1{
ВВОД B
ЕСЛИ(B>=0x41B<=0x5D)
{
ВЫВОД ‘b’-‘B’
}
	ИНАЧЕ
	{
		ВЫВОД ошибка
	}
}
ИНАЧЕ
{
	ВЫВОД ошибка
}
КОНЕЦ
}
ЕСЛИ S=2{
ВВОД 
ЕСЛИ (Y>='А' && Y<='Я')
{	
	ВВОД у
ЕСЛИ (у>='а' && y<='я')
{
ВЫВОД ‘y’-‘Y’
}
	ИНАЧЕ
	{
		ВЫВОД ошибка
	}
}
ИНАЧЕ
{
	ВЫВОД ошибка
}
КОНЕЦ
}
ЕСЛИ S=3{
ВВОД  c
ЕСЛИ (c >= 0x30 && c <= 0x39)
{	
	ВЫВОД c-0;
}
ИНАЧЕ
{
	ВЫВОД ошибка
}
КОНЕЦ





