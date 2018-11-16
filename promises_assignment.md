//Jonathan.e
# Promises!

_Use promises to resolve each of these problems._

- Write a function `testNum` that takes a number as an argument and returns a Promise that tests if the value is less than or greater than the value 10.

- Write a function `whisperShout` that accepts a lowercase string. It should log that lowercased string to the console, wait three seconds, and then return the string in all capital letters.

- Write a function `waitFact` that accepts an array of integers. For each integer, wait three seconds and console log that integer's factorial (e.g. the integer 4 would console log 4!, or 24). Your function should take a little while to run!

- Write a function `barnyard` that accepts no arguments but defines an empty object. It should populate that object with five key-value pairs representing animals and the sounds they make (e.g. {pig: "oink"}). Then, (hint: `.then`) it should use `setInterval` console log each value of the object in order, creating a cacophony of animal noises in your console. When you get to the end of your array of values, you should return to the beginning.

- Take an object from an API. The object doesn't have to be large - it could be a single Ghibli film, or a single User, or a single Pokemon. Assign it to a variable. Create a function `getAPIResponse` that accepts no arguments, but contains a Promise. The first clause of the Promise should resolve with the API response, and the second clause (`.then`) should resolve with a single value from that object. Return the Promise.
