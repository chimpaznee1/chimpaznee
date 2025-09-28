---
layout: post
title:  "Penchant: A Two Days' Mistake"
date:   2025-09-28
categories: jekyll update
---
<a href="https://penchantpuzzlehunt.com/">Penchant Puzzlehunt</a> was a fantastic hunt, but a single mistake that may have cost me two whole days and robbed me of the intended experience. Now is a good time to write about this hunt, now that I'm much less salty about my blunder and have my own github page. I solved this hunt solo, on team Errant Chronology of /r/PictureGame. Unmarked spoilers for everything Penchant, obviously.

<h1>The Beginning</h1>

<a href="https://penchantpuzzlehunt.com/puzzle/playing-with-places">Playing with Places, Part 1</a>: The info page suggested looking at the meta early, so I opened it before looking at any of the feeders. With just flavour text, I could not solve anything, but I had a decent chance at guessing what will happen. Before solving any puzzle, I figured out this is London Monopoly. I remembered that there are 28 Monopoly properties, so if you don't count the two utilities, there are 26. The puzzle number. Seems simple, but unfortunately, I'd make a fatal mistake later.

<h1>Feeders</h1>

<a href="https://penchantpuzzlehunt.com/puzzle/plainly-indicated">Plainly Indicated</a>: A few days before the hunt, I did the first four sections of the <a href="https://docs.google.com/spreadsheets/d/1RD-kBhdaIeUIpP_gTws15uiSefYbGdHB_YSJq6-NqVo/edit">maven exam</a>, both to refresh my memory and to learn how to use more sheet functions than I'm used to. It showed - For each clue, I used a set of 26 fairly big XLOOKUPs to compare the ciphertext and the plaintext and output the result as an array into a column.<sup id="fnref1"><a href="#footnote1">[1]</a></sup> It was more efficient than doing it by hand, and was a fun little puzzle to do while simultaneously solving the actual puzzle. Also, I liked the do-it-again at the end, and all the unique-letter clues are very clever!

<a href="https://penchantpuzzlehunt.com/puzzle/penchant-word-search">Penchant Word Search Generator™</a>: Had to take a hint here, because I can't read (the hint was to look at the letters in the unused spaces). Probably got the correct variance numbers because I put 100,000 word searches in my sheet. It was a fun puzzle, but I thought the first part was disconnected from the second part.

<a href="https://penchantpuzzlehunt.com/puzzle/youre-missing-something">You're Missing Something</a>: I was happy to solve the devilry clues where the answers are not words (WHL, OHL) after co-authoring a puzzle with devilries that have non-word answers, however I thought the author was very merciful by giving us enumerations. Not gonna lie it's crazy that the puzzle made me come up with QMJHL with only 6 letters as a clue.

<a href="https://penchantpuzzlehunt.com/puzzle/reportedly">Reportedly</a>: This is a work of art. My aptly-labelled parse column:

<img src="/chimpaznee/assets/img/penchant-recap/reportedly.png">

I got the wordplay of SUCH and LOAFS later, after filling in the grid. I'd like to contest the English pronunciation of SINAI. It is very wrong! In Hebrew it's pronounced see-NAI, which is how I've known it my whole life.

<a href="https://penchantpuzzlehunt.com/puzzle/gas-water-electricity">Gas, Water, and Electricity</a>: This is the only feeder I didn't frontsolve. I knew the grid is a torus but couldn't figure out how the lines are laid out. I eventually backsolved the puzzle. Skill issue.

<a href="https://penchantpuzzlehunt.com/puzzle/rereading">Rereading</a>: I don't have many comments on the puzzle itself, but this is the second one where I put my newly-learned sheet tricks to good use. I used XLOOKUP to put the letters in the cells and make my life much easier. I'm normally the biggest acrostic hater on the planet, but now I have a solution to my chief complaint about them.

<a href="https://penchantpuzzlehunt.com/puzzle/pen-paper-logic">Pen-and-Paper Logic Puzzles: An Introduction</a>: I solved the "fair" version of this puzzle, after all the errata. This took me several hours, and what a journey it was. It was clear each puzzle was far from unique on its own, and I found it highly sus that the Koburin, Slalom and Yajilin all have the same pattern of shaded cells, so I used the graph to try to combine three different puzzles to get a new unique puzzle, and do it nine times. The first few combined puzzles were hard to find, but with some trial and error, and ruling out some incompatible candidates, I did it! I had to error-correct the final extraction several times before getting something like "TOBACCORO*" which was enough to obtain the answer. Fantastic set of logic puzzles, I can't imagine all the constraints Thomas and Zach (who I didn't know as logic puzzlers) worked with.

<a href="https://penchantpuzzlehunt.com/puzzle/blank-matchmaker">Blank Matchmaker</a>: This puzzle stood out as being substantially "faith" in the Logic/Magic/Faith triangle, in a hunt where nearly everything is logic or magic. And there was a lot of faith - it started with Nutrimatic of a few entries (a few major My Little Pony characters) and quickly spiralled out of control (hundreds of Animal Crossing villagers). It's a cool idea, but required too much research to my taste, because some of the character lists are too damn big!

<a href="https://penchantpuzzlehunt.com/puzzle/oh-just-a-criss-cross">Oh, Just a Criss-Cross</a>: This puzzle made me suspicious of the "puzzle types" described in the intro page because it is also a cryptogram. Because the words don't form sentences, I solved the two cryptograms by hand instead of using quipqiup. I don't think this was a bad decision, because I liked the little logic puzzle and wasn't trying to be competitive. Something about finding 26 phrases of two words starting with 26 unique letters felt very elegant.

