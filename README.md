<h1># Generator </h1>

A generator is a function that yields values one at a time using the yield keyword instead of return.
Each time you call next() on a generator, it resumes where it left off.

<h1>Key Features </h1>

Uses yield instead of return.
Maintains internal state (remembers where it left off).
Automatically raises StopIteration when done.
Lazy evaluation — doesn’t compute until you ask for the next value.

 <h1> Why Use Generators?</h1>
Efficient memory usage.
Great for reading large files line-by-line.
Useful in pipelines and real-time data processing.
