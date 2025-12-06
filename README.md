lab 1

D:\CD_Lab_MRC>flex lex1.l

D:\CD_Lab_MRC>gcc lex.yy.c

D:\CD_Lab_MRC>a.exe


lab -4
Compilation Steps:

flex lexer.l
bison -d -t simple.y
gcc lex.yy.c simple.tab.c
./a.exe
