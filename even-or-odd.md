# Even or Odd

## Instructions
Write a script that takes an integer as an argument and returns "Even" for even numbers or "Odd" for odd numbers.

## Solution
```bash
if (( $1 % 2 == 0 ))
then
  echo 'Even'
else
  echo 'Odd'
fi
```
