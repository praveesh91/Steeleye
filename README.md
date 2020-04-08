# Steeleye
scenario based assignment 


Improvements in the current scenario.

1) The current class component doesnot have a parent constructor "super(props)".

2) In the map method, rather than calling a function to list out the elements, the list elements can be included 
   within the map function as a part of performance optimisation.
   
3) In the current scenario, there is no need for a shouldComponentUpdate lifecycle method as the data remains unchanged here.
   shouldComponentUpdate is helpful for better performance to stop re-rendering the DOM when the data remains unchanged.
   I have created such a scenario in attachment.
   shouldComponentUpdate can also be achieved through pure components

4) handleClick is a function call invoked on clcking the list element, so whatever goes into the function gets excecuted
   once the user clicks a list element. Here if we want to display index, we can alert this by "alert(index)".
   
**Please find my chunk of code in the files included in the repo
