# Frontend Machine Coding Questions - (Vanilla JS/ React-JS)

## Questions

- Show a button that will show start label on click it should show stop, viceversa show a counter with 0, after clicking start it should increment the counter by 1 every one second, on click of stop it should stop the counter and resume again where it was stopped previously.

- Given an API returning a list of todos, we want to fetch the list, create a separate block for each user, and display their todos in the appropriate block. Use this endpoint URL to get the todos: https://dummyjson.com/todos?limit=10&skip=80. It will return the following structure with a total of 10 todos: { “todos”: [ { “id”: 1, “todo”: “Do something nice for someone I care about”, “completed”: true, “userId”: 26 }, ], } Each block should contain the userId as the title of the block and the list of todos.

- Create 2 mock API’s which returns a list of students and each student has a name, some marks and a unique registration ID. Data from the 2 API’s can have common students i.e. mock API 1 can have a student as — ABC / 98% / 1234 (name / marks / registration ID) and this same data can be there in mock API 2 response as well. Now after creating these 2 API’s using Promises and hard-coded data, you need to merge the data coming from both API’s and have to delete the duplicates.

- Using this API endpoint - https://dummyjson.com/products, Display the data in a list with a checkbox and button delete with each item, Before displaying the items, add a feild completed: false in the JSON, It should be able to delete the item on click of delete button, on click of checkbox it should mark the item as completed with line-through to the item marking it as complete.

- Implement pagination using this API endpoint - https://dummyjson.com/products,

```
1.It should display 10 items on each page.
2. The page which is active should show active state.
3. It should have forward and Previous arrow on which we can change the page number.
4. Handle loading state on each page change.
5. When it's the first page the previous button should be disabled, similarly for last page.
```

- https://dummyjson.com/products using this API, display products, create a sidebar Just like Flipkart UI, show checkboxes with label - 40% and more, 50% and more, 60% and more, 70% and more, When click on particular checkboxs it should filter the products according to the discount percentage, If no products available show a display message accordingly, there should also be a button to clear the selection of selected percentage, render the UI accordingly.

- Create a multi-step form, where next and previous button are there on the last page user should be able to submit the form, on previous click the data entered should be persisted.

- Create a stopwatch display in this format - HH:MM:SS, with three buttons start, stop and reset, it should update the seconds every one second, after 60 sec update to 1 minute after 60min, update to 1hr, on stop button it should stop the watch and should be able to start again, on reset it should reset all values.

- Implement a stack structure

```
1. Create a UI that resembles stack
2. Add Input that accepts number.
3. push button : Add an element to the top of the stack.
4. pop button : Remove the topmost element from the stack.
5. create a function isEmpty : Checks whether the stack is empty.
6. create a function top : Displays the topmost element of the stack.
```

- Impelement a previous and next functionality, create a button increment, display initial count to 0, when Increment is clicked it should show two text -

```
1. Current : that will display the incremented count.
2. Previous : This will show the previous value that was before incrementing the count.
```

- Build an input box and a button to store items in an array, and have another button to find the second largest element from the stored array. Also, the array of items should be displayed along with the second-largest number.

- Create a reusable input component that will accept type as a prop
  and will do different types of input validation(if the type is text it should contain max x no. of characters if a type is a number it should be between x and y etc.) depending upon the type we passed. As soon as something invalid is entered, an error should dynamically show on screen and as soon as we change it to something valid, the error should also disappear.

- Implement four quadrants (just like the Microsoft logo) using react with reusability.
  And after that, whenever I click on a box, it should show clicked on that particular box, and when I click on another box it should show clicked in that box and disappear in another box. ( without any code redundancy)

- Make three radio buttons with labels red, blue, and yellow and add a div below it . When I click on any radio
  button the color of the div should change ,for example , if I click on red the colour should be red.
  Add feature that if I click on two radio buttons the colour of div should be mixture of those colours.

- On check/uncheck of top checkbox, all checkboxes should be checked/unchecked and vice-versa.
  We should be able to individualy check/uncheck checkbox from the list.
  If any of the checkbox is unchecked, the top checkbox should show an intermediate symbol.
  A button below the checkbox, which when clicked should console log only the Id of the checked checkbox.

- create a toast message using Javascript/ React , it should disappear automatically after 5sec.

- Create a Reusable react card, header and type is passed as props, style of that card should be determined by type of card it is through prop : like type="facebook" some style, for "twitter" some other style, some nested components inside the body of card, they should also have styles.

- Create a component which converts the input to ascii, add 10 to it and convert the same from char code.

- Validate form
  name (must not be empty and less than 100 characters allow);
  age (between 18-99)
  email(valid email)
  password(at least 8 characters)
  re-password(password and re-password same)
  show error message in the alert box!
- optimize the performance of a React app that displayed a large list of data, and the interviewer wanted me to explain the most efficient approach to rendering the lists.
