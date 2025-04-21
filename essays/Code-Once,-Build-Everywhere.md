---
layout: essay
type: essay
title: "Code Once, Build Everywhere!"
# All dates must be YYYY-MM-DD format!
date: 2025-04-20
published: true
labels:
  - Design Patterns

---

<img class="img-fluid" src="../img/Ask-Smarter-and-Learn-Faster:-The-Science-of-Smart-Questions/stackoverflow.png">

## Smart Roofs, Smarter Design

*Good design is actually a lot harder to notice than poor design, in part because good designs fit our needs so well that the design is invisible - Don Norman*

Imagine you are hired as a designer at an architecture company and tasked with designing roofs for houses all across America. You quickly realize that it would be way too crazy to design a different roof for every single house, so you need to find a better approach. Soon, you come up with a smarter idea: instead of making a unique roof for each home, you can design a few different types of roofs based on the climate of the region where the house will be built and reuse those designs.

For example, houses in Hawaii should have roofs that let rainwater run off easily, since it rains often. On the other hand, houses in Alaska need roofs designed to help snow slide off, since snowfall is frequent there. This is a real life example of a design pattern where you create a core solution to a recurring problem and reuse it over and over again, rather than solving it from scratch each time.

## Design Patterns: The Good, The Bad, and The Useful

Now let’s talk about design patterns in software development, which are reusable solutions to common coding problems that help improve efficiency. OO design patterns, or Object-Oriented design patterns, act like blueprints that show how objects in a program can collaborate to solve recurring design problems. According to the book "Design Patterns: Elements of Reusable Object-Oriented Software" published in 1994, there are 23 "Gang of Four" design patterns, which are categorized into three groups: creational, structural, and behavioral. Each type of design pattern has its own advantages and disadvantages, so it’s important to choose the one that best fits your specific problem. Additionally, anti-patterns are solutions that may seem effective at first but ultimately lead to more problems, so they should be avoided whenever possible.

## Code Like a Pro: Design Patterns in Action

Let’s take a look at some examples of design patterns mentioned earlier to better understand how they work. 

The Factory pattern helps create objects without showing how they are made, making it easier to use different types of objects and build extra parts if needed. However, it can be a bit more complicated than just using a regular class constructor. 

The Singleton pattern ensures that only one object is created and used throughout the program, which is helpful for sharing data easily. But if too many parts of the program rely on it, it can become risky and is not always safe to use with threads. 

The Observer pattern allows many objects to watch and react when something changes, making it flexible and useful for event-driven systems. Still, if it’s not implemented well, it can cause performance issues and make the program harder to understand and fix. 

The MVC pattern organizes code into three parts—model, view, and controller—so different people can work on different areas. This structure is helpful but can be complex and take some time to learn.

Understanding these patterns helps us write better, cleaner code and solve problems in smarter ways as our programs grow more complex.

## Copy-Paste, the JavaScript Way

In my JavaScript code, I used the Prototype design pattern to make new objects by copying existing ones. This was helpful because it saved time and kept my code cleaner by not repeating the same code over and over. JavaScript naturally uses prototypes, so when I created classes with the class keyword, the language automatically used the prototype chain to share methods and properties. This made my code more efficient since all objects could share behavior without needing separate copies. Using this pattern also helped me learn how JavaScript is different from other programming languages and how design patterns can improve the way code is written.

- Used ChatGPT for grammar check and brainstorming only.
