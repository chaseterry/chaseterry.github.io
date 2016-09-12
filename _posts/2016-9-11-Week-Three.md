---
layout: post
title: Week Three
published: true
---

## What did you do this past week?
I finished Collatz! It took so long to finally get Docker working, but it actually happened. I had resigned to ignore Docker and just hope for best, but I had Docker run without yelling at me. I also learned the fundamentals of Exceptions, which I had used but never formally learned how they work in terms of cascading and the copies. Additionally, I got another run-down of pointers and references in C++.

## What's in your way?
Many, many, many projects. So many of my classes this semester are all project based, so I spent most of my type in the lab developing, which is not necessarily a bad thing. However, it takes up a very large chuck of my time. My week consists of rowing, school, developing, homework, and sleep. 

## What will you do next week?
I will be starting on the next project (hopefully) on Monday. I have a partner lined up and regret from starting Collatz so late, so I'm very ready to start as soon as possible. In addition, I would preferably get my life together. I was entirely sleep deprived last week and it was only the second week of school, so something needs to change. I don't know what it is, but I will be finding that out very soon.

## Class Impressions
Now that I'm finally done with Collatz, it doesn't seem like it was that difficult of a project. I spend a much larger ratio of time and effort on the dev setup than actual coding. We were essentially given the solution to the problem, and told to improve it. However, Docker gave me headaches for a full week, the instructions were vague in someplaces (apparently intentionally), and I had never used clang-format, Doxygen, or Travis CI, so they took a bit of finagling and confusion to get them to work. But now that everything is setup, hopefully the future projects will be smooth sailing.

## Tip of the Week
A very neat game I've discovered this week is [John Conway's Game of Life](http://www.bitstorm.org/gameoflife/). If you've never seen it, I'd recommend fiddling around with it. You don't even have to enjoy video games, it's more of a simplistic model for life. It is a grid based set of cells, which live, die, or reproduce based on a set of simple mathematical rules. The rules are as follows:
For a space that is 'populated':
- Each cell with one or no neighbors dies, as if by solitude.
- Each cell with four or more neighbors dies, as if by overpopulation.
- Each cell with two or three neighbors survives.
For a space that is 'empty' or 'unpopulated'
- Each cell with three neighbors becomes populated.
