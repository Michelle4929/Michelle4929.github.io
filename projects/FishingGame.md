---
layout: project
type: project
image: img/uhu better2.jpg
title: "Fishing Tournament"
date: 2022
published: true
labels:
  - Java
  - GitHub
summary: "A Hawaiian fishing tournament game my group developed for ICS 211."
---
<img class="img-fluid" src="../img/fishing tournament.png">

## How to Play the Game

Fishing tournament is a competitive two-player game to see who can catch the three largest fish. In a span of a year (in-game time), the two players will alternate turns (one turn per month), then catch fish until the end of one year and the player with the three largest fish is the winner. This game implements 3 different Hawaiian fish families; puaama, uhu, and weke. In the game, legal size, season, and catch methods are very important, as each family of fish will have different rules. If they catch a fish under legal size, the player will be punished by having all their fish confiscated. Certain fish cannot be caught in certain months as well. While other fish families will have different catch methods, such as "net" or "pole". Each month, the player has three attempts to catch a fish, which randomly will not hook or hook a fish. When hooking a fish, then there is a chance it is caught or gets away. Once caught, the player has the option to keep the fish, caution: players must watch out for legal size. Also, every month that passes, the fish caught will grow and sometimes evolve into a bigger fish of their species depending on the size of the growth and gender of the fish.

Example of Gameplay:
```cpp
  Month: January
  Player 1, it is your turn!
    *Choose:
    1. Cast out for a fish
    2. View sack of fish
    3. Release a fish from your sack
  1
    You hooked a fish!
    Name: Weke ula
    English Name: Yellowfin Goatfish
    Scientific Name: Mulloidichthys Vanciolensis
    Length: 14.68
    Weight: 29.35
    Body Color: White with Yellow Stripes
    Fin Color: Yellow
    Sex: Female

    Do you want to keep this fish? y/n
  y
    Fish added to your sack!
    Your fish is legal and in season
```
## My Contributions 
 
I had 2 other group members and we were all in charge of one fish family. I coded the object classes for the Uhu family: Ohua, Panuhunuhu, and Uhu. The Uhu family is born as an Ohua baby then depending if it meets certain requirements, it will evolve into a Panuhunuhu and finally a Uhu. I had to create several functions to randomize its chance of growth to evolve. The main functions that controlled the fish's growth were length, color, and gender. All three different fish families had different requirements so some families did not need some functions to determine their growth like gender, while others did. Then as a team, we all contributed to making the fish driver class to implement our three different fish families into one to make a game. All fishable fishes needed to be subclasses of FishableI_a subclass of I_a. 

Here is some code that illustrates the eat method to increase the length of the fish:

```cpp
 protected void grow() {
      Random ran = new Random();
      double lengthIncrease = ran.nextDouble() * growthRate;
   
      //calculate a new length by adding a random value between 0 and growthRate
      double newLen = this.length + lengthIncrease;
   
      //check to see if this fish needs to level up
      if (newLen > this.maxLength) {
         throw new FishSizeException("This fish has outgrown its name, it must level up!");
      } else {
         this.length = newLen;
         this.weight = 2 * newLen; //rudimentary weight calc
      }
   }
```

## What I Learned

In this project, I learned how to implement a fishable interface using object classes, having a superclass and abstract subclasses. The game my team developed used Java's objected-oriented programming. Not only did I learn new programming techniques but I also learned the value of teamwork. Up to this point, all my coding work has been by myself so I have never worked in a group project before. It was a valuable experience as when in a group project, you don't just have yourself to rely on but your teammates as well. It also helped me communicate more with my teammates as each part of the project will not work if we are not on the same page.

