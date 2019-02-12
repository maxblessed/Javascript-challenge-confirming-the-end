# JAVASCRIPT CHALLENGE CONFIRMING THE END



in these challenge the function confirmEnding is use to confirm if the
 last word of the first input match the only word in the second input
 if it match the function will return true else it will return false
---
##CONFIRMING END function
---
function confirmEnding(firstInput,secondInput){

firstInput=firstInput.value.split(' ');

if(firstInput.length>0){
firstInput=firstInput[firstInput.length-1];
 if(firstInput===secondInput.value){

  return true;
 }else{
   return false;
 }
}

}
---
###THE SECOND INPUT MUST BE A WORD NOT SENTENCE
---
 THOMPSON YEBOAH
