<h1 align="center"><a href="https://retroachievements.org/game/15758">Crazy Kong (Arcade)</a></h1>

<p align="center">
  <span>6/10 Difficulty</span>  •
  <span>Multiple Playthroughs</span>  •
  <span>20-30 Hours</span>
</p>

<p align="center">
  <span>Developed by <a href="https://retroachievements.org/user/WCopeland">WCopeland</a></span>  •
  <span><a href="https://github.com/wescopeland/RAScripts/blob/main/sets/Crazy%20Kong.rascript">RAScript</a></span>
</p>

<p align="center">
  <img src="https://i.imgur.com/YysSetR.png" width="400">
</p>

---

## About the Author

Hi! I'm Wes. Thanks for your interest in the Crazy Kong set. Many years ago [I developed an interest in the arcade Donkey Kong series](https://arstechnica.com/gaming/2016/05/is-this-the-worlds-first-perfect-game-of-donkey-kong/). I'm hoping this set could help spark an interest with you, and I'm hoping I can help you unlock the secrets to mastering it.

---

## Introduction

Crazy Kong is a 1981 arcade game developed and published by Falcon. It's a clone and "official" bootleg of the classic arcade game [Donkey Kong](https://retroachievements.org/game/11943), with some slight modifications made to the gameplay to accommodate Crazy Kong's much weaker hardware.

Nintendo distributed Donkey Kong to the United States and Japan. Falcon distributed Crazy Kong to the rest of the world. Legendary arcade gamer Ben Jos Walbeehm, the first player to beat Billy Mitchell, had grown so accustomed to Crazy Kong he once referred to Donkey Kong as being the bootleg title between the two.

The objective is the same as the original Donkey Kong. You, Jumpman, must navigate four different platforming levels while avoiding obstacles and enemies to save the girl, Pauline.

There are four different types of stages: barrel boards, conveyors (also known as pie factories), spring boards, and rivet boards.

The game starts at L=01 **and ends at L=22.** Each level consists of four stages: barrel, conveyor, spring, and rivet, in that order. Stage 22-1 is the 85th stage of the game.

Due to hardware limitations, only four barrels can be on-screen at any time. On the barrel stage, there can only be a single fireball active at once. On the conveyor stage, only two fireballs can ever be active at once. This is a stark contrast to Donkey Kong, which hurls many more obstacles and enemies your way.

These limitations mean **Crazy Kong is significantly easier than Donkey Kong.** I am convinced that with enough practice, anyone can reach L=22 and finish the game.

---

## Gameplay Mechanics You Must Understand

There are several quirks of Crazy Kong's (and by extension, Donkey Kong's) programming you can take advantage of to turn the tables in your favor.

### You Control the Barrels

That's right. You control all of the barrels on the screen. "Barrel control" steadily increases until you hit L=05, at which point you have "maximum control".

How exactly does barrel control work? **Barrels respond to your current joystick direction.** If you are pointing the joystick towards a ladder and a barrel is rolling over that ladder, there is an increased likelihood the barrel will go down that ladder. This control starts at roughly 25% on L=01, and increases to 75% by the time you have reached L=05.

Knowing this, you can manipulate all the barrels on the screen to do your bidding. Take a look at the video below:

<img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Barrel%20Control.gif?raw=true" height="400">

<br>

### Barrels Can Be Dodged With 100% Precision

This is an exploit that exists in Crazy Kong, but not Donkey Kong. It is called the "ladder trick". Take a look at the video below:

<img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Ladder%20Trick.gif?raw=true" height="400">
<br><br>

