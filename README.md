# FTC-Projectile-Motion-Ultimate-Goal
program that calculates and graphs the projectile of the foam ring used in the Ultimate Goal TM Challenge for FTC (First Tech Challenge). Relevant for 2020-2021. Intellectual Property of FTC 14607. Use with caution. Created by FTC 14607 Robot Uprising, with primary contributer being *krishpatel1077*

# Understanding the Code and Using property with Care
THIS PROJECT IS THE INTELLECTUAL PROPERTY OF FTC 14607. USE THE PRODUCT IN ACCORDANCE TO THE MIT LISCENCE IN THE REPOSITORY
# The program will ask for the following input:
  - Starting height (yzero, inches)
  - Launch angle (theta, degrees)
  - Launch speed (vzero, meters/second)
  
# Optional Variables to edit:
  - x_cords = range(0, *your number here*) <---- This is used to determine the launch distance (horizontal) from the goals
  - x = float(*same number from above*) <--- Required for graphs and calculations to load
  
# What the program will return:
  - A final message with the format:
      It took *time* seconds to reach the tower. Falls in *goal it reaches* at *height* in.
  - A graph on the bottom displaying the path of the projectile (distance on the xy planes assuming 2d motion) with respect to the ground (the graph is 2d)
      A sample output can be seen using this link: https://imgur.com/EMzr6zd
