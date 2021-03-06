# ProgrammersFolly

ProgrammersFolly is an app idea I had since I first started programming about a year ago in mid-2017. I was tired of making the same
programming errors, which were often innocent spelling mistakes (syntax error) or inconsistent variable names in statements (semantic
error). Larger, broader mistakes that were harder to spot, like storing a value of an incompatible data type, were logical errors I was
making that did not show up underlined in red in the IDE, since it compiled successfully but failed at runtime!

ProgrammersFolly shows all the most common programming errors in Java, and this first version is meant as more of a reference list to check back on after initial programming, to review (and hopefully catch!) the most common errors/illogical behavior not found by logcat.

I will be working on adding functionality to allow users to log how many of these errors they continually commit, in the hopes that less
errors will result in users' future programming! Ex. If someone is prone to instantiating a bunch of variables at the beginning of a class
definition, but fails to later provide an initial value for each variable, the runtime will throw an exception that you cannot use an un-initialized variable. 

If the user could record how many times they commit that same error, and have the app display how many times they
made that same error, the user will be less likely to make that error in the future and likely be a more consistent programmer overall.

Once I have a working version of ProgrammersFolly that can record the number of times a programmer makes each error, I will
add a feature that lets users sort the list in Ascending/Descending order of the number of times an error was made, making it easier to 
see which errors they are actually committing the most.
