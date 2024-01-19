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

Fishing tournament is a competitive two player game to see who can catch the three largest fish. In a span of a year (in-game time), the two players will alternate turns (one turn per month), then catch fish until the end of one year and the player with the three largest fish is the winner. This game implements 3 different hawaiian fish families; puaama, uhu, and weke. In the game, legal size, season, and catch methods are very important, as each family of fish will have different rules. If they catch a fish under legal size, the player will be punished by having all their fish confiscated. Certain fish cannot be caught in certain months as well. While other fish families will have different catch methods, such as "net" or "pole". Each month, the player has three attempts to catch a fish, which randomly will not hook or hook a fish. When hooking a fish, then there is a chance it is caught or gets away. Once caught, the player has the option to keep the fish, caution: players must watchout for legal size. Also, every month that passes, the fish caught will actually grow and sometimes evolve into a bigger fish of their species depending on the size of growth and gender of the fish.
 
I had 2 other group members and we were all in charge of one fish family. I coded the object classes for the Uhu family: Ohua, Panuhunuhu, and Uhu. Then as a team, we all contributed in making the fish driver class to implement our game. All fishable fishes needed to be subclasses of FishableI_a subclass of I_a.

In this project, I learned how to implement a fishable interface using object classes, having a superclass and abstract subclasses. The game my team developed used Java's objected oriented programming. 

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

Here is some code that illustrates the eat method to increase the length of the fish:


Source: <a href="https://github.com/ICSatKCC/assignment-8---final-project-fishing-game---s22-assignment-8-group-1"><i class="large github icon "></i>fishing/ics-211-game</a>
