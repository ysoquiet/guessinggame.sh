# guessinggame.sh
Coursera

echo "[Welcome to Steven's Guessing Game]

echo "Let's Begin"

function ask {
  echo "Guess the number of files in the current directory."
  read "Guess"

if [[$1 -gt 60]] && [[$1 lt 150]] 
then
  echo "$1 is between 60 and 150"
 else 
 "You entered $1 not what I was looking for"
 
 
