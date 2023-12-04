# World of Codecraft Kata

Greetings, and congratulations on being the newest member on the team! We are creating the groundbreaking game *World of Codecraft*. Did we mention you’re the sole member with any experience? You might have to carry us a bit.

What makes the game special? Well, we like to keep things nostalgic, so it’s a text-based and turn-based RPG. Also our strategy is to get rich with minimum investment, though our marketing department said that we shouldn’t let buyers know. *Nostalgic Turn-Based RPG* apparently sells better than *Hopefully a Cash Cow*. 

We currently don’t have anything to show yet, and we hope you might help us out here, with your experience and all.

Buckle up, your coding journey begins! Pixels may be sparse, but imagination goes a long way! (I should talk to marketing about this, we should make that our slogan or something)

## 1 - Humble Beginnings 

First off, we need the ability to create a character in the game. Without that our RPG wouldn’t make much sense, wouldn’t it?

A character:
- is created with a (unique) name
- Starts at level 1

## 2 - A Matter of Life & Death

Great! We really like what you’ve done so far. The first players were able to create characters with enjoyable names (including swearwords, but who has the budget to fix that…)

Didn’t we tell you we released the game after the first feature you built? Ah… well we did. No pressure, but people payed for the game and are eagerly awaiting something to actually do.

We should add the crucial element of life and death to the game. Without it we can’t build anything worthwhile!

- Characters start with 1000HP
- A character dies when its health reaches 0HP

## 3 - Are You Not Entertained?!

Good, players now have characters with health. However, it turns out there isn’t much to do for them yet. Let’s change that.

Time to add the core element of the game: combat.

- Characters can fight each other
- An attack deals 200 fixed damage
- An attack can only damage other characters

## 4 - Leveling Up

Great! Our users can now do something useful in the game. We’ve been getting feedback that they get bored with the game pretty quickly. Maybe we should add some character progression?

- Each kill nets 500 XP
- Cap the level at 10
- Characters level up at 1000XP
- After that, each level requires 50% more XP

## 5 - Experienced Fighters

Players have been really positive about our most recent addition, and are happily grinding away, leveling up their characters. But there have also been complaints saying the level of the character is just vanity and doesn’t change anything.

I hate it when users are correct…

Let’s give them something and see if it sticks.

- Level difference between characters in combat changes damage dealt
- An attacker deals 25% more damage per level he is higher than the defender
- An attacker deals 25% less damage per level he is lower than the defender

## 6 - A Real Hit!

Do you remember that XP thing we added? Players were complaining it’s unfair to only get XP if they kill something. Apparently players were stealing kills from each other.

- Each successful hit nets 50 XP

Also, there appear to be a lot of people with too much time on their hands. Many players have already reached the level cap and are bored.

- Raise the level cap to 80

That’ll keep them occupied for a while

## 7 - Something with Numbers 

Things are looking great! World of Codecraft is getting attention and the userbase is growing.

Let’s see if another feature might pull in even more players! We had this idea about letting characters have stats, groundbreaking right!

- Each lvl increases HP by 100
- We also added attack and defense as stats
- Attack starts at 200
- Defense at 100
- Each level increases attack and defense by 25 points 
- Attack determines damage dealt
- Defenses reduces damage taken

## The Realms Beyond…

At this point we can lean back. The game is doing its thing, players are happily enjoying the game and we’re earning steadily.

What’s that? You want to do more?! Fine… if you insist. Have a look at some ideas we had: 

- Equipping weapons 
- Equipping armor 
- A class system
- Adding Skills

## Retrospective 

Take some time to reflect on the kata. Here are some questions to consider:
- What went well?
- What didn’t go well?
- Which lessons did you learn?
- Would you do something different if you were to start over?

## Rationale

Most code katas are a simple small problem, involving little software design. They also do not simulate the realistic scenario of incrementally building up a system with changing requirements. These scenarios are why we design our software - to enable change. I specifically wanted this kata to stretch slightly beyond that.

This kata can be used to practice:
- Software Design
- Modeling
- Dealing with changing requirements 
- Tidying/refactoring
- Creating feedback loops

## Resources

- [Original Source](http://www.slideshare.net/DanielOjedaLoisel/rpg-combat-kata)
- [Other inspiration](https://github.com/ardalis/kata-catalog)

#kata