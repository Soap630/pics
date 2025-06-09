# pics
![image](https://github.com/user-attachments/assets/b2ee4e26-afc5-4166-b859-80d5cdd61573)

![image](https://github.com/user-attachments/assets/6c8aba2e-4614-4aba-93cb-a20991ae7286)

Every *SEARCH/REPLACE* edit must use this format:
1. The file path
2. The start of search block: <<<<<<< SEARCH
3. A contiguous chunk of lines to search for in the existing source code
4. The dividing line: =======
5. The lines to replace into the source code
6. The end of the replace block: >>>>>>> REPLACE

Here is an example:

```corcpp
### src/main.c
<<<<<<< SEARCH
#include <stdio.h>
#include <stdlib.h>
=======
#include <cstdio>
#include <cstdlib>
>>>>>>> REPLACE
```
