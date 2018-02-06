Problem 3

Psuedocode


Guessing game
get random number
user inputs number
loop
count number of guesses
if user number equals random number then print "congrats it took you" number of guesses "guesses"
else 
  if guess is less than number print "guess was too low"
  else print "guess was too high"
print guess again and go back to loop


run
num=getRandomNumber

for(x=1;x>1;x++)
{
value= input "value"
if (value==num){
  print "congrats it took you"+x+"guesses"
  x=0}
else if(value<num){
  print "guess was too low"}
else{
  print "guess was too high"}
}
print "game over"



