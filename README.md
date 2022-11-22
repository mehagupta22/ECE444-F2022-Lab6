# ECE444-F2022-Lab6

## Flaskr-TDD Activity

Heroku App for flaskr-tdd activity: 
https://radiant-everglades-83490.herokuapp.com/

## Unit Tests in Group Project

Added 2 unit tests (test_search_substr() and test_search_name()) in test_app.py here:
https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-15-runtime-terror/blob/develop-new/Education_Pathways/tests/test_app.py

## Pros and Cons of TDD

Test-driven development is a software development practice relying on product requirements being converted into test cases before software is completely developed (writing tests before writing code). This contrasts the practice of developing software first and then testing the requirements. The following are some of the pros and cons of this kind of software development process:

### Pros

1. Easy maintainence - Since all functionalities are covered by unit tests, any change in code that causes an error is easily detectable in testing.
2. Modular codebase - To be able to write small unit tests one at a time, the code must be modular enough so that each feature can be thoroughly tested.
3. High test coverage - One test per functionality allows maximum code coverage which also helps with regression testing as no further implementation testing is required.
4. Easier collaboration - Allows team members to quickly understand each other's code and to modify code with confidence that defects will be caught in unit testing.
5. Clear requirements - Writing unit tests before starting development forces the team to have clear product requirements and use cases in mind.

### Cons

1. Maintainence of tests - The test suite must be kept updated with all future developments both in internal codebase and in external dependencies.
2. Slower development - TDD slows down initial development as it shifts focus to defining and writing tests. In small projects, this overhead might not be worth it.
3. Learning curve - This kind of development cycle might take some getting used to as most developers are used to testing functionalities after writing code and a round of internal local testing.
