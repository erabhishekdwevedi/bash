# Check File Exists

If file exists
```
#!/bin/bash

FILE=./file
if [ -e "$FILE" ]; then
    echo "File exists"
else 
    echo "File does not exist"
fi 

```

If file doesn't exist

```
#!/bin/bash

FILE=./file
if [! -e "$FILE" ]; then
    echo "File doesn't exists"
else 
    echo "File exist"
fi 

```
