#Here are all 5 rules reviewed below:
* Give your functions precise verb/action based names
* Use camelCasedNames (like this one)
* Properly indent the function code
* Functions should focus on a single task: returning a value or causing a side effect. Break your function into additional smaller functions if you find it doing two or more things
  * One single task could be to compute and return a value (eg: zeroPad)
  * Another single task could be to perform a side effect such as logging a message to the screen (eg: printFarmInventory)
* Data needed by Functions should be passed in as parameters/arguments (i.e. local scope) instead of being accessed directly
