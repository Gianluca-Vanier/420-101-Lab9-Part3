------------------------------------------------------------------------
Super Calculator
Author: Hacker T. Largebrain
------------------------------------------------------------------------

This program implements a highly efficient calculating engine for
a pocket calculator. It includes a complete test rig to demonstrate
that the engine works as it should.


QUESTIONS:

22. 
Testing the addition operation.
The result is: 1
Testing the subtraction operation.
The result is: 5
All tests passed.

No i don't believe it because it doesn't tell me what tests were done.

23. It gives 7. It is the same result as the testAll. It does give the same answer as the previous attempt. It should always returm 7.

24. It always returns 5.

26.
Method called       displayValue        leftOperand         previousOperator
initial state       0                   0                   ' '
clear               0                   0                   ' '
numberPressed(3)    3                   0                   ' '
numberPressed(4)    34                  0                   ' '
equals()            -34                 0                   ' '
getDisplayValue     -34                 0                   ' '

27.
clear               0                   0                   ' '

Yes, it is in the same state.

30.
Method called       displayValue        leftOperand         previousOperator
clear()             0                   0                   ' '
numberPressed(9)    9                   0                   ' '
plus()              0                   9                   '+'
numberPressed(1)    1                   9                   '+'
minus()             0                   10                  '-'
numberPressed(4)    4                   10                  '-'
equals()            6                   0                   '-'

It should and does return 6.

