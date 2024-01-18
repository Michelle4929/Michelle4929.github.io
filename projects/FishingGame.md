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

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

Fishing tournament is a competitive two player game to see who can catch the three largest fish. In a span of a year (in-game time), the two players will alternate turns (one turn per month), then catch fish until the end of one year and the player with the three largest fish is the winner. This game implements 3 different hawaiian fish families; puaama, uhu, and weke. In the game, legal size, season, and catch methods are very important, as each family of fish will have different rules. If they catch a fish under legal size, the player will be punished by having all their fish confiscated. Certain fish cannot be caught in certain months as well. While other fish families will have different catch methods, such as "net" or "pole". Each month, the player has three attempts to catch a fish, which randomly will not hook or hook a fish. When hooking a fish, then there is a chance it is caught or gets away. Once caught, the player has the option to keep the fish, caution: players must watchout for legal size. Also, every month that passes, the fish caught will actually grow and sometimes evolve into a bigger fish of their species depending on the size of growth and gender of the fish.

In this project, I learned how to implement a fishable interface using object classes, having a superclass and abstract subclasses. The game my team developed uses Java's objected oriented programming.

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
