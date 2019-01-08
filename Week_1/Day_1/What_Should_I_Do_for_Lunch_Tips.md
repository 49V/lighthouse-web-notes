### Tips

Try experimenting with the comparison operators ('<', '>', '===', etc.) in the node REPL, which you can launch using the 'node' command in Vagrant.

Work on your code iteratively – that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript

  function whatToDoForLunch(hungry, availableTime) {
   (hungry && availableTime < 20) ? console.log("Pick up something and eat back in the lab!")
  :(hungry && availableTime < 30) ? console.log("Take a break and go to Gastown")
  :(hungry && availableTime > 30) ? console.log("This is a bootcamp, take a shorter lunch you fool")
  : console.log("Wait until you're hungry");
}

```