That's right, when barrels are rolling over you and you're near the top of a ladder, they will never roll down the ladder and kill you. This was in the earliest versions of Donkey Kong (which Crazy Kong's code is based on), but was later patched by the game's developers because they found it made Donkey Kong too easy! Fortunately, the exploit still exists in Crazy Kong.

### There is Only ONE Correct Way to Play the Rivets

The rivet board will be the most dangerous board in Crazy Kong. It is _essential_ that you learn to play it correctly if you want to make it to L=22. The proper way to play the rivet board is by using something called the "Star Pattern".

With the Star Pattern, you clear most of the left-hand rivets, grab the left hammer, and run across while clearing the final left-hand rivet.

**Read that carefully a few times and be sure you understand it.** Here's a video demonstration:

<img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Star%20Pattern%203.gif?raw=true" height="400">
<br><br>

On the rivet stage, when you smash fireballs with the hammer, **they will respawn on the opposite side of the screen that you're standing on.** In other words, you can force them to respawn on the left-hand side of the screen (where they can no longer hurt you). Nice!

### The Fireballs are Random, but Follow Predictable Rules

These are the rules you need to memorize:
* Fireballs will _only_ go down ladders if you are below the fireball in terms of your current screen position.
* Fireballs will _only_ go up or down a ladder if they approach the ladder from the left-hand side.
* When a fireball freezes in place, it will always unfreeze by moving left. It will never unfreeze by moving right.
* Only two fireballs are capable of freezing.
* Fireballs are not aware of your presence, they float around mindlessly.
* On a rivet stage, fireballs will respawn on the opposite side of the screen that you're currently standing on. If you're on the right-hand side, they'll respawn on the left-hand side, and vice versa.

---

## Walkthrough

### Progression Achievements

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325543.png">

```
How High Can You Try [5 Points]
Clear 1-1
```

This is very simple: clear your first barrel board. The only caveat to this barrel board is you have extremely limited barrel control.

One tip to keep in mind: the bottom hammer can oftentimes be a trap! The safest way to play barrel boards is to skip it and only grab the top hammer. You can use the top hammer like a shield. Take a look at this video:

<img src="https://user-images.githubusercontent.com/3984985/223606898-387c43d7-0fd6-4411-ab89-939e4952ee60.gif" height="400">

<br><br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325545.png">

```
Only 20 More Loops Left [5 Points]
Clear 1-4
```

For any new player, getting this achievement is a great accomplishment. You will have successfully cleared all four board types! Here are videos for how to clear 1-2, 1-3, and 1-4. Take special note of the Star Pattern being used to clear 1-4. Remember, **it is the only correct way to play the board.**

By reaching this achievement, you will also have earned your bonus man at 7000 points. You only have four lives to finish a game of Crazy Kong! In other words, each life should last you 6 levels (around 21 boards).

| Conveyor | Spring | Rivet |
|---|---|---|
| <img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Basic%20Conveyor.gif?raw=true" height="300"> | <img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Basic%20Spring.gif?raw=true" height="300"> | <img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Basic%20Rivet.gif?raw=true" height="300"> |

<br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325546.png">

```
Novice of the Arcade [5 Points]
Clear 2-4
```

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325547.png">

```
Student of the Arcade [10 Points]
Clear 3-4
```

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325548.png">

```
Enthusiast of the Arcade [10 Points]
Clear 4-4
```

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325549.png">

```
Adept of the Arcade [10 Points]
Clear 5-4
```

These achievements should all play out fairly similarly. Some things to note as you progress through this:

* The speed of fireballs and springs will increase with each level.
* Your barrel control will increase with each level. Always be thinking about it on barrel boards.
* After clearing L=04, you will have reached "max difficulty". The game gets no harder than this!

If you are serious about your learning, I recommend immediately moving on to working on the next achievement...

<br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325550.png">

```
Veteran of the Arcade [25 Points]
Clear 4-4 on your very first life
```

Donkey Kong circles refer to this as "getting a start". On your first life, you've reached maximum difficulty. Because you have the most barrel control at maximum difficulty, generally L=05+ is considered easier (less random) than levels 1 through 4. It is common practice for Donkey Kong players to reset their game if they do not reach 5-1 on their first life.

<br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325551.png">

```
Prodigy of the Arcade [25 Points]
Score 200,000 points
```

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325552.png">

```
Master of the Arcade [25 Points]
Score 400,000 points
```

After you're used to getting a start, you should earn these naturally with a little bit of practice. As a measuring stick, you'll likely score 400,000 points somewhere around L=17.

### Technique Achievements

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325553.png">

```
Oil Can Antics [5 Points]
Jump to the top of the oil can on any barrel board
```

This is actually a bug in Crazy Kong. Doing this in Donkey Kong results in Jumpman's death. This trick isn't particularly valuable, but was added to the set to highlight there are subtle differences between the two games, and Falcon's reverse engineering wasn't 100% perfect.

<img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Oil%20Can%20Antics.gif?raw=true" height="400">

<br><br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325554.png">

```
Barrel Bounce [5 Points]
Leech the first falling barrel on 1-1 for 100 points
```

When Kong drops the first barrel on 1-1 straight down, you can straight jump next to it as it falls for a free 100 points. This is **much** easier if at the apex of your jump, you hold the joystick either left or right. Holding the joystick in a direction increases the "window" which the game detects if you are jumping over an object. In other words, it makes it easier to score points off something next to you on the screen.

This is a basic point pressing technique that is very common in high-level games. "Point pressing" is a term used for squeezing out points from the game, oftentimes in unintended ways. In high-level play, it is essential to point press, given that there is an ending to the game. Every point counts!

<img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Barrel%20Bounce.gif?raw=true" height="400">

<br><br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325555.png">

```
Hammered Out I [5 Points]
Successfully finish a barrel board after using both hammers
```

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325556.png">

```
Hammered Out II [5 Points]
Successfully finish a conveyor board after using both hammers
```

These should both be fairly straightforward. As a reminder, the conveyor board is the 2nd stage of each level, ie: 1-2, 2-2, 3-2, etc. The important thing about these achievements is you can't suicide while grabbing the hammers. You must actually clear the stage before the achievements are awarded. This forces you to be thoughtful while wielding the hammers themselves.

<br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325557.png">

```
Barrel Manipulator I [2 Points]
By pointing the joystick towards barrels as they rolled over ladder tops, you forced ("steered") 10 of them down the ladders.
```

It is very likely you will unlock this achievement completely by accident. The whole point of this achievement is to get you thinking about how you control the barrels on the screen. In case you need a refresher, [check the section on barrel control](#TODO) in this guide.

<br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325558.png">

```
Barrel Manipulator II [3 Points]
Use the ladder trick to dodge 2 barrels in a row (Note: the ladder trick is when you climb a ladder and wait at the top, which forces barrels to roll by)
```

Also very simple, just use the ladder trick and let two barrels roll by before getting off the ladder. In case you need a refresher on the ladder trick, [check this part of the guide](#TODO).

<br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325559.png">

```
Barrel Manipulator III [5 Points]
Use the ladder trick to dodge 8 barrels in a row
```

Still simple, you just need to be sure a fireball doesn't climb up and kill you. Camp near the top of a ladder on any barrel board and after several seconds this should unlock. If you don't remember what the ladder trick is, [check here for a refresher](#TODO).

<br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325561.png">

```
Barrel Manipulator IV [10 Points]
Steer barrels down ladders 45 times on any barrel screen
```

Time to prove your barrel control skills! Pro tip: don't attempt this unless you are on L=04 or higher. It's best to do this when your barrel control is at maximum, which only happens as the game approaches max difficulty. If you need a refresher on barrel control, [click here](#TODO).

### Challenge Achievements

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325562.png">

```
Conveyor Collector [5 Points]
Collect all three of Pauline's items on any conveyor board and finish the stage
```

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325563.png">

```
Spring Scavenger [5 Points]
Collect all three of Pauline's items on any spring board and finish the stage
```

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325564.png">

```
Rivet Retriever [5 Points]
Collect all three of Pauline's items on any rivet board and finish the stage
```

All three of these should be quite simple, especially if you attempt them on L=01 when the fireball speed is the lowest. Remember, it is not enough to suicide while getting the items, you must complete the stage after the items have been retrieved.

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325565.png">

```
Barrel Vaulting Pro [10 Points]
Make corrupted graphics appear by leaping over three obstacles in a single jump
```

Because only a maximum of 4 barrels can be present on the screen at any time, this can get tricky. Consider this your final test of barrel control. You will likely need to be quite comfortable with steering and manipulating barrels to be able to unlock this achievement. It is best attempted when you have maximum control, around L=05+.

<img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Barrel%20Vaulting%20Pro.gif?raw=true" height="400">

<br><br>