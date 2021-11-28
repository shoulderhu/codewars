# Reversed Words

## Instructions
Complete the solution so that it reverses all of the words within the string passed in.

Example:
```
"The greatest victory is that which requires no battle" --> "battle no requires which that is victory greatest The"
```

## Solution
```bash
IFS=' '
read -a ARRAY <<< "$1"

END=${#ARRAY[@]}
for ((i = END - 1; i >= 0; i--))
do
  echo -n ${ARRAY[$i]}
  if [[ $i -gt 0 ]]
  then
    echo -n ' '
  fi
done
```
