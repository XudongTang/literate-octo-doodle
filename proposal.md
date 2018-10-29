# X-Team 29 Project - CookBook - Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description
Briefly describe a problem that your team would like to solve.
The problem we are trying to solve is wasting time trying to figure out what to cook. Our program will save the user time figuring out what to cook by using inputted ingredients to provide a recipe idea.

Describe at a high level a program that could solve that problem:
Our program is going to use a hash table implemented through an array of ArrayList buckets with ingredient objects. The user would input one or two ingredients and the program will output all of the recipes that use either one or both of the ingredients. The user can also enter in their own recipes with new or previously added ingredients. The ingredient object has a key of it's name and a value of an ArrayList of recipes that can be made from it.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
The Reverse Cookbook


2. Output: Describe the output your program will produce.  Include and example format of the output produced.<br/>A list of recipes that match the inputed ingredients. EX: Pasta with meatballs: spaghetti, meatballs.  


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.<br/>
First the number of ingredients. Than the ingredients. EX: 2, spaghetti, meatballs.

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.<br/>
It will be a text-based user interface. it will prompt user for inputs, which are ingredients, and the program will return 
a list of recipes, via console. 


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.<br/>
 a. Ingredients Class: Key (Name of ingredient), Value (Array List of Recipe Object)<br/>
 b. Recipe Class: Name of Recipe, Array List of Ingredients to make that recipe<br/>
 c. HashTableADT Interface: put, get<br/>
 d. RecipeTable Class: Hash Table containing the Ingredients Object, and uses buckets with Array List<br/>
 e. Main Class: Main user interface for the program<br/>
 f. TestRecipeTableClass Class: Test for exception handling, resizing, adding ingredients, test for input of 1/2 ingredient(s),<br/>
    IllegalArgumentException, NullPointerException when inputing 2 ingredients and one is empty string

