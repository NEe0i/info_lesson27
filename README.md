# info_lesson27
1. В числах со знаком старший бит (знаковый бит) используется для указания знака числа - 0 для положительных чисел и 1 для отрицательных чисел. В числах без знака все биты отводятся для представления самого числа, и они могут принимать только неотрицательные значения
2. количество чего-либо
3. прямым кодом где каждый бит в таком числе отображает определенную степень двойки (от 2^0 до 2^(n-1)), и значение числа получается путем сложения всех этих степеней двойки
4. в 2, в 4, в 2^n раз
5. (2^K - 1)
6. отбрасывает старшие разряды результата, оставляя только младшие разряды
7. потому что старший бит то естоь знаковый бит в отрицательных числах отводится для обозначения знака, а не для представления значения числа. Это приводит к смещению диапазона значений в отрицательную сторону
8. нет
9. можно инвертировать все биты положительного числа и затем прибавить к нему единицу, чтобы получить дополнительный код этого числа
10. так как они все основаны на применении операции инверсии и операции сложения к положительному числу
11. -2^(K-1)
12. Переполнение может возникнуть при сложении двух отрицательных чисел и в этом случае знак результата будет положительным. Например, если сложить -2 и -3, то получится -5, что превышает допустимый диапазон отрицательных чисел
13. олучится обратный код числа с добавлением к младшему разряду единицы
14. Если старший то есть знаковый разряд числа, записанного в прямом коде, равен 0, то число положительное и никаких преобразований не делается
15. заменить операцию вычитания на операцию сложения, сделать операции сложения и вычитания одинаковыми для знаковых и беззнаковых чисел, что упрощает архитектуру ЭВМ
16. компьютере используется сложение с дополнительным кодом вычитаемого

ЗАДАЧИ

1. 2^16 = 65536, 2^24 = 16777216
2. 4, 254
3. 3
4. –32767
5. 1111 1111, 1111 0110, 1001 1100
6. 1000 0001, 1000 1010, 1110 0100
7. 8016: 80, 90, A1, CC, F0, FF
8. макс 2^K‐1 ‐1, мин –2^K‐1
9. –126
10. 7! = 5040; 8! = –25216
