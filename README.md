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
14. Walk through Code and write comments as you go. Comments should tell why are we doing this not what.
15. Is connection pooling used?
16. If it is spark code. How is spark object being created?
17. Suggest Any Design Pattren to use.
18. If a function is having lot of input parameters. can It be bundled in domain objects.
19. Suggest to use domain object instad of primitive variables.
20. Multithreaded vs Single threaded
21. Unit test cases are exaustive or not
22. DRY and KISS Principle, Boy scout Principal
23. No Password in repository.
24. How to handle Sql Injection?
25. Input variable sanatization.
26. 

## Interview Experience
1. [Google EM Interview](https://www.teamblind.com/post/Google-code-review-interview-5HSeJtjD)
2. [Continous Delivery vs Continous Deployment](https://www.indellient.com/blog/whats-the-difference-between-continuous-integration-continuous-delivery-and-continuous-deployment/#:~:text=Continuous%20Delivery%20vs%20Continuous%20Deployment,-By%20this%20time&text=Continuous%20delivery%20is%20a%20partly,automating%20the%20entire%20the%20process.)
3. [Types of Release Process](https://www.testenvironmentmanagement.com/deployment-styles-bluegreen-canary-and-ab/)
4. [A/B Testing vs Canary Release](https://stackoverflow.com/questions/62092338/canary-vs-a-b-release-strategy)

## Blogs
1. [Try Exponent](https://blog.tryexponent.com/how-to-ace-a-code-review/)
2. [Code review Best Practices](https://www.youtube.com/watch?v=1Ge__2Yx_XQ)
3. [leetcode](https://leetcode.com/discuss/study-guide/1535554/how-to-prep-for-a-google-code-review-interview-question)
4. [Blog Post](http://www.javainterview.in/p/code-review-interview-questions.html)
5. [Github Blog](https://google.github.io/eng-practices/review/reviewer/looking-for.html)

## Code Review Examples
1. https://github.com/yogitaAP/codereviewgkcs/compare/53ed96b323f7b2dd85696a1689a8fdde53da3988...bef32a8cb9c15789bfa24d9ea648006921d11027
2. 
