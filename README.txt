Open fricas
)r Ktest_init.input
Should run all tests
For a smaller subset look at Ktest_init.input bottom.
You can comment out whatever test set you want or add your 
own.  Notice that I packaged the result in tests.log as 
FDA_factorCheck_poly
factorCheck_poly
Returning
[passed/failed, original polynomial, [list of returned factors]]

f_factorCheck
xf_factorCheck
Returning
[passed/failed, original polynomial, [list of asserted factors aprior],[list of returned factors]]

These could output to a seperate file if you are interested; the log file has a lot of extranious output.
Look at any of the test sets to see the template.
---------  
x7:FDA := (1+x*y)*x*(1+z*y)*(x*y*z-z*x*y);
factorCheck_poly(x7)
--------
and so on.....
