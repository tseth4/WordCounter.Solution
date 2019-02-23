# Track suggester

Count the words in any sentence

By Tristan Setha 02/15/18, update 02/22/19

## Description

A word counter that takes an input of a Word and a Sentence and outputs how many words are in the sentence!

## Setup/Installation Requirements

Cloning
Open terminal and $ cd into preferred destination of clone
Run the command $ git clone https://github.com/tristansetha/WordCounter.Solution
$ cd into WordCounter
$ dotnet restore
$ dotnet run
Open the path from "Now listening on: http://localhost:5000 in your favorite web browser
then 
$ mcs Program.cs Models/Word.cs; mono Program.cs

## Specs

|   Behavior                          | Input Example | Output Example |
| ------------------------------------|:-------------:| :-------------:|
|  user enters home and clicks the link to form | click link  | form |
|  user enters in a word input with no sentence   | apple | invalid input |
|  user enters in a sentence with not word | the apple | invalid inout |
|  user enters in not inputs | | invalid inpute |
|  User enters in just an alphabetic string (word),User enters in alphabetic string (sentence)  | apple, The apple tree has an apple |  Word: apple, Sentence: he apple tree has an apple, Count: 2  |
|  User enters in number or symbol in 'any' input | 4ppl&, the apple tree has an apple | invalid input |
|  if any words match the inputted word in sentence add one to counter (eg. sentence: The apple tree has an apple ) | apple | add 2 to counter; Count: 2 |
|  if no words match sentence (eg. sentence: The apple tree has an apple) |  zebra | (add 0 to counter) no words match; Count: 0 |


## Technologies Used

Mono, C#, .NetCore 1.1, HTML, Git, Visual Studio code

ask me anything!!! tristansetha@gmail.com

MIT

Copyright (c) 2019 Tristan Setha
