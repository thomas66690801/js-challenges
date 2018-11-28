### JS Drills

Sometimes you learn how to do things before you fully understand how they work. Coding is like this a lot. There are many things that I learned how to do well before I asked how they function. There are still plenty more things where that is the case for me. You merely push back that barrier slowly, but the unknown remains. In that vein, these are exercises that are designed to get you familiar with the lingo of arrays, objects, and functions, and get you repeatedly using them. It’s not a test, or even a challenge - it’s practice. Consider it like doing a forehand drill in tennis, or scales in music. You wouldn’t be upset making some mistakes while you practice, because you know that this is the thing you need to work toward being competent, and you allow yourself to fail and learn. This is exactly the same. 

Learn and fail as you need here, because the bigger tests are to come. As you get more comfortable with the basic syntax, and getting your code to work, you will have more brain space to think about what it is it all means. (And we are more than happy to keep explaining that at the same time too!)

Follow the instructions carefully. They will be repetitive and are not designed to be interesting, but rather build up ‘muscle memory’. *Each* line of code that you write, you *must* save the file and run the code. If there are *any* errors, you fix them then and there. If in doubt, puts out the structure you have made to make sure that it is what you hoped it was. I’m looking for accuracy - I want the instructions followed precisely. It will be your choice of class and variable names (etc), but the functioning and number of attributes called for are immutable. Ideally you’ll want the work to be checked, so copy and paste this text into a file and comment it out, so that I can check it easily - put the answer directly below the question.

1. Make a function that takes two arguments, and returns the result of them added together.
2. Call the above function four times with different inputs each time. Make at least some of the inputs floats. 
3. Define two integer and two float variables, and use them as arguments to this method you have made.
4. Make an object (in ruby this would be a hash) with four keys, and have the keys be three different data types.
5. Access two of the values in your object, and log them to the screen.
6. Define a function that takes an object as the input, and log out the value of one of the keys of the object.
7. Create an object with one key and value pair, and invoke the previous function with that object as the argument.
8. Make an object with three keys and values, and assign it to a variable.
9. Make four more objects with the same keys.
10. Access a value from three of these objects.
11. Define a variable and assign to it an empty array.
12. Define a function that takes an array and an object as arguments. The function will push the object into the given array.
13. Using the function, the four objects, and the array that you have made in the previous steps, invoke the function four times to put those four objects into the array.
14. Make sure that the array contains four hashes (maybe log to the screen).
15. Access two elements of the array that you have created (via an index)
16. For one of these, now access one of the values of the object at that is located at that index.
17. Write a function that takes two arguments - one an object, and the other an array. Inside the function log out a value from the object, and an element from the array.
18. Define four objects, one with one key, one with two keys, one with three keys, and one with four.
19. Define two different arrays, with two different datatypes.
20. Call the function four times, once with each object, and use the arrays you made.
21. Write a function that takes five arguments: three strings, and two numbers.
22. Call that function twice.

The next set of drills are a bit more difficult. I know that sometimes it might be hard to work out what is meant by the question, but I ask that you stay with it and do your best to piece it apart - sometimes it is hard to express these questions without some confusion. I am happy to give answers to some of the questions if that will help with the understanding so that you can move forward. Where a question asks for a log to screen, the simplest thing will be to log the name of the function. Most times in these questions it is not what the function does that will be important, but rather how that function sits within the object, or even within the other function.

1. Define an object that has two keys. One will have the value of a string, and the other a function (and this function can simply log its own name to screen).
2. Log the string to screen.
3. Log the entire function to screen.
4. Invoke the function within the object. 
5. Define an object that has three keys, and each key has the value of an anonymous function. In each function log something to screen (different in each function).
6. Call each function (through the object).
7. Make a function that returns an object that has two keys, one key with a string value, and the other that has an anonymous function as its value. 
8. Log to screen the result of invoking this function.
9. Work out how to log to screen the value of the returned object’s string.
10. Invoke the returned object’s function (via the first function - you will need to return the object, and then call the function within the returned object). 
11. Write a function that takes a number and a function as an argument. Inside this function perform three simple calculations with the given number (the first argument), and then pass the final result to the function that is passed as the second argument.
12. Call this function three times with different numbers, and a different anonymous callback function each time (perhaps each time the callback doing a different simple calculation). 
13. Now write two functions that take a number as an argument, and do some very simple calculation.
14. Invoke the function from 11 twice, each time with a different number argument, and using each of the two functions that you just defined in 13 (one in each invocation). 
15. Define three very basic functions that take no arguments and that simply console out the name of the function. 
16. Place each of these functions into an array (do not call the functions).
17. Loop through this array and invoke each of the functions in turn.
18. Define a function (funcReturnsFunc) that returns an anonymous function. If you like you can have funcReturnsFunc log out something before it returns the function. The returned function can just log out a simple message to inform you it ran. 
19. Invoke funcReturnsFunc, and store the result in a const.
20. Using that const, run the returned function.
21. Now do the same thing in one line: run funcReturnsFunc, and then run the anonymous function result immediately.
