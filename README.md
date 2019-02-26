# Protictor
An automatic corrector or PROMELA models

Usage: ./protictor <filename>.pml [-vN]
  
Performs corrections iteratively on the model, producing a new file for each fix.

Important:
Each statement must be on a separate line
There must be no active processes (init must run starting proceses)
This version does not support inline and #define.
  
  
