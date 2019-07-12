# printf
ft_printf() - реализация стандартного printf на Си.  

Реализованна большая часть спецификаторов, а именно:  
 - %c %s %p .  
 - %d %i %o %u %x %X with flags hh, h, l, ll .  
 - %f %e %g wtih flags l and L .  
 - %% .  

Все спецификаторы поддерживают флаги # 0 - + $ * и модификатор ширины и точности.  

Также есть возможность задавать цвет текста с помощью макросов (color.h).  

Для использования необходимо подключить в проект файл библиотеки libftprintf.a.  
