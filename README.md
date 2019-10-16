# Exes-and-Ohs-
function XO(str) {
let Exes=0; let Ohs=0; 
for (i=0; i<str.length;i++){ 
  if (str[i].toUpperCase=='X'){Exes+=1} 
  if(str[i].toUpperCase=='O'){Ohs+=1}
 } 
if (Exes==Ohs) {console.log(true); return true} 
else {console.log(false); return false}
