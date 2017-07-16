# 100 Days Of Code - Log

<!-- ### Day 0: February 30, 2016 (Example 1)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link to work:** [Calculator App](http://www.example.com)

### Day 0: February 30, 2016 (Example 2)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts**: I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link(s) to work**: [Calculator App](http://www.example.com)


### Day 1: June 27, Monday

**Today's Progress**: I've gone through many exercises on FreeCodeCamp.

**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after a lot of attempts and hours spent.

**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence) -->

### Day 1: July 14, 2017

**Today's Progress**: Created a json file, hosted it on github, successfully brought it down into my js with httpRequest. Learned how to use querySelectorAll to select all buttons and bind individual eventListeners to them using Array.from().forEach like so:
```javascript
Array.from(chordButton).forEach(button => {
  button.addEventListener('click', function(e) {
    let currentChord = this.dataset.chord;
    // console.log(this);
    // console.log(chordList.guitar.a.major.audio);
    console.log(chordList.guitar[currentChord].audio);
    console.log(currentChord);
  })
})
```
The rest of the console.log nonsense in my code is maybe me trying to figure out something that might be useless. It's just a really roundabout way to pull data from individual buttons...

**Thoughts**: Sometimes you spend a large amount of time(1 hour in this case) doing something that might be useless. So I'm a bit frustrated about that.

**Total Time: 2:15**

**Link(s) to work**: [Ear trainer app thing](https://github.com/westleyc30/gquiz)

### Day 2: July 15, 2017

**Today's Progress**
NONE. All I'm trying to do is put whats in my html data attribute into a variable and putting that into an object call so I can use buttons to play different sounds. I could do it an easier way I guess but I would have to type more code things. I'd be done if I just used a switch statement but noooooooooOOOOOO I wanna make things easier and now I've spent a couple hours doing something that might not work :{
Oh well at least I might be learning something? The code is same as day 1.

**Thoughts**
Frustrated

**Total Time: 1:24**