Name: Pradosh Kharel

How long did the lab take?
20 Hours

Does your lab work as expected?
Yes as far as I know

Are there any issues?
Not as far as I know. Error handling is not that extensive so there
may be issues regarding that. I get a warning with waitpid when I
compile but I haven't noticed any issues yet

What design choices did you make and why?
The program wasn't built to handle many different cases. I stored local
variables in a malloced struct because it made sense since we were storing
key value pairs. A struct also allowed me to use an int value to see
if the malloced space was empty or full.

Did you make any assumptions about input or user interaction?

Comments have to marked with a # string. Simply having # in front of
a word isn't recognized as a comment. 

e.g #test is not a comment but # test is.

Yes. There can only be a maximum of 100 local variables at any given time. The commands must be less than 100 characters as well.

There is some error handling but it is not very extensive so the shell expects users to enter commands properly.


