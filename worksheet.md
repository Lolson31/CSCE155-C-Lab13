
# CSCE 155E
## Lab 13.0 Worksheet

Name(s) and Login(s):



1. Examine the "search, find' section of the `main` function.  
   A key has been created that will match any team from California (CA).  
   Four searches are performed.

a) What is the result of the first search?
  null

b) What is the result of the second?
  Dodgers     82   79 (0.509) Los_Angeles     CA $104188999.00 $3472966.00

c) What is the result of the third?
  Padres      71   91 (0.438) San_Diego       CA $ 45869140.00 $1479649.00

d) What is the result of the fourth (number 1B)?
  Giants      86   76 (0.531) San_Francisco   CA $118198333.00 $4377716.00

e) Why did the same search produce different results for all
   three searches even though we called `bsearch` on the same
   inputs?
   It could have used different halves of the list

f) Observe that the fourth search (number 1B) was performed
   under the same ordering as the first search, so why did
   it produce a different result?
   It could be because the giants were the first instance of a CA team it ran into linearly
