# Interview_Questions
General
--------------
1. What is CDN?
2. Explain CI/CD pipeline?
3. How Agile methodology works?
    - Task estimations - Planning poker?
    - What is Scrum? 
4. Testing
    - How Unit testing is done?
    -  What is Jest? How to include and work on it?
    -  What is TDD?
5. How do you check code quality?
6. What is minification? What is minified version? Why it is required? How it is minified?
7. Rate yourself for React out of 10?
8. What is the difference between Rest API and GraphQL?
9. What is Lazy Loading?
10. What library did you use for Unit testing? How did you do unit testing?
11. What do you prefer for unit test cases? Is it good to write test cases while working on an each use case or at the end of development?
12. What is the difference between Javascript class and Java/.Net class?
    A: Talk about dynamically typed and mutable concept.
13. What is git? why it is used? What is your day to day activity with git?
14. What is rebase in Git?
15. What is DOM? Which data structure it will use?
16. Difference between local storage, session storage and cookies? When to use what and why?


Javascript
--------------------
1. Difference between ES6 and ES7? Difference between ES5 and ES6?
2. Difference between == and ===?
3. What is object in JS?
4. What is Map?
5. Difference between let, var and const? Finding output (puzzels).
6. What is Pure functions?
7. what is Prototype inheritance? Puzzels on that.
8. What is Promises?
9. What is async and await?
10. Difference between async/await and promises.
11. Puzzels on async, await and promises.
12. What is Event loop? A: Its a concurrency module. (Talk about it)
13. What is this? Puzzels on this.
14. What is array destructuring?
15. Javascript design patterns.
16. How JavaScript is dynamically typed language?
17. How inheritance is achieved in JavaScript.
18. How to check Objects are equal? How to check object has same properties.
19. Explain Coercion in JavaScript.
20. What is Wrapper function? why it is required? what it does?
21. Difference between let and const? Ans - Reassignment is not possible to const but in let it is possible.
22. Difference between arrow function and regular function? When to choose between them?
23. What is callback hell in javascript?
24. What are the advantages and disadvantages of closure? A: https://dev.to/provish/closures-in-javascript-5fab
25. What is concurrency module in Javascript?
26. Why we cannot change the value of Const in javascript? A: Talk about Reference by value.
27. Puzzels on spread operator and destructuring.
28. Puzzels on async-await. (Order, does it need await)

HTML and CSS
---------------
1. Tell the priority of css when same css applied with tag name and class name?
    A: class will take priority. 
2. What is Specificity in CSS?
3. What is the specificty of this line?
    <div class='', id='', style=''></div> 
    A: style will take higher priority. (Inline style)
4. Give me 5 features of HTML?
5. What is HTML Semantics?
6. What is Box model in CSS?
7. What is the differemce between px and percentage? When to use what?
8. What is difference between padding and margin?
9. What is 1rem? Why it is used?
10. What is !important in CSS?
11. Does CSS follows top to bottom approach? A: Yes, its top to bottom and right to left approach
12. Expalin how you have written CSS? Will you choose to write inline CSS?


ReactJs
-------------------
1. What are the difference between React and Javascript? Jquery and React?
    - Virtual DOM and DOM
    - JSX - logic and HTML coding in one page
    - React represent main View (UI layer) of project.
3. Why to use React?
4. What are the libraries you used in React.
5. How to get details from server? Explain.
6. React build process.
    - Packaging process.
7. What version of React you used?
8. How Diffing algorithm works?
9. What are the other state management libraries available for react apart from Redux.
10. What is controlled and uncontrolled components in react?
11. What is Props drilling in React? How to avoid it?
12. How to pass properties between two siblings?
        A: 1 option : use of Redux
           2 option : Context API (avoiding props drilling)


Redux
----------
1. Redux workflow.
2. Why Redux.
3. Will React hooks replaces the Redux?
4. What is Flux? How it works?
5. What is reducers? How it works? How it is built.
    -Ans: It built on Pure functions.
6. Why Redux required? When to choose between Redux and other state management system.
7. What is the role of Reducer?
8. Is it required to store all data/state into reducer? 