<a href="https://penchantpuzzlehunt.com/puzzle/ladders">Ladders</a>: This is the first puzzle I solved, a trait I share with many teams. That's many interpretations of "one" and "off by one<sup id="fnref2"><a href="#footnote2">[2]</a></sup>". Fun and elegant!

<h1>Metapuzzles</h1>

<a href="https://penchantpuzzlehunt.com/puzzle/playing-with-places">Playing with Places, Part 2</a>: After solving my first puzzle, I had the answer SHAW THEATRE<sup id="fnref3"><a href="#footnote3">[3]</a></sup>. This is a place on London's Euston Road, easily extracting an E. Then I got my next 5 answers and did not see a connection to Monopoly properties. I still think it's weird only SHAW THEATRE is very strongly connected, while for all other answers, you have to think. It's only when I got CIGARETTE (my 7th solve) that I found a second link. It was the wrong one (Marlborough Street), but it encouraged me to find links for my remaining answers, which I managed, except for an ambiguity regarding IVORY. I then fixed CIGARETTE in order to get an answer ending with "GAME". In a perfect world, I would've been able to wheel-of-fortune the final answer.

But then my fatal error affected me.

<img src="/chimpaznee/assets/img/penchant-recap/ouch.png">

I accidentally swapped the order of two puzzles. And the cost was two hints spent on the meta, one hint on <i>Penchant Word Search</i>, and a lot of time. This tiny mistake gave me the illusion that the meta is really hard. Despite having most feeders, there were teams far ahead of me on the leaderboard who haven't finished. But then the second hint finally pointed out my problem, and I solved the puzzle. I also haven't noticed the titles' first letters until the hint told me. How tragic. But now there are more metas to solve!

<a href="https://penchantpuzzlehunt.com/puzzle/playing-with-words">Playing With Words</a>: Scrabble meta! This was a completely different story from <i>Playing with Places</i> - I aced this. However, the hint for <i>Penchant Word Search</i> may have been more helpful than I realized - POLARITIES appears quite early in the solve path and has two other words attached to its branch. It's also hard to backsolve from "Northumberland". When I solved <i>Playing With Words</i>, I had all answers - I'd already backsolved <i>Gas, Water and Electricity</i> from <i>Playing with Places</i> by guessing the answer has 5 letters.

<a href="https://penchantpuzzlehunt.com/puzzle/playing-with-letters">Playing With Letters</a>: I don't have a lot to say about this - it was short.

<a href="https://penchantpuzzlehunt.com/puzzle/playing-with-markers">Playing With Markers</a>: I solved all minipuzzles except for the third one, so I regret to inform everyone that I've never got laid. Holy hell the metameta for this is surely contrived.

<a href="https://penchantpuzzlehunt.com/puzzle/playing-with-cards">Playing With Cards</a>: This was really cool, and I find it hard to believe it was 100% spaghetti! I don't play Poker regularly, but for some reason I loved every poker meta that I solved in 2024 and 2025. <a href="https://www.puzzlerojak.org/puzzle/fortius.html"><i>Fortius</i></a> from Puzzle Rojak was one of my favourite puzzles from 2024. <i>Playing with Cards</i> was very good too, and my headcanon is that the Spades were used to dig a dump for all the weird goth letters, while Clubs only admitted useful letters and J. More poker metas please!

<a href="https://penchantpuzzlehunt.com/puzzle/playing-with-others">Playing With Others</a>: I got baited by a shiny red herring dangling on a stick. I thought the diagonal arrow in the square pointed at "GO" in Monopoly, since each meta supposedly gives 2 letters. With these two letters being fixed in place, I could find a different cycle (but admittedly awkward in two places):
- His own game is Greek Hold 'Em, which has 11 letters, and is convincing because the game is viewed from the dealer's perspective. I don't remember the solution to this game - I think it was unique, but you had to put a spade in your hand.
- There is one one answer in <i>Markers</i> that gives two letters rather than one, and they are marked by a red X.
- This is the most tenuous one, you can find two words that give you the two blanks that collectively have 13 letters, but there is no way to determine their order. I should've heeded this warning sign.
- On <i>Words</i>, there are two extraction letters that are placed on double-letter squares.
- Finally, "ITS IN THE BAG" means you get the Monopoly letters for free.

Solvers will always find a way to BE NOISY or find other convulted non-solutions to their problems, and I was so tunnel visioned that it took a hint to get me out of the hole I dug myself into. I was just happy I didn't have to learn the rules of Diplomacy (the board game).

<h1>Conclusion</h1>

I finished the hunt - or did I? There was a secret puzzle at the end, an exercise for true Penchanters.

Thank you Team Penchant for this hunt! I still wish I could get the experience of solving the first meta earlier, but after coming to terms with my invocation of Murphy's Law, I'm content.

<h1>Footnotes</h1>

<p id="footnote1">1. I later figured out how to use ARRAYFORMULA to reduce this to just one function per clue. <a href="#fnref1">&#8617;</a></p>

<p id="footnote2">2. As I wrote this, an oboe was sounded in the distance. <a href="#fnref2">&#8617;</a></p>

<p id="footnote3">3. How prescient! <a href="#fnref3">&#8617;</a></p>