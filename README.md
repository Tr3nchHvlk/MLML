## MLML: Machine Learning Modelling Language
---
The MLML has a similar structural fashion to Assembly.

&lt;OPERATOR&gt; &lt;PARAMS&gt; {FOR &lt;VAL&gt; FROM &lt;SELECTION&gt;} {AS &lt;VAR&gt;}

**Examples:**

MUL INPUT[i] INPUT[i+1] INPUT[i+1] FOR i FROM INPUT.0 AS Y

COPY INPUT IX

MMUL IX Y Y

SUB Y OUTPUT LOSS