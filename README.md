# SSOS-LAB-PROGRAMS
vtu lab programs for system software and operating systems lab (2015 cbcs scheme).


How to execute?

If you are using lex and yacc : 
    run the following commands on terminal/command prompt
      
      for lex :
      lex filename.l
      gcc lex.yy.c
        
      for yacc :
      yacc -d filename.y
      gcc y.tab.c lex.yy.c -ll
    
    
If you are using flex and bison : 
    run the following commands on terminal/command prompt
      
      for lex :
      flex filename.l
      gcc lex.yy.c
        
      for yacc :
      bison -d filename.y
      gcc filename.tab.c lex.yy.c -ll
