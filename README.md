# 100 Days Of Code - Log
<!-- ` ### Day 3: July 17, 2017

Wasn't able to code yesterday so today is the new day three.

**Today's Progress**
Learned some vue.js I kinda like it better than react but I don't really know why. Nothing done on my project but I'm going to be using vue to make it from now on.

**Thoughts**
Pretty neutral about things.

**Total Time: didn't keep track**  -->

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

**Today's Progress**  
  
Created a json file, hosted it on github, successfully brought it down into my js with httpRequest. Learned how to use querySelectorAll to select all buttons and bind individual eventListeners to them using Array.from().forEach like so:
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

**Thoughts**  
  
Sometimes you spend a large amount of time(1 hour in this case) doing something that might be useless. So I'm a bit frustrated about that.

**Total Time: 2:15**

**Link(s) to work**: [Ear trainer app thing](https://github.com/westleyc30/gquiz)
***

### Day 2: July 15, 2017

**Today's Progress**  
  
NONE. All I'm trying to do is put whats in my html data attribute into a variable and putting that into an object call so I can use buttons to play different sounds. I could do it an easier way I guess but I would have to type more code things. I'd be done if I just used a switch statement but noooooooooOOOOOO I wanna make things easier and now I've spent a couple hours doing something that might not work :{
Oh well at least I might be learning something? The code is same as day 1.

**Thoughts**  
  
Frustrated

**Total Time: 1:24**  
***


### Day 3: July 17, 2017

Wasn't able to code yesterday so today is the new day three.

**Today's Progress**  
  
Learned some vue.js I kinda like it better than react but I don't really know why. Nothing done on my project but I'm going to be using vue to make it from now on.

**Thoughts**  
  
Pretty neutral about things.

**Total Time: didn't keep track**
***


### Day 4: July 18, 2017

**Today's Progress**  
  
Learned how to create a single page vue application(kinda). No personal project work. I would like to figure out how to put different template pieces into the same page. 

**Thoughts**  
  
Pretty neutral about things.  

**Total Time: 1:26**
***


### Day 5: July 19, 2017

**Today's Progress**  
  
Learned more vue. Props

**Thoughts**  
  
Pretty neutral about things. Again. I should really write these things day of instead of day after. I keep confusing my dates.

**Total Time: 0:47**
***


### Day 6 & 7: July 20 & 21, 2017

**Today's Progress**  
  
Learned some mongodb specifically:
1. how to run it on localhost >mongod
                              >mongo
2. switching into the database you want > use databaseName
3. updating database info > db.collectionName.update({"prop":"data"})
4. using $set and $addToSet to add to collection
5 db.name.remove({"":""}) to remove collection  

 I'll have to organize this better so I know what I'm writing here in the future  
   
**Thoughts**  
  
Pretty good idea of what I'm doing with mongo so I feel good about that. But I'm having trouble thinking up ways to organize my data in my app thing. But it shouldn't be to hard. I'm *REALLY* having trouble understanding how vue.js and node go together with express.js or should I leave express out? Are express and vue interchangable? bleh  


**Total Time: 20th: 1:55, 21st: 2:05**
***

### Day 8: July 25th, 2017

**Today's Progress**  
  
Worked on building a menu in vue based on what items I can pull down from a JSON file I stored on github. It worked, but, I want it to populate the menu items automatically. So when I add a new chord to the JSON file it makes a new list item. Oh well, another day perhaps. It wouldn't take too much time to just add lines to the vue file.
   
**Thoughts**  
  
Feel good. I may have not have progressed much but I learned how to do something.  

[link to the thing](https://codepen.io/westleyc30/pen/jwgzpK?editors=0010)


**Total Time: 1:00*
***

### Day 9: July 26th, 2017

**Today's Progress**  
  
I took what I made yesterday and made it ugly
   
**Thoughts**  
  
eh 

[link to the thing](https://codepen.io/westleyc30/pen/jwgzpK?editors=0010)


**Total Time: ???*
***

