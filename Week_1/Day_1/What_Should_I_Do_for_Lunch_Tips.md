### Tips


#### Lunch time
Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript 
function whatToDoForLunch(hungry, availableTime) {
  console.log("hungry is", hungry);
  console.log("availableTime is", availableTime);
}
```

#### Process.Argv

All this script does is loop through the process.argv array and prints the indexes, along with the elements stored in those indexes. It's very useful for debugging if you ever question what arguments you're receiving, and in what order.

```javascript
'use strict';

for (let j = 0; j < process.argv.length; j++) {
    console.log(j + ' -> ' + (process.argv[j]));
}
```
[More info on process.argv and Command Line Interface (CLI)](https://stackabuse.com/command-line-arguments-in-node-js/)