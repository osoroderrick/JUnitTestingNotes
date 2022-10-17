# JUnitTestingNotes
>Unit test are useful because they provide quick feedback on a small unit of code instead of waiting for a system to be built
>Unit test act as a form of documentation if somone needs to konw what a class does and how its used they can open the unit test and find information
>The @Test annotation above the method declaration indicates to JUnit that this a test method to execute
>Annotations in Java provide meta databout code but aren't executable statements
>JUnit 5 unit test include setup code, code that calls the system under test, and assertions to verify results
>AssertSame will verify that the two variables being compared point to the same object in memory
>AssertNotSame will verify that an object that was supposed to have been copied to another object isnt the same instance as what is what to be copied from
>AssertTrue verifys that a condition is true
>AssertFalse verifys that a condition is not true
>AssertIterableEquals used to compare collections of different types 
>@BeforeAll run once before all test methods in the class  
>@BeforeEach will run once before each test method
>@AfterEach will run once after each test method
>@AfterAll will run once all the test in the class have been completed 
>@AfterAll and @BeforeAll are at the class level so they are static 
>AssertThrow can be used to explicitly verify that we get an exception when a certain code is called
>The first parameter of asserThrows is a runtime exception and the second is a lambda expression
>The runtime exception is the parent class in all exceptions of the java that are expected to crash or break down the program or application when they occur.
>A lambda expression is a short block of code which takes in parameters and returns a value. Lambda expressions are similar to methods, but they do not need a name and they can be implemented right in the body of the method.
>After and asserrtEquals you can add a message that describes what a failure means in more detail
>@Disable temporarily stops a test from running instead of having to comment it out
>The Single priniciple is the idea that a unit of code should do one thing is realted to code cohesion that the functioncs of some unit of code are closeley related to one another and also the idea of seperation of concerns , a given unit of code should only haave one reason to change
>
