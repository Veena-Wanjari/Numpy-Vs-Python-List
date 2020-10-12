# Numpy-Vs-Python-List

## Mini Program to prove which is faster ??

Quite a lot has been written about the performance of Numpy versus Python List in recent years on many discussion platforms and data science blogs. 

To begin with, NumPy is a Python fundamental package which used for efficient manipulations and operations on High-level mathematical functions, Multi-dimensional arrays, Linear algebra etc. 

The Python core library provided Lists. A list is the Python equivalent of an array, but is resizeable and can contain elements of different types.

A common beginner question is what is the real difference here ??

**__Numpy data structures perform better in__**:

 1. Size - Numpy data structures take up less space.
 
 2. Memory - NumPy arrays have smaller memory consumption and better runtime behaviour. 
 
 3. Functionality - NumPy has optimized functions such as linear algebra operations built-in.
 
 4. Performance - they have a need for speed and are faster than lists.

So, the answer is performance. 

To substantiate, a small code is written to prove it. 

 1) We will be using an in-built python library timeit.

 2) timeit module runs our snippet of code millions of time (default value is 1000000), so that we get the statistically most relevant measurement of code execution time!

 3) timeit is pretty simple to use and has a command line interface as well as a callable one.

   * A 'nanosecond (ns)' is an SI unit of time equal to one billionth of a second, that is, ​1⁄1 000 000 000 of a second, or 10<sup>−9 seconds.

     The term combines the prefix nano- with the basic unit for one-sixtieth of a minute.
     [Nanoseconds](https://en.wikipedia.org/wiki/Nanosecond)
  
   * A 'microsecond (μs)' is an SI unit of time equal to one millionth (0.000001 or 10<sup>−6 or ​1⁄1,000,000) of a second. 
    
     Its symbol is μs, sometimes simplified to 'us' when Unicode is not available.
     [Microseconds](https://en.wikipedia.org/wiki/Microsecond)

   * A 'millisecond (ms)' (from milli- and second; symbol: ms) is a thousandth (0.001 or 10<sup>−3 or 1/1000) of a second.
     [Milliseconds](https://en.wikipedia.org/wiki/Millisecond)
  
  
