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

Fishing tournament is a competitive two player game to see who can catch the three largest fish. In a span of a year (in-game time), the two players will alternate turns (one turn per month), then catch fish until the end of one year and the player with the three largest fish is the winner. This game implements 3 different hawaiian fish families; puaama, uhu, and weke. In the game, legal size, season, and catch methods are very important, as each family of fish will have different rules. If they catch a fish under legal size, the player will be punished by having all their fish confiscated. Certain fish cannot be caught in certain months as well. While other fish families will have different catch methods, such as "net" or "pole". Each month, the player has three attempts to catch a fish, which randomly will not hook or hook a fish. When hooking a fish, then there is a chance it is caught or gets away. Once caught, the player has the option to keep the fish, caution: players must watchout for legal size. Also, every month that passes, the fish caught will actually grow and sometimes evolve into a bigger fish of their species depending on the size of growth and gender of the fish.

In this project, I learned how to implement a fishable interface using object classes, having a superclass and abstract subclasses. The game my team developed uses Java's objected oriented programming. I had 2 other group members and we were all in charge of one fish family. I coded the object classes for the Uhu family: Ohua, Panuhunuhu, and Uhu. Then as a team, we all contributed in making the fish driver class to implement our game.

Here is some code that illustrates how the game simulates fishing:

```cpp
 public static void lawai_a(ArrayList<FishableI_a> fishPond) {
      Random randGen = new Random();
      FishableI_a ia;
      int chosenFish = 0;
      boolean isCaught = false;
      boolean isLegal = false;
      
      String[] months;
      months = new String[]{"January", "January", "February", "February", "March", "March", 
         "April", "April", "May", "May", "June", "June", "July", "July", "August", "August",
         "September", "September", "October", "October", "November", "November", 
         "December", "December"};
      Scanner scan = new Scanner(System.in);
      String menuChoice = "";
      String ynChoice = "";
      boolean validMenu = false; 
      boolean validYn = false; 
      boolean player1 = true; 
      ArrayList<FishableI_a> p1Sack = new ArrayList<>();  
      ArrayList<FishableI_a> p2Sack = new ArrayList<>();  
      //set game to be one year, both player have a turn in each month
      for (int i = 0; i < MONTH; i++) {
         System.out.println("\nMonth: " + months[i]);
         //starts I_a game
         if (player1) {
            System.out.println("Player 1, it is your turn!");
         } else {
            System.out.println("Player 2, it is your turn!");
         }
         //sets players fish cast to 3 attempts
         int attempts = 0;
         while (attempts < 3) {
            //menu options for players
            validMenu = false;
            while (!validMenu) {
               System.out.println("* Choose: \n"
                                + "  1. Cast out for a fish\n"
                                + "  2. View sack of fish\n"
                                + "  3. Release a fish from your sack");
               menuChoice = scan.nextLine().trim();
               if (menuChoice.equals("1") 
                   || menuChoice.equals("2") || menuChoice.equals("3")) {
                  validMenu = true;
               } else {
                  System.out.println("Please enter 1, 2, or 3");
               }
            }
               

```

Source: <a href="https://github.com/ICSatKCC/assignment-8---final-project-fishing-game---s22-assignment-8-group-1"><i class="large github icon "></i>fishing/ics-211-game</a>