NodeJs
----------------
1. How you used NodeJs in your Project.
2. Why NodeJs required?

Previous Experience related / Behavioral
--------------------------------
1. Explain your last project?
2. Why moved towards React?
3. What is your role?
4. What components you have worked on? Explain? - related to react.
5. Reason for geting good performer award.
6. How did you handle the complaince in your project in pharma company?
7. How do you mentor your juniors? Difference between mentoring and coaching?
8. Tell me how did you develop PeoplePicker component?
9. Tell me about the time when you have to work on something new?
10. Give me 3 positive and negative things about your project?
11. What makes successful developer?
12. What makes successful Project?
13. How did you handled Performance in your projects?
14. Tell me about a time when you worked on strange/complex story?

Coding
----------
1. React status bar based on object consisting of 3 values - critical, warning and normal.
    - Need to fetch the values from props and assign it to div element's width.
2.  1. Find each char occurances
    2. Remove duplicate in it. 
    3. Do not add uppercase values.
    4. Why the sequence is changed?
3. Find the ancestor for two Nodes 
    - Binary tree problem
4. Reverse the input.
    - Input can be string or integer
5. Finding output for code
    - this keyword
    - setTimeout
    - Promises
    - let, var const
    - block scope, closure, hoisting
6. Create a class
    - To register a call -> callName with action need to be registered => obj.register(action, callName)
    - To dispatch a call -> callName should execute based on action. Should accept data as parameter. => obj.dispatch(action, data)
    - To unregister a call -> callName with particular action should get unregistered. => obj.unregister(action, callName)
7. Design and develop Airline Price Calculator
    - Input - [['United', 150, 'Premium'], ['Delta', '50', 'Economy']] 
    - Output - Price should be calculated for United airles with Premium seat for 150 miles.
    - Price of per mile will be given. Additional charges for Premium seat(value will be given).
    - Price per mile will be different for different airlines. Also for different seat class.
8. Print array of 5 elements for every second. - Each element in the array should be printed with 1 sec interval.
9. ValidParantheses - Given a string s containing characters '(', ')', '{', '}', '[' and ']', determine if the input string is valid.
    - Input: 2(( ..+))5 
      Output: true
10. Build Shopping Address widget (Carasoul widget).
11. Print Prime numbers between the specified interval. For eg. n = 10 => Print all prime nubers from 1 to 10. If n = 100, print all prime numbers from 1 to 100.
12. Design a page below using HTML and CSS?
    \\\\\\\\\\\\\\\\\\\\\\
    \           \         \
    \           \         \
    \           \\\\\\\\\\\       
    \           \         \
    \           \\\\\\\\\\\
    \           \         \
    \           \         \
    \\\\\\\\\\\\\\\\\\\\\\\
 13. Create a class Model. These are the methods for the Model:
    - .get
    - .set
    - .has
    - .unset
    
    Should create class for
        - const person = new Model({ name: 'Jess', age: 22 });
        - var company = new Model();

14. You are a developer for a university. Your current project is to develop a system for students to find courses they share with friends. The university has a system for querying       courses students are enrolled in, returned as a list of (ID, course) pairs.

    Write a function that takes in a collection of (student ID number, course name) pairs and returns, for every pair of students, a collection of all courses they share.


    Sample Input:
    
    enrollments1 = [
      ["58", "Linear Algebra"],
      ["94", "Art History"],
      ["94", "Operating Systems"],
      ["17", "Software Design"],
      ["58", "Mechanics"],
      ["58", "Economics"],
      ["17", "Linear Algebra"],
      ["17", "Political Science"],
      ["94", "Economics"],
      ["25", "Economics"],
      ["58", "Software Design"],
    ]

    Sample Output (pseudocode, in any order):
    
    find_pairs(enrollments1) =>
    {
      "58,17": ["Software Design", "Linear Algebra"]
      "58,94": ["Economics"]
      "58,25": ["Economics"]
      "94,25": ["Economics"]
      "17,94": []
      "17,25": []
    }

   
