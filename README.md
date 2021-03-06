Star Raiders for Atari 800 Source Code ~~Multiplayer Notepad~~ Type-In Project
==============================================================================

Odds are that you're here because you read [KevinSavetz's Tweet](https://twitter.com/KevinSavetz/status/654837470157139968)'s or saw [Knimrod's post on Atari Age](http://atariage.com/forums/topic/243904-star-raiders-source-code-to-be-released).  If not, then let me explain...

What
----
The source code for [Star Raiders](https://en.wikipedia.org/wiki/Star_Raiders) has been made [available on the Internet Archive](https://archive.org/details/AtariStarRaidersSourceCode).  Even though the listing has been run through optical character recognition software, the vast majority of the text is gibberish (at best; at worst, it's simply omitted).  As much as we like to think that "technology can do anything", the fact of the matter is "no, it can't": reading is essentially pattern-matching and computers just plain suck at it compared to... well, anything with a brain, really.  (Yes, even a politician...)  So... we want people to look at some scanned documents, type in what it says, and... uhm... well, that's it, actually.

Why
---
Short version?  Because it's inevitable.  A fully-digitized, ready-to-download, accurate copy of **Star Raiders** *will be* on the Internet.  So why not be one of those few, those happy few, that band of brothers, which makes it possible to stand in front of future generations saying "These sources code I typed on St. Foobar's Day!"?

Even shorter version?  Because you want to.  And you know you want to.

How
---
Look at the text files in the master branch.  Each one corresponds to a page of the source code.  Find out what page is missing, head over to the [source code](https://archive.org/details/AtariStarRaidersSourceCode), and start typing.  Like I said, it's so simple even a politician can do it.  

That said, there is one thing which disqualifies your typical politican: you must be *faithful* and *true*.  This project isn't about revisionism, improving existing code, or inflating your ego: it's about preserving existing, historic, and significant code - warts and all.  Your task (should you choose to accept it) is to type into a file what a printer printed on a piece of paper.  No embellishments, no commentaries, no improvements, no explanations: just the facs (facsimilie, that is).

Most of the source code is in one of the following formats:
```
                 	;
                 	;	COMMENT
    AAAA         	LABEL
    AAAA BB      	LABEL	OP
    AAAA BB CC   	LABEL	OP	ARG
    AAAA BB CC DD	LABEL	OP	ARG
    AAAA BB CC DD	LABEL	OP	ARG	; COMMENT
```
...and so on.  The exact number of combinations I leave to the reader as homework in combinatiorials (No, the answer is not in the back of the textbook).  In these examples, `AAAA` represents a two-byte address; `BB`, `CC`, and `DD` represent one byte of operands, arguments, and/or memory contents; an optional `LABEL`; `OP` and `ARG` which are the assembler instructions; and `COMMENT`, which, if present, must be copied verbatim ad literatim.

The exact format of how these bits of data are arranged is both paramount and trivial at the same time.  I know that sounds contradictory, but you should keep in mind that the source code was put together by many people and every person has/had his/her own way of writing.  As a result, the **Star Raiders** source code is somewhat inconsistent.

Think of it this way: Do you use two spaces after a period?  Do you indent the first line of your paragraphs or do you skip a line in between paragraphs?  Do you write "Two Strippers, Kennedy, and Stalin" or "Two Strippers, Kennedy and Stalin"?   Now imagine a bunch of people writing a book together.  You can see how with eight people, each possible combination of writing style would clash within the same book.

Now, unlike the examples I've cited, the differences in source code styles are invisible.  You may have heard of it; it's called [whitespace](https://en.wikipedia.org/wiki/Whitespace_character#Computing_applications).  For the most part, `LABEL`s, `OP`s, `ARG`s, and `COMMENT`s are aligned with horizontal tabulation.  As a result the text will line up quite nicely and quite easily.  For the lesser part (as is "not 'for the most part'"), you'll have to figure it out.  Here are your guidelines:

 1. There are eight spaces per tab.
 2. Each line begins with thirteen characters followed by a tab.
 3. If you don't know how to set your tabs then don't use tabs at all - just use spaces.

(If 8 spaces per tab is against your religion, tough: it's against my religion, too, so you have no excuse.  `Space` it `XOR` `Tab` with 8.  Capisce?)

How *Not*
---------
If you find a blank file and it's not your doing, don't touch it.  If you start working on a page, finish it.  If you want kudos, earn it.  If you want to brag, GitHub's metadata whozitswhatsits will be brutally honest about what you did[n't] do.  If you do sloppy work, you'll be banned.  If you're responsible, you'll reap the privileges.  And if you take cranberries and stew them like applesauce they taste much more like prunes than rhubarb does.

Final Thoughts
--------------
No matter how you type, be consistent.  Assume that you're going to make mistakes.  Assume they'll be found.  Make it easy on the guy/gal who'll be fixing your mistakes (because that person might be you!).  Scrutinize what you're transcribing twice, that way you only have to key it in once.

And, even though it's at the top of every page, you do not have to type `STAR RAIDERS,	VERSION 25.1	STARDATE 26-JUL-79` in each file.  If you want to, do; if not, don't.  Either way, be consistent, keep true to the original, and thank you you've been a wonderful audience!

Cast
=================
 * xıoɴʏᴄ (a/k/a `XioNYC`)
 * `edburns`
 * `jzatarski` 
 * Kevin Savetz (a/k/a `savetz`) who has made this work ~~possible~~ necessary
 * Typists Like You.
