# clock

>How it Works

It selects the HTML element with the id clock.

It uses setInterval() to update the clock every 1 second (1000 milliseconds).

Inside the interval function:

It creates a new Date() object to get the current system time.

It converts the time into a readable format using toLocaleTimeString().

It updates the webpage clock display using innerHTML.
