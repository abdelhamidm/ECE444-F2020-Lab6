# Lab6 - The Pros and Cons of TDD

Test Driven Development (TDD) is a development methodology by which a developer writes and runs a set of tests before writing code. Obviously, these tests will fail at first. The developer then starts to write code to get all the tests to pass. Once all the tests pass, a developer may use that to mark the completion of the development work. 

Pros of TDD include: 
* TDD involves writing small tests at a time. Because the developer's goal is to pass these individual tests, the code tends to be modular. Because modular code is not tightly coupled, it is easy to maintain, upgrade, and refactor over time. 

* TDD allows discovering and avoiding problems early on. Because tests are written before the code is written, it is easier to detect architectural problem early in the process. This makes it easier to correct these problems. 

* TDD facilitates collaborating on the development of a project with a team. Because the code is modular, it is easier for different team members to work on different components of the program. Additionally, because the tests exist, team members can modify other members' code and see if their changes caused any issues with the code.

Cons of TDD include:
* TDD requires developing and maintaining an extensive test suite. It may be difficult to write and maintain tests for large programs with many components and functionalities. 

* TDD slows down the initial development. This is because developers start writing tests before writing program code, so it takes them longer to start developing the actual program code.

* TDD adds overhead to the project. A developer needs to run tests often, and, for large prorgams, running these tests may require more time. 

* TDD requires everyone on the team to correctly maintain their tests in order for the process to be organized, efficient, and successful. 
