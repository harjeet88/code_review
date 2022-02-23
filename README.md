# Code Review

## Approach
1. Check Naming convention of Variables
2. Opportunity to split a function. A function should not be doing multiple things and follow Single responsibilty approach.
3. Function should be generic and re-usable
4. Check code for Edge cases
5. It should not have too many if else condition and too many nested if conditions - This means cyclomatic complexity is high
6. Code should not do operations which can easily be done in DB. like filetring and joining datasets. there should be strong reason why such code is written
7. Nested Loops are bad - They increase complexity of code and makes it slow. suggest better way to remove this. it can be by using a datastructure or by recursion etc.
8. Exception handling in code. How errors are handled
9. Is code following SOLID Principal.
10. Any hard coding of string or variable value is bad.
11. Is Property Management done properly?
12. How Nullable - non-nullable is handled
13. How unexpected input is handled?
14. Walk through Code and write comments as you go.
15. Is connection pooling used?
16. If it is spark code. How is spark object being created?
17. Suggest Any Design Pattren to use.
18. If a function is having lot of input parameters. can It be bundled in domain objects.
19. Suggest to use domain object instad of primitive variables.
20. Multithreaded vs Single threaded

## Interview Experience
1. [Google EM Interview](https://www.teamblind.com/post/Google-code-review-interview-5HSeJtjD)

## Blogs
1. [Try Exponent](https://blog.tryexponent.com/how-to-ace-a-code-review/)
2. [Code review Best Practices](https://www.youtube.com/watch?v=1Ge__2Yx_XQ)
