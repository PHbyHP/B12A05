## question and answer

Q1: What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

ans: 
getElementById("id") is used to Finds one element by ID and for A single element.

getElementsByClassName("class") for to Finds all elements with a class 

querySelector("selector") is used to Finds the first match using CSS selector for A single element

querySelectorAll("selector") is Finds all matches using CSS selector for A list of elements.


---
q2: How do you create and insert a new element into the DOM?

ans:  
 let newElement = document.createElement("div"); 
newElement.textContent = "Hello!"; 
document.body.appendChild(newElement); 


----
q3: 
What is Event Bubbling and how does it work?

ans:
When you click a child element, the event also goes up to the parent and grandparent.
It starts from the clicked element and "bubbles up" to outer elements.


-----
q4: What is Event Delegation in JavaScript? Why is it useful?

ans: 
Event Delegation means: Add one event listener to a parent, and handle events for all its children.

Useful because:
1. we don’t need to add many listeners.
2. Better performance, especially when elements are added/removed dynamically.

---
q5:What is the difference between preventDefault() and stopPropagation()?

ans:
preventDefault() :   Stops browser’s default action 
stopPropagation():     Stops the event from bubbling to parent elements