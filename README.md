# ECE444-F2021-Lab6
Completion of Lab 6

## Pros and Cons of TDD

Test driven development is the method of writing test cases that you initially fail and then write your code to make it pass those tests. This approach comes with it's own set of pros and cons. The following highlight the pros and cons of the approach.

### Pros
- TDD forces developers to have a a code base with good architecture and modularization. Since you have to write tests for each new feature and then code to pass the test. It means you cannot work on too large of a component at a given time as the complexity will be too much to test.
- This approach leads to detailed test cases. Since the test cases are written at the start of implementation they will be properly done as opposed to conventional tests written once the code is written. Often in industry if there are deadlines approaching tests will be rushed in the hopes of staying on track.
- This apprach is also really good for refactoring one;s code. The approach helps programmers really understand their code as they have a clear set of requirements they write the test on and code towards accomplishing this. Therefore modifying old code is easy due to how detailed the test cases are.

### Cons
- One of the biggest drawback of this approach is it is time consuming and not maitaniable in a fast paced tech development environment. The need to fully determine and write the unit test delays the time spent implementing the code.
- Programmers often get confused and instead of wtiting good TDD test they only write basic unit testing.
- It is difficuly to implement on legacy code
- The set of code can grow very quickly making build take longer. Therefore the tests need to be maintained and reformed regularly to maintain it's speed and remove redundancy.
