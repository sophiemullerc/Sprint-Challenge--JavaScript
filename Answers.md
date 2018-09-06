# Your responses to the short answer questions should be laid out here using Mark Downs
1. Describe some of the differences between `.forEach` & `.map`.

     The biggest difference is that .map returns a new array, .forEach doesn't. This just means that you have to give .map a variable for the array to be returned into. .forEach you can just straight up mess with the original array.
2. Name five different Types in JavaScript. A Type is something that can represent data. What is so special about Arrays?
    Basically the same thing, it's just where they're located at. A function inside of an object is a method. 

3. What is closure? Can you code out a quick example of a closure?
    Closure is where the invokation of your function ends. Like if you have return value pushed to a global variable, your closure would end with that variable.

4. Describe the four rules of the 'this' keyword. 
    Explicit(methods), Implicit(.chaining), New(constructor), Window(global window).

5. Why do we need super() in an extended class? 
    super() functions as the 'gut connector' between the two objects you are linking. It lets you connect the methods between two objects. 