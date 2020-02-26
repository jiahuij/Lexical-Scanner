# Lexical-Scanner
c++
From other modules, users should be able to lexically analyze the BIOLA source program
(as a collection of lines of statements like what you have in your editor module)
by using the implementation of the lexical scanner module. By looking at the source program, 
the lexical scanner module should derive the information of
(i) for every statement of the source program, a collection of individual tokens (i.e. the basic lexical components) and 
(ii) for every statement of the source program, the category of these tokens. 
Users from other modules should be able to get such information back from the lexical scanner module. 
When requested, the lexical scanner module should also be able to display statement by statement, the individual tokens 
and their categories in each statement.
