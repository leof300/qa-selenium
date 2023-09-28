# qa-selenium

## Page Object Model | POM

 Is a design pattern or a framework that we use in Selenium using which one can create an object repository of the different web elements across the application.  In the Page Object Model framework, we create a class file for each web page, create different classes for  multiple pages, and then save the web elements on the pages in them. Correspondingly, we save the test cases under a different package, making clear segregation among the different aspects. 

 ![imagen](https://github.com/leof300/qa-selenium/assets/69184023/3f6b17d1-89c6-4159-8484-2536a2843ffd)


 ### Benefits
 
- Makes code maintainable- Since the test classes are separate from the classes containing the web elements and the operation on them, updating the code is very easy if any web element updates or a new one is added.
- Makes code readable- The user can easily read through the project and test scripts due to a fine line between the test classes and the different web pages.
- Makes code reusable- If multiple test scripts use the same web elements, then we need not write code to handle the web element in every test script. Placing it in a separate page class makes it reusable by making it accessible by any test script.


