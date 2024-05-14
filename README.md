# JAVAScript-tasks-

//Create a greet function that takes name and partOfTheDay parameters and returns a greeting as a string.
//greet('Paul', 'night'); // 'Good night, Paul!'
//greet('Mike', 'morning'); // 'Good morning, Mike!'
//If only the name is given during the call, set the default value of the partOfTheDay parameter to 'afternoon'.
//greet('John'); // 'Good afternoon, John!'
//Call the greet function twice:
//first time with arguments Mike and morning;
//a second time only with the argument 'John'.


function greet(name, partOfTheDay = 'afternoon') {
  return `Good ${partOfTheDay}, ${name}!`;
}

greet('Mike', 'morning');
greet('John');

