# Test assignment


<b>TEST ASSIGNMENT BY Doruk Taskin.

Assignment is performed using:</b>

Windows OS,Android Studio,Espresso,Kotlin,JUnit,Git,API level 28 android version 9 emulator.

For this assignment I have created the class Maintest to run the passing tests. These tests can be run individualy or a a group by running the tests from class MainTest.
This class uses some other functions and is extended by the class BaseTest, which has a built in rule to start the app everytime a test is run.
The Maintest class also imports some helper classes like MainPage and Utilities classes which have useful functions and are upholding the OOP-principles.

The other test runner class I have created is NegativeCasesTest and through this class we can run the negative tests, by testing and asserting unexpected values.
Negative testing ensures that your application can gracefully handle invalid input or unexpected user behavior. Just added a few simple negative case examples in there.

The tests were run with API level28 and android version 9 emulator. In Android Studio under Tools then select AVD Manager and there you can choose an emulator to be used.


<b>TEST RESULTS</b>

After running the tests you can export the test results by clicking on 'Export Test Results' button that is circled in red. This will automatically export
the test result in an html format to the Test Results folder that I have created, which can then be viewed in the browser.

![image](https://user-images.githubusercontent.com/32645994/141430286-beb648a9-1b4d-47f5-ac1b-519b34522fe6.png)




An example of a Test Result, after running the NegativeCasesTest suite, the report generated is as follows:

![image](https://user-images.githubusercontent.com/32645994/141385763-11197f58-bcef-45a4-b640-fa2289ab9a8b.png)


