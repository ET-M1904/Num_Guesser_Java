String Menu
- It take no parameters
- Prints out the menu
0) quit
1) Human Guesser
2) Computer Guesser
- ask for input
- return input as a string

Menu Constructor
- Make boolean keepGoing
- set response to empty string
while keepGoing
	call menu and put result as string
	if response is one
	call humanGuesser()
	if response is two
	call computerGuesser()
	if response is anything but 1 or two
	call quit()

humanGuesser()


computerGuesser()
- create int lower, set to one
- create int higher, set to one hundred
- create int guess, use getMean to find the mean of lower and higher
- create int turns, set to zero
- creat boolean keepGoing, set to true

int getMean(int lower, int higher)
- utility function
- used in computerGuesser()
- Calculate the mean from lower to higher (



