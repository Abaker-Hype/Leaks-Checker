How to use.

1. Add both files to the main folder of the project.
2. Put '#include "leaks.h"' into the projects main header file
3. In the Program's/Testing File's Int Main() add check_leaks() right before the return (Also add it right before any exit() func is called)
4. Add leaks.c into the Program's/Testing File's gcc compile line;
5. Compile and Run
