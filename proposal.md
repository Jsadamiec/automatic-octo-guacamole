# X-Team 102 Project Proposal "WisCARson"

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

We will develop a program for a Wisconsin-based company that sells cars. Our goal is to create an easy way to search cars by creating a database by implemneting a Hash Table made from an Array of Linked Lists. We will sort the cars using their VIN number, and be able to calculate total tax given from the price of the car. 

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

   WisCARson

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

   The Year, model, ownner name, the tag number, purchase price and the tax that the ownner should paid for this  registration.
   Year: 2003
   Model: Camry
   Owner: Jeff
   Tag Number: 3423954032234
   Purchase Price: $15,000
   Tax: $750


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
 
    VIN number and purchase price
    
    Enter your VIN: 
    Enter Price:

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
 
    Two textboxes for VIN number and purshase price along with two buttons, one for inserting and one for searching. Along with text field for the output. 

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

    Our class will contain a subclass for the nodes, and methods for inserting, seraching, removing, and sorting the cars along with private helper methods.

HashTable interface, HashTable class

## Edit and Submit this file and any figures referenced by this document.

