** EXERCISE 1 **

1. Outputs 'welcome' because lastWord was defined as 'welcome' before the console.log

2. Outputs 'up here!' because the message variable runs through the function shout()

3. Outputs 'down below' because shout(message) function closes before shout(down below) is called.

4. Outputs 2 dozen; var muffins and purchasedMuffins are global and get run thru the getMuffins function

5. Output is sneak out, because var chore = sneak out is defined within the function and that's the function being run.

6. Outputs 'looking for gold' because getMail function is run and var contents = 'looking for gold' is a global variable. var contents = 'struck it rich' will only output if changeContents() is run.

7. Undefined because both functions close before they are called upon.

** EXERCISE 2 **

1. assigning address as the buildHouse function

function buildHouse(address) {
  // ... house gets built
  return 'Building house at ' + address;
}
address = buildHouse('123 Happy St.');
console.log(address);

2. Moving var smoothie outside if the function allows it to print whether the function is true or false

var smoothie = 'strawberry banana';

var determined = false;
if (determined) {
  var smoothie = 'strawberry banana';
}
console.log(smoothie);


3. Putting the loop inside a function that closes before console is called upon

function arrayLoop() {
  for (var index = 0; index < 5; index++) {
  // ...
  }
}
console.log(index);


4. Changed into a for loop so that console.log will run

var items = ['glasses', 'toothpaste', 'wallet'];
for (var i = 0; i < items.length; i++) {
  var lastItem = items[i];
}
console.log(lastItem);
