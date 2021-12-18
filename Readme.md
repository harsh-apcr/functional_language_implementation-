compile lexer.x on terminal using 
alex lexer.x -o Lexer.hs
compiler grammar.y on terminal using 
happy grammar.y -o Parser.hs

-------------------------------------
All the file input/output functions are in main.hs

