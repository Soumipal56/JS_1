# JS_1
# Introduction to JavaScript
##### Open any website -> right-click -> Inspect -> Console -> type: document.title
      In Dribbble: Dribbble - Discover the World’s Top Designers & Creative Professionals 
##### Try: alert("Hello World!") 
       A dialogue box will open with message written "Hello World!"
##### Write one line in your own words: "If HTML is skeleton, CSS is clothes - what is JS?" 
#### Answer: JS is the brain i.e. because of these our webpage becomes interactive, animations etc.
##### Write one example of where you've seen JS being used (like popup, animation, etc.) 
#### Answer: mouse movements, form submissions etc.

# Linking JavaScript Files
##### Create an HTML file and link JS file like this:
##### In script.js,write: console.log("Connected!)
##### Move the script tag to the section and see what happens. 
#### Answer: The code runs normally.
##### Try using defer:
      <script defer src="script1.js></script>
      <script defer src="script2.js></script> 
#### Answer: Makes script tag load in the background and run only after HTML is loaded.

# Running JS in Browser Console
##### Open console and type: 2 + 2 #### Answer: 4
##### Type: alert("Hi) #### Shows a popup message box with a message.
##### Try: prompt("Your name?") 
#### Opens a dialogue box showing name? where you can enter your name and it will return it.
##### Type: let city = "Durgapur"; city

# Variables and Keywords (var, let, const)
##### Declare your name using all three: var a = "Soumi"; let b = "Pal" const c = "NSHM"
##### Try reassigning them: a = "Updated"; b = "Updated"; c = "Updated" 
##### Create a variable inside curly braces using let and log it outside.
##### Predict output before running.
##### Write 3 examples where const is useful (like PI, baseURL, etc.) 
#### Answer: Name, Gender, birth year, gender etc.

# Logging and Interaction (console, alert, prompt)
##### Log name, age and city using console.log, console.info, console.warn
##### Use prompt to take user's name -> alert a welcome message.
##### Log typeof of user's input.
##### Try: let age = prompt("Enter age:"); console.log(age + 5); observe what happens.
#### Answer: It concatenates age with 5.

# Working with Strings
##### let msg = "I love Github";
##### Try msg.slice(2, 6) and predict the result.
##### Try msg.split("") and count words. 
#### Answer: 13
##### Try msg.replace("love", "work at")
##### Template string example: 
      let name = "Soumi"; 
      console.log(Hey ${name}, welcome to JS!)
##### Check if msg.includes("love")      

# Statements and Semicolons
##### Remove semicolon and check if code still runs. 
#### Answer: It still runs.
##### Combine two statements in one line and see if it breaks. 
#### Answer: Error.
##### Write 3 console.log statements without semicolons and predict output. 
#### Answer: It will run successfully.

# Comments
##### Write your name as a single-line comment.
      // Soumi Pal
##### Write a 3-line comment explaining what your code does.
      /* My first
         session on
         JS  
      */
##### Hide one console.log using comment and check output.
      // console.log("Hello World"); 
#### Answer: It will not print.

# Expressions vs Statements
##### Type 5 + 10 (expression). 
      5 + 10 = 15
##### Type let x = 10; (statement).
      let x = 10;
##### Which one gives a value immediately? 
#### Answer: First one.
##### Try: let y = (5 + 10) * 2; console.log(y)
      let y = (5 + 10) * 2;
      console.log(y);
#### Answer: 30
##### Write one line explaining the difference between both. 
#### Answer: statement doesn't return a value while expression returns a value.

# Data Types
##### let age = 25; let name = "Soumi"; let isStudent = true; let skills = ["JS", "HTML"]; let user = { city: "Durgapur" }; let x = null; let y; let z = Symbol("id")
##### Log typeof each variable. 
#### Answer: number, string, boolean, array, object, null, undefined, symbol
##### Change one value and recheck typeof.
      let x = 120.0 
#### Answer: number     
##### Try adding a number and string together.
      "Soumi" + 21
#### Answer: Soumi21

# Special Values
##### Log 1 / 0, 0/ 0, Number("abc"), undefined + 1
      console.log(1/0);
      console.log(0/0);
      console.log(Number("abc"));
      console.log(undefined + 1);
##### Write what appears
      Infinity
      NaN
      NaN
      NaN
##### Write one line explaining when to use null vs undefined. 
#### Answer: Use null when you don't want to give value null and undefined is assigned by default.

# Primitive vs Reference
##### 
     let x = 5; 
     let y = x; 
     y = 10; 
     console.log(x, y);
##### 
     let abj1 = { 
                  name: "Soumi" 
                }; 
     let obj2 = obj1; 
     obj2.name = "Pal"; 
     console.log(obj1.name);
##### Observe which one changes together. 
#### Answer: x=5, y=10 -> Real value was copied.
#### Answer: Pal -> Parent reference was copied.
##### Draw memory boxes on paper to visualize difference.
      
     

      




      


      



    
    
