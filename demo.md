# Test Automation Questions

[![hackmd-github-sync-badge](https://hackmd.io/63f1w72WTi6JzHh-2oqqUA/badge)](https://hackmd.io/63f1w72WTi6JzHh-2oqqUA)


1. How many types of webdriver API are available in Selnium
* choromeDriver
* firefoxDriver
* htmlUnitDrive
* ie driver

3. how would you make sure that a page is loaded using selenium and webdriver?
We can implicitly wait for the page to load: 
```
driver.manage().timeouts().implicitlyWait()
```
After the page is loaded, we can also invoke javascript method `document.readyState()` wait till `complete is returned`
```java 
JavaScriptExecutor js = (JavaScriptExecutor)driver;
js.executeScript(return document.readyState()).toString().equals("complete")
```

5. how can we launch a batch file in selenium webdriver project?
```java
process batch = Runtime.getRunTime().exec("Path of the batch file");
batch.waitfor();
```
6. how do you run selenium webdriver test from command line?
7. what are the different exceptions that you found in selenium webdriver?(no such element, webdriver exeption, timeout exception, noalert exception, nowindowexception)
8. what do you mean by timeout exception?
9. staleelement exception
10. have you heard about page object model?
11. how do you scroll down to a page in javascript in 
12. how do you scroll down to a particular element?
13. which all file types can be used as data source to selenium framwork? csv, excel, xls etc. 
14. what are the listenrs in the selenium
15. is it possible to navigate back-and-forth in selenium?
16. how will you take screen shot in selenium webdriver?(takeScreenShot function, getScreenShot)
17. some of the testing types can be acheived (sanity, smoke, cross browser, regression, functional, responsive, ui testing, integration)
18. what do you mean by assertion in selenium? (verification point)
19. which are the types avaiable? (assert, verify)
20. which are the build phases in maven? (validate, compile, test, package, install and deploy)
21. how will you handle keyboard and mouse actions in the selenium? (action class=>, robot class, vinium class)
22. what is json
23. what are the priciples of the software testing?
24. what is the difference between low testing and stress testing?
25. what is stale element exception?
26. what is random testing?
* order of specifier don't matter in java
* four access specifier, public, private, protected and default
* object is the instance of the class and it is the real time entity, it has it's own state and behaviour
* static method can not be over written, static method can not be used not static method,
27. which are the different phases of the software testing lifecycle?
28. what would be the correct exection order 
29. why is main method static?
 



