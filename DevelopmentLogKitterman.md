The first day of working on our project. Today me and Carson started writing a class that can recognize Ruby code. If the inputted code is not legit ruby code, it screams at you and throws some exceptions. I am also starting to relearn ruby. The toughest part about it is that in Ruby, for loops are nowhere similar to those in Java. The while loops are also pretty crazy. We'll need to implement the whole loop syntax in an "if" statement, and if it is ever so slightly wrong, we'll throw an exception and reprompt the user. There are also a lot more loops and statements in Ruby, so that's more that can go wrong in our program. We'll have to save their whole input as a string then save several ints and strings and use .split() method then check each element to see if it matches the syntax we've written. 


2/11/16
Today the battle continues. Ruby is a stupid piece of garbage because half of it doesn't make any sense. Even Git seems to be better. At least in Java you don't have to put a dollar sign before every single variable. Alas, I have also started writing the first method of our project. It recognizes loops in ruby and tells the user what they should write in their Java compiler that they have downloaded maybe. It's pretty functional, but you have to be 100 percent correct in your code writing. If you deviate from the standard at all, the code will print "Nope." and then end itself. I think this really encourages people to get better at the language they are writing in(Ruby). I will continue writing the program until it is more user friendly and accepts deviations from the norm. It will be hard though, as I'll have to write if() 98504783246823974 times. It will probably be worth it though because this is a really good program and will help a lot of people in their struggles.

2/19/16
Trying to program a project that recognizes the entirety of Ruby was definetely a bad idea. We can't do it at our specified deadline so we changed it. The rest of the class I was writing our new deliverable. It will only recognize the loops and statements in Ruby. It's going to be much easier. We also changed the second deliverable to our original first deliverable that recognizes all of Ruby. So far the program is going well. It can recognize while loops, for loops, and until loops. Implementing Ruby into Java was a lot easier than I thought it would be. Basically I need to write code that accepts basic syntax for Ruby and checks it against things that are already written. It can also recognize break statements, retry statements and redo statements. It's working pretty well so far, we just need to implement the rest of the loops and statements.


2/26/16 
Today we have finished and turned in our first deliverable. It is working pretty well, the only broken thing is the until loop tester. We have no idea how to make our translate() method read more than one line. This is okay though, the rest is good. The other checks read the first line to see if it is the correct loop. Then it outputs what you should write in java, assuming it was in Ruby when you typed it. The other method is a filewriter does stuff. You input the name of your file, the code checks to see if you have that file on your PC, converts it to java using the translate() method(well, only the loops as of now), and prints out a new file that has been converted. We're aiming to be able to read all of your file, then with the next deliverable be able to convert all that to java. This is not going to be that hard, just a bunch of switches and if-else if-else statements. Maybe a for loop to go through your entire file in one fell swoop.

3/4/16
Today working on the project went well. We are starting to write the implementation for recognition of the entire ruby language. We are going to have to use for loops for whenever someone wants to do a statement more than once. We'll have them input a number of times they want to do something, then iterate the statement that many times. Also the filereader is good. It accepts a file, reads it, and tries to convert it to java. Ruby is pretty compact, so we're going to give them back a file that is a lot larger. The scope of variables in ruby is also pretty hard to understand. Basically everything is global unless you put it in some sort of block? Whatever, at least you don't need a semicolon at the end of every line :). The loop converter is fully functional now, because I took the time over the weekend to fix it.


3/11/16
Working was good, we made lots of progress. At least in understanding how Ruby works and the translations we are going to need to make. We are also going to run a single filewriter. It reads the file one line at a time, then prints out the appropriate java code to a different file. This is going to run pretty well. Then we started to write code to translate all the weird stuff like.

twice.do{//code}

puts#//word{name}

for($i...115) & for($i .. 115)

twice.do will be replaced with a for loop that iterates twice, and puts will be replaced with System.out.println
The for loops will be replaced with for loops that run num times for three dots, and num-1 dots for two dots.

We will also need to check out the different declarations of variables in ruby. That's it for now.