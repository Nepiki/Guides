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

It is very likely you will unlock this achievement completely by accident. The whole point of this achievement is to get you thinking about how you control the barrels on the screen. In case you need a refresher, [check the section on barrel control](#you-control-the-barrels) in this guide.

<br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325558.png">

```
Barrel Manipulator II [3 Points]
Use the ladder trick to dodge 2 barrels in a row (Note: the ladder trick is when you climb a ladder and wait at the top, which forces barrels to roll by)
```

Also very simple, just use the ladder trick and let two barrels roll by before getting off the ladder. In case you need a refresher on the ladder trick, [check this part of the guide](#barrels-can-be-dodged-with-100-precision).

<br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325559.png">

```
Barrel Manipulator III [5 Points]
Use the ladder trick to dodge 8 barrels in a row
```

Still simple, you just need to be sure a fireball doesn't climb up and kill you. Camp near the top of a ladder on any barrel board and after several seconds this should unlock. If you don't remember what the ladder trick is, [check here for a refresher](#barrels-can-be-dodged-with-100-precision).

<br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325561.png">

```
Barrel Manipulator IV [10 Points]
Steer barrels down ladders 45 times on any barrel screen
```

Time to prove your barrel control skills! Pro tip: don't attempt this unless you are on L=04 or higher. It's best to do this when your barrel control is at maximum, which only happens as the game approaches max difficulty. If you need a refresher on barrel control, [click here](#you-control-the-barrels).

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

<br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325565.png">

```
Barrel Vaulting Pro [10 Points]
Make corrupted graphics appear by leaping over three obstacles in a single jump
```

Because only a maximum of 4 barrels can be present on the screen at any time, this can get tricky. Consider this your final test of barrel control. You will likely need to be quite comfortable with steering and manipulating barrels to be able to unlock this achievement. It is best attempted when you have maximum control, around L=05+.

<img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Barrel%20Vaulting%20Pro.gif?raw=true" height="400">

<br><br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325587.png">

```
Proper Rivet Form [10 Points]
Execute the Star Pattern on any rivet board
```

Remember: the Star Pattern is the **ONLY** correct way to play the rivet board. By unlocking this achievement, you will have done the Star Pattern correctly.

To recap, you want to take the bottom left rivet first, then the top two rivets in whatever order you prefer, then take the left hammer, then run across and smash whatever you can.

<img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Star%20Pattern%203.gif?raw=true" height="400">

<br><br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325567.png">

```
Heat Seeker I [10 Points]
Leech the fireball on 1-1 for 100 points as it jumps out of the oil can
```

After a few tries, you'll start finding this is a very easy point-pressing trick to perform. When the fireball jumps out of the oil can, you can squeeze 100 points by also jumping to the right. Take a look:

<img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Heat%20Seeker%20I.gif?raw=true" height="400">

<br><br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325568.png">

```
Heat Seeker II [10 Points]
Score 1,000 points before climbing a single ladder
```

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325569.png">

```
Heat Seeker III [25 Points]
Score 1,000 points before climbing a single ladder and before the bonus timer hits 4300
```

Now that you have the hang of leeching the fireball for 100 points, it's time to step it up a little bit. You can repeatedly leech the same fireball for 100 points, as well as get bonuses by leeching it and barrels simultaneously! This will take some practice, but hopefully the video below can offer some inspiration on how this can be done:

<img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Heat%20Seeker%20III%202.gif?raw=true" height="400">

<br><br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325570.png">

```
Super Smasher I [5 Points]
Get 3 smashes with a single bottom hammer on any barrel board
```

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325571.png">

```
Super Smasher II [5 Points]
Get 4 smashes with as ingle top hammer on any barrel board
```

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325572.png">

```
Super Smasher III [10 Points]
Get 6 smashes with a single bottom hammer on any barrel board
```

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325573.png">

```
Super Smasher IV [10 Points]
Get 7 smashes with a single top hammer on any barrel board
```

The first four Super Smasher achievements all take place on barrel boards. To maximize your odds of unlocking these, you want to ensure you don't waste any swings. In other words, the very first swing of the hammer should be smashing a barrel board.

For the bottom hammer, wait until there are four barrels on the screen to smash. While holding the hammer, do your best to steer them down ladders so they get to you faster. It's also advantageous if you're able to smash the fireball.

For the top hammer, you'll need to be steering constantly as well as smashing barrels as they roll down ladders overhead.

<br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325574.png">

```
Super Smasher V [10 Points]
Get 5 smashes with a single middle hammer on any conveyor board
```

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325575.png">

```
Super Smasher VI [25 Points]
Get 5 smashes with any single hammer on the rivet board
```

The final two Super Smasher achievements are a bit trickier and rely a bit more on luck, as you cannot directly influence the objects you're smashing on these stages.

For the conveyor board, wait until you see at least two "pies" on the conveyor before picking up the hammer. Once you're holding the hammer, try to walk towards the side of the screen where pies are spawning in from. Smash them as they spawn.

For the rivet board, you'll have to get lucky with one of the hammers. The achievement will unlock with either one, but you need to get five smashes with a single hammer. One trick is to do the Star Pattern, smash fireballs (and force them to respawn on the left), then walk to the left and smash them again! This totally relies on _where_ they spawn, but you can often squeeze out an extra smash with this technique.

<br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325580.png">

```
Barrel Phantom Hammer [10 Points]
On any barrel board, grab the top hammer first and the bottom hammer second
```

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325581.png">

```
Rivet Phantom Hammer [5 Points]
On any rivet board, grab the left hammer first and the middle hammer second
```

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325582.png">

```
Conveyor Phantom Hammer [5 Points]
On any conveyor board, grab the left hammer first and the middle hammer second
```

There is nothing particularly special about these hammers. These achievements are present mostly to ensure you're aware this programming error in Crazy Kong exists. For whatever reason, when grabbing a certain hammer first, the other one becomes invisible. This can be incredibly annoying on the rivet board in particular. Though invisible, the hammer can still be used.

<br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325583.png">

```
Elevator Elite [5 Points]
On any spring board, leech the fireball for 100 points while riding the elevator
```

Test your point-pressing skills! This is, of course, dependent upon if the fireball is descending or ascending the ladder while you're riding the elevator, but it should happen several times in a single game. Be sure to hold the joystick left or right during the apex of your jump to increase the odds that you are awarded points.

<img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Elevator%20Elite.gif?raw=true" height="400">

<br><br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325584.png">

```
Spring Board Elite [5 Points]
Leech a spring for 100 points on the right-hand side of any spring board
```

Isn't it interesting that everything in the game which can kill you is also able to award you points? The springs are no exception. Remember to hold left or right at the apex of your jump to increase your odds of earning the points.

<img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Spring%20Board%20Elite.gif?raw=true" height="400">

<br><br>

### Speedrun Achievements

These achievements will require a lot of practice and patience. Also keep in mind they must be attempted at L=05+. There is not enough bonus time in the earlier levels to pull these achievements off.

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325576.png">

```
Turbo Barrel [10 Points]
Finish a barrel board with at least 6800 left on the timer
```

The easiest of the speedrun achievements. Ignore the hammers and immediately bolt for the top (this will be a recurring theme). Exploit the ladder trick if at all possible.

<img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Turbo%20Barrel.gif?raw=true" height="400">

<br><br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325577.png">

```
Turbo Conveyor [25 Points]
Finish a conveyor board with at least 6800 left on the timer
```

This one will require a little bit of luck, but it's likely that the game will eventually just hand this one to you once you're proficient at playing on max difficulty. This will come down to how cooperative the fireballs and retracting ladders are. Eventually you'll get a fast pattern and will be able to nail this.

<img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Turbo%20Conveyor.gif?raw=true" height="400">

<br><br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325578.png">

```
Turbo Spring [50 Points]
Finish a spring board with at least 6700 left on the timer
```

The speedrun achievements aren't messing around anymore. This will be quite challenging, even for seasoned experts. Your jumps between the elevators and platforms need to be extremely optimized, and you cannot afford to hesitate with the springs.

<img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Turbo%20Spring.gif?raw=true" height="400">

<br><br>

```
Turbo Rivet [50 Points]
Finish a rivet board with at least 5000 left on the timer
```

This will depend entirely on how cooperative the fireballs are. You cannot afford to grab a single hammer while attempting this achievement. You need to immediately clear all the rivets on the left, then hope the fireballs are cooperative in letting you clear the rivets on the right. Do not be afraid to jump over a fireball if that's what it takes. Another very helpful trick is you can actually run behind Kong and not die. Being on max difficulty also helps here thanks to the quicker fireball speed - you can leap over the fireballs if they're moving towards you.

<img src="https://github.com/wescopeland/RAScripts/blob/main/assets/guides/Turbo%20Rivet.gif?raw=true" height="400">

<br><br>

### End of the Road

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325585.png">

```
The Hammerless Hero [50 Points]
Reach L=05 without using a single hammer
```

Thankfully, you can do this with all four of your lives. But if you grab a single hammer, this achievement is unobtainable. This will put all of your skills from all previous achievements to the test. The rivets will be the most challenging. Be extra sure to [memorize the fireball behavior rules](#the-fireballs-are-random-but-follow-predictable-rules).

<br>

<img align="left" width="72" height="72" src="https://media.retroachievements.org/Badge/325586.png">

```
Legend of the Arcade [100 Points]
Reach L=22 and survive until the game gives up
```

I truly hope you will be able to unlock this achievement. Once you reach L=22, take note of the bonus timer. You will see it behaving erratically. After a few moments, Jumpman will suddenly die. You have beaten the game.

**This will not unlock if Jumpman dies to any obstacles on the screen.** Be extra sure to survive until the game truly ends.

If you made it this far, I would love to hear from you.