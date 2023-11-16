To recompile, follow these steps (write the following in the terminal):
flex Lexer.l
bison -dy Parser.y
gcc lex.yy.c y.tab.c
start a.exe