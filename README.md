# Happy-Numbers-JD-Salinger
### Happy Number: The Definition ☺️
Take a positive integer > add the squares of its digits > Keep repeating this process till the sum of squares of the digits is 1 > If you do manage to reach 1, the number is happy, if you don't, its an unhappy number.

### The Code
```javascript
// I’m aware that many of my friends will be saddened and shocked, or shock-saddened by JavaScript.

// Most numbers are goddamn phonies, I swear to God.
function howAreYaAnyway(number) {
	// What I thought I'd do, I thought I'd loop. I mean it.
	do{
		if (number < 5) break 
		thisNextNumber = 0;
		// Making it a string. I'm serious. 
		number = String(number)
		for (i in number)
			thisNextNumber += number[i]*number[i]
		// Putting the next one right back in the old one. Corny as hell I'll admit it.
		number = thisNextNumber 
	} while (true)
	// Only about five numbers are really happy, that kills me.
	// return "I'm " + ['H','Unh'][number==1?0:1] + "appy, I really am"
	// I have changed it for testing, original on line above (issue with the apostrophe)
	return "Im " + ['H','Unh'][number==1?0:1] + "appy, I really am";
}
```
