# Python-Game
Game develop with python
`pig_latin game`

This function accepts `english` word or sentence and convert it to 'pig_latin`.
This function make use of `while`,`for` and `if statement`



If the word begins with a vowel, add `way` to the end of the word. So `Air` becomes `Airway` and `eat` becomes `eatway`.

If the word begins with any other letter, then we take the first letter, put it on the end of the word, and then add `ay.` 

If a word starts with capital letter, the newly created word should start with a capital letter as well, 

while the previously capitalised first letter should become lowercase. Capitalisation of other letters should not be changed.

Thus, `python` becomes `ythonpay`, `PoS` becomes `OSpay`, and `Computer` becomes `Omputercay`.

This function should return the new string Pig Latin sentence instead of printing it.

Write a program that repeatedly asks the user to enter their sentences. Each time the user enters a sentence, 

the program should convert it to Pig Latin using the pig_latin function and then prints it out.

The program only exits after the user enters an empty string as an input.

