if-else:
  
  To convert unmatched if statements into matched if-else statements by adding else statement to the particular if statement.
  
Loops:
  
   Converting for and do-while loops into while loops.
   
Syntax Tree:

  Creating a Syntax tree for the particular Arithmetic Expressions.
 
 BackPatching:
    
    Creating a symbol table from the input.
    
    Converting all the statements to their equivalent three address statements.
    
    Construct Basic blocks and flow-graphs from that.
    
    Construct DAG,copy assignment,constant assignment.


Compiling and executing code:
  
  lex file:lex filename.l
  
  yacc file:yacc -d filename.y
  
  g++ lex.yy.c y.tab.c -lfl
  
  ./a.out
