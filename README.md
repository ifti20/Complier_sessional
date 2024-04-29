# Complier_sessional
It is a sample compiler project

cmd lines

1.  flex nri.l
2.  bison -d nri.y
3.  gcc lex.yy.c nri.tab.c -o comp
4.  comp
