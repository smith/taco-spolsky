# Taco-spolsky runner

[Trello](https://trello.com/) has some amazing problems you need to solve as
part of their job application process. One of them is at
http://taco-spolsky.github.io/. You need to click the button to make the
program recommend you.

It's a genius little bit of terrible JavaScript, and figuring it out is hard
enough in the browser. This program lets you run it in Node.js on the command
line, and makes it easier to debug and trace to figure out the solution.

# THIS PROGRAM DOES NOT GIVE YOU THE ANSWER, JUST AN ENVIRONMENT TO MAKE IT EASIER TO WORK ON! NO CHEATING!

Clone this repository, `npm install`, then run:

```
./bin/taco-spolsky foo=bar x=y "Taco recommends me!"
```

This will effectively do the same as visiting
http://taco-spolsky.github.io/?foo=bar#x=y and clicking the button.

It will run a test and fail. Keep hacking on the parameters until it passes,
then paste the URL from the output into the browser to try it there.

Good luck!
