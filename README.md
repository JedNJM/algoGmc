# algoGmc

 
var sentence = "Ahla talel";
 
var length = 0;
var numWords = 0;
var numVowels = 0;

 for (var i = 0; i < sentence.length; i++) {
   length= length +1;
  if (sentence[i] == " ") {
     numWords = numWords +1 ;
  }

   if (sentence[i] == "a" || sentence[i] == "e" || sentence[i] == "i" || sentence[i] == "o" || sentence[i] == "u") {
     numVowels =  numVowels +1;
  }
}

 numWords = numWords+1;

 console.log("Length: " + length);
console.log("Number of words: " + numWords);
console.log("Number of vowels: " + numVowels);
