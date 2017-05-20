# LJ Code 301 - Day 10   
Today we discussed declarative programming and higher-order functions. Specifically we went over how to use the Array methods forEach, map, filter, and reduce. Also how to attach everything to a single global object.  

It was interesting to see how to attach all the functions to a single global. I did not realize you could pass an argument into an IIFE in order to attach functions and other variables as methods and properties. It seems pretty tricky to only attach the functions to the global after they were created. This way, you do not need to have the global in front of the functions declarations, thus making the code much cleaner.  
