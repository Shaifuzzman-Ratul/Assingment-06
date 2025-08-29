1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
 
   Answer:

   getElementById : It get element from html using id name,it select only one element.

   getElementByClassname : It get all element from html with given the class name.we get a htmlcolection.we need use loop to get a single element.

   querySelector : It select the element which match 1st with givien selector.It get only single element.

   querySelectorAll : It Select all Elements matching with the selector.It get a nodelist.we need use loop to get single element from it.



2. How do you create and insert a new element into the DOM?
  
 Answer : First, create a new  element using 'createElement' then set attributes using 'innerText'.Second get the parent container using 'getElemetById/getElementByTag'.Last use 'appendChild' to add the new element to the parent container.


3. What is Event Bubbling and how does it work?

   Answer :  Event bubbling is a process in DOM where an event starts from the inner element and then go its parent elements until it reach the main document.


4. What is Event Delegation in JavaScript? Why is it useful?

Answer : Event delegation means putting  eventListener to a parent element so it handle event from all of it's children.
Every time adding a click to every small button we just use one listener on the parent, and it will works on which  child is click because of event bubbling.

i.it makes code short nad faster because of less use of eventlistener.

ii.it works eeven we add new element becase we use listner on parent.


5.What is the difference between preventDefault() and stopPropagation() methods?

Answer:

preventDefault : preventDefault stop all action of an element.

stopPropagation : Stops the event from bubbling to parent elements means it stops the event from moving to the parent element.
