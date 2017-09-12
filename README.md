# sendnudesjs
Printing the phrase "send nudes" using only expressions and operators using JavaScript.

This JavaScript returns a string using only expressions and operators. 

Here's how I printed the string:

I've read an article online (https://tutorialzine.com/2013/12/the-10-weirdest-programming-languages), it talks about 10 weirdest programming languages. It basically shows a list of esoteric programming languages (https://en.wikipedia.org/wiki/Esoteric_programming_language) and at the end of the list, it shows an example on how JavaScript is added to the list. The article also links you to a website (https://wtfjs.com/) that contains a list of "bugs" JavaScript can generate.

So, let's proceed on understanding why it generated the string "send nudes".

This expression "[![]]" returns false. This expression "[][[]]" returns undefined. When both expressions are concatinated using "+", it returns the string "falseundefined". Inorder to get each letter in the string, just access it like an array. So if we want to access letter "s" in the string, just do this expression "([![]]+[][[]])[(!+[]+!+[])+(++[[]][+[]])]". The index used to access the array returns a value of 3. To be able to get a value of 3 I've added the expression "!+[]+!+[]" and "++[[]][+[]]" which returns 2 + 1. The expression "[+[]]" returns an index of 0 in an array and post-increment it using ++ to get a value of 1. 

You can add different numbers to get the index of the letter in the sting. 

That's about it. You can do whatever you want with this script. Enjoy coding and exploring the weirdness of JavaScripti! :)
