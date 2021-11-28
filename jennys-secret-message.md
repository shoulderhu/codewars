# Jenny's secret message

## Instructions
Jenny has written a function that returns a greeting for a user. However, she's in love with Johnny, and would like to greet him slightly different. She added a special case to her function, but she made a mistake.

## Solution
```bash
#!/bin/bash

echo "Hello, $1!"
if [[ "$1" == "Johnny" ]]
then
  echo "Hello. my Love!"
fi
```
