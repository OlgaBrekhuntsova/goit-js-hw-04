# goit-js-hw-04

-----TASK-1-----

Write a function isEnoughCapacity(products, containerSize) that calculates
whether all products will fit into the container when packed.

The function declares two parameters:

products — an object where the keys are product names and the values are the
quantities of those products. For example: { apples: 2, grapes: 4 }.

containerSize — a number, the maximum number of product units that the container
can hold.

The function must return the result of checking whether all products will fit
into the container. That is, it should calculate the total number of products in
the products object and return true if it is less than or equal to
containerSize, and false otherwise.

Take the code below and insert it after declaring your function to check if it
works correctly. The results of its calls will be displayed in the console.

-----TASK-2-----

Write a function calcAverageCalories(days) that returns the average daily number
of calories an athlete consumed during the week.

The function expects one parameter:

days — an array of objects. Each object describes a day of the week and the
number of calories (calories) consumed by the athlete on that day.

Take the code below and insert it after declaring your function to check if it
works correctly. The results of its calls will be displayed in the console.

-----TASK-3-----

The object profile describes a user’s profile on a gaming platform. Its
properties store the profile name (username) and the number of active hours
(playTime) spent in the game.

const profile = { username: "Jacob", playTime: 300, };

Extend the profile object with methods to work with its properties:

The method changeUsername(newName) must take a string (the new name) as the
parameter newName and update the value of the username property. It does not
return anything.

The method updatePlayTime(hours) must take a number (the number of hours) as the
parameter hours and increase the value of the playTime property by that amount.
It does not return anything.

The method getInfo() must return a string in the format: <Username> has <amount>
active hours!, where <Username> is the profile name and <amount> is the number
of game hours.

Take the code below and insert it after declaring your function to check if it
works correctly. The results of its execution will be displayed in the console.
