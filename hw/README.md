# Домашние задания

## 1 - ASM BigInteger mul&sub
По [адресу](http://github.com/sorokin/cpp-course) лежит пример двух программ на ассемблере. 
Программа `hello.asm` — это программа выводящая строку `Hello, world`.
В ней подробно прокомментирована каждая строчка.
Программа `add.asm` — это программа, которая выполняет сложение двух длинных чисел.

Вам необходимо разобраться в этих примерах и написать на их основе программы
выполняющие вычитание и умножение беззнаковых длинных чисел.

Для запуска тестов необходимо переместить скомпилированную
программу в папку `tests`, а затем запустить команду:
```
~ sudo bash run_tests.sh <название вашей программы> <mul/sub>
```