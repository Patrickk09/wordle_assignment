# WORDLE ASSESMENT
 Assesment of WORDLE clone written in React, Tailwind.


# steps taken to create

- `npm create vite wordle --template react-ts .`
-  [add tailwind](https://tailwindcss.com/docs/guides/vite)
- I did some google surfing and seems isn't easy


- I started by getting one core algorithm working
  - [found a 5 letter word list that I have used](https://www.thefreedictionary.com/5-letter-words.htm)
    -`copy(Array.from(document.querySelectorAll('.TCont li a')).map(a => a.innerText))`


-  done UI first, switched to making the basic word guess building block
- start making WordRow
  - realize I need to finally to take help from[css grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Relationship_of_Grid_Layout)
  - got initial basic design and then realized i needed to go back to making the core algorithm work
- ok get `computeGuess()` working

- after that I updated props of WordRow and clean up styles somewhat
- spend way too long my whole day to get empty state of the game to have correct default height
- get things deployable for demo assesment 
- Refactor store to save computed guesses into store so I can calculate game state more easily
- this took far too much time than it should have
- some minor refactoring to get isValidWord working.
- added the keyboard 
