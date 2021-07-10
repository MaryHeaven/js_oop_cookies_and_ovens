# Cookies and ovens: bakery model

## Introduction

*I <3 Cookies* is a bakery that specializes in making delicious cookies. The bakery is growing rapidly and it's becoming difficult to meet the demand. Some management programs should help you achieve your goals. Your task is to create a program that will help you manage your bakery.

Here are some user feedback to help you get started:

- As a baker, I want to make different types of cookies (peanut butter, chocolate chips, etc.).
- As a baker, I want to put batches of cookies in the oven.
- As a baker, I want to know when the batch of cookies is ready to take out of the oven.

### Object-oriented programming. Planning 
The goal of this challenge is to transfer objects, classes of the real world to objects and classes of your program. Here are some guidelines you should follow.

* Create well-defined classes that are responsible for one thing.
* Implement clean and flexible logic of interaction between objects.

## Releases
### Pre-release: Understanding the problem

Before you start coding, you need to think critically about this issue. Then describe how to develop this program in plain Russian. Consider the following questions:

- What are the main classes?
- What attributes will each class have?
- What functionality will each class provide?
- How will the classes interact with each other?
- Does inheritance make sense? Composition? Do you know what composition is?


### Release 0: MVP (minimal viable product)

With some idea of ​​what components make up your program, start writing code. Build a *minimum viable product* (MVP) - no fancy features, just the essentials.

Based on the user's stories in the *Introduction*, you should be able to cook cookies, you should be able to put cookies in and out of the oven. If the cookie is in the oven, then you must bake it and check its readiness status.

You have a great opportunity to write some tests that describe how your classes work!


### Release 1: Additional funcitonality

Excellent! You've written MVP. Now is the time to expand the program with some new features and, as always, test them out. You must absolutely do the following:

- Make several types of cookies, each with a different baking time.
- Cookies have four possible statuses depending on how long they have been baked: `doughy`,` almostReady`, `ready` and` burned`.

### Release 2: Refactoring

[Refactoring] (https://en.wikipedia.org/wiki/Code_refactoring) is an important part of development. Take a step back and look at the code you have created. Make sure you like it and don't want to optimize anything. Do you understand OOP well? Pay attention to the following aspects:

- Are you using more properties and functions for the object than necessary?
- Do you repeat the same logic several times in your code? No need to repeat.
- Are your classes orthogonal? ([Orthogonal])

### Release 3: Be creative!
Put yourself in the shoes of a baker and think about what other features you might find useful. Choose the most useful and feasible function and add it to your program.

[Orthogonal]: http://stackoverflow.com/a/1527430
