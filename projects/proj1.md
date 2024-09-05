---
layout: project
type: project
image: img/proj1pic.png
title: "Formula Fish"
date: 2024
published: true
labels:
  - Game Development
  - Java
  - jGRASP
  - GitKraken
summary: "An interactive loko i'a (fish pond) video game that integrates sustainable Native Hawaiian lawa i'a (fishing) practices."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

Formula Fish is a interactive 2-player text-based tournament style fishing game where both players will take a turn every month to catch 3 fish over the course of 12 months. Players will have the choice to choose 1 of 5 fishing tools: pole, net, spear, trap, or throw net. There are 4 different fish species: Moiliʻi, Oama, Ohua, Puaʻama that will continue to grow at the end of every month. These fish have certain rules and regulations that will decide if the player is illegally fishing. If the player is caught illegally fishing, then all the fish caught during their turn are confiscated and their turn ends. Players can check the rulebook on fishing regulations during their turn. Players can always choose to release the illegal fish before putting it in their sack to avoid a fishing penalty. Fishing season ends when 12 months have passed and the player with the 3 largest fish (sum of the 3 largest length) wins!

My team was a group of 4 individuals: Ella Self, Martino Koo, Adam Bell, and I. Our game encompasses a number of Java files that form a hierarchy of fish families. The primary file users will interact with is FishDriver. FishDriver contains methods such as 
• Main: gives player options, displays information, and
counts off the months within the year
• caught & throwBack: simulates catches and releases
• fillPond: adds fish to the pond
• lawai_a: monitors and modifies players caught’s
• growFish: allows monthly growth of players fis
• I_a: basis for interactive elements and information of the respective fish families
• Fishable: an interface contains methods thats are used within the hierarchy to allow for the game functionality
• MoiLi_i, Oama, Ohua, Pua_ama: the child classes to each fish family that holds fish’s base information and is an extension of fishableI_a that implements game methods
• Expectation: classes that alerts users of discrepancies or alterations to their fish’s
• Changeable: classes that allows for variation in qualities of older fish.

You can learn more on page 71 in the [2024 Pueo o Kū Journal of Science, Technology, Engineering, and Mathematics (STEM).]([https://manoa.hawaii.edu/news/article.php?aId=2857](https://drive.google.com/file/d/1EQfDB4KRqd0SOKlOI6y_mTqio0xxLxPc/view)).
