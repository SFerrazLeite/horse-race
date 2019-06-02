# Horse Race Simulator
This little project is the companion code to [my acrticle](https://sferrazleite.blog/understanding-promise-race/) on the Promise.race function.

There are two files: `playground.html` shows the use of promises in general. `horse-race.html` is a playful
implementation of a horse race simulation. The supidly simple slightly randomized horses will return promises
when they start racing. Upon reaching the goal, their promises resolve. The calling glue code
uses Promise.race in order to get notified of which horse wins the race.

## Usage
Check out the code and open the html files in your browser. That's it!

## Self Advertising
Check out [my coding blog](https://sferrazleite.blog/) for details or more tutorials and content!

If you wish to support my work, feel free to [donate through paypal](https://www.paypal.me/SFerrazLeite) -- any support is appreciated.