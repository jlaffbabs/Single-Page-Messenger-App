# Single-Page-Messenger-App
Single Page JS App 

# Plan
	1.	Testing environment set up (Jasmine)
	2.	Run infrastructure test (passes by being able to read page title) 
	3.	Maybe second infrastructure test which tests whether Jest can detect an onclick / JS event 
	4.	Make one test for each of the requirements - follow red green refactor cycle

```
  As a user I want to see: <br>
    A title <br>
    A form (text box and button)
    All the messages with a timestamp in reverse chronological order (newest at the top) <br>
  
  As I user I want to: <br>
    Input text of a message <br>
    Click on the submit button and see the new message at the top of the previous messages<br>
```

So six tests for the above user stories
Technical requirements
	1.	The logic of this app should be tested
	2.	The logic should be encapsulated in classes
