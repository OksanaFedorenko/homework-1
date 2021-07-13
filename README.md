# homework-1

### Из десятичной в двоичную систему счисления.

Дано число 1000, переведём его в двоичную систему.
Для этого число нужно последовательно делить на 2, каждый раз записывая остаток от деления, пока не останется остаток меньше или равный 1.

1. 1000/2. Остаток от деления равен 0, т.к. число чётное.  Пишем 0.
2. 500/2 - Остаток - 0.
3. 250/2. Остаток - 0.
4. 125/2. Остаток от деления - 1.  Дальше берем ближайшее чётное число к 125 (124) и делим его на 2.
5. 62/2.  Остаток - 0.
6. 31/2. Остаток - 1.
7. 15/2. Остаток - 1.
8. 7/2. Остаток - 1.
9. 3/2. Остаток - 1.
10. В конце остается 1.

Теперь записываем получившиеся цифры в обратном порядке - 1111101000. Это и есть число 1000 в двоичной системе.

### Из двоичной в десятичную систему счисления.

Переведем теперь число из двоичной системы в десятичную.

Дано число 1101101. Сначала нужно пронумеровать разряды справа налево начиная с 0. 

 6 | 5 | 4 | 3 | 2 | 1 | 0 
---|---|---|---|---|---|---
 1 | 1 | 0 | 1 | 1 | 0 | 1 
 
 Затем берем каждую цифру из двоичного числа и умножаем на количество двоек, соответствующее разряду. Результаты суммируем.
 
1\*2⁶ + 1\*2⁵ + 0\*2⁴ + 1\*2³ + 1\*2² + 0\*2¹ + 1\*2⁰ = 64+32+0+8+4+0+1 = 109.
 
