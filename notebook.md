# My Coding Notebook



## Table of Contents
- [Flutter Notes](#flutter-notes)
  - [What is Flutter?](#what-is-flutter)
  - [Key Terms and Definitions](#key-terms-and-definitions)
  - [Layout and Design Widgets](layout-and-design-widgets)
  - [Definitions with Structures](#flutter-definitions-with-structures)
- [Code Definitions](#code-definitions)
- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)

## Flutter Notes

### What is Flutter?
- Definition:
- Why is it useful?

---

### Key Terms and Definitions


## Flutter Definitions with structures

| Term | Definition and Description | Base Structure | Real Life Example | App Example |
|------|----------------------------|----------------|-------------------|-------------|
|      | A function that runs when your app starts. It tells Flutter what app to show. | `void main() => runApp(MyApp());` |  |  |
|      | The widget that sets up your whole app’s look and navigation. | `MaterialApp(...)` |  |  |
|      | A widget that gives you the basic layout: background, navigation bar, floating button, etc. | `Scaffold(...)` |  |  |
|      | A widget that holds and displays your content in a straight line from top to bottom. | `Column(...)` |  |  |
|      | A widget that shows things side-by-side. | `Row(...)` |  |  |
|      | A box that holds other widgets. You can add color, padding, borders, or size. | `Container(...)` |  |  |
|      | A widget to display text on the screen. | `Text('Hello')` |  |  |
|      | A widget to show an image using a link from the internet. | `Image.network('https://...')` |  |  |
|      | A clickable button that floats above content. You choose what happens when it's clicked. | `ElevatedButton(onPressed: ..., child: ...)` |  |  |
|      | The code that gets run when a button is tapped or something happens. | `onPressed: () => doSomething()` |  |  |
|      | A class that creates widgets that never change. Good for static screens. | `class HomeScreen extends StatelessWidget` |  |  |
|      | A class for widgets that can change while the app is running. | `class MyWidget extends StatefulWidget` |  |  |
|      | Lets you move from one screen to another using route names. | `Navigator.pushNamed(context, '/about')` |  |  |
|      | Makes space around a widget inside its container. | `Padding(padding: EdgeInsets.all(8.0), child: ...)` |  |  |
|      | Aligns content in the center of the screen or container. | `Center(child: ...)` |  |  |
|      | Automatically puts widgets onto a new line when there's no space. | `Wrap(children: [...])` |  |  |
|      | This marks a method as one that’s replacing a method in a parent class. | `@override` |  |  |
|      | The special function in every widget that describes what gets drawn on the screen. | `Widget build(BuildContext context) {...}` |  |  |
|      | Required in every widget class to describe what to show. | `build` |  |  |
|      | A variable that helps the widget know where it is and lets it communicate with the app. | `BuildContext context` |  |  |
|      | A keyword used to pass a value to the parent widget. | `super.key` |  |  |
|      | A keyword that means the value won't change and is set once. | `const` |  |  |




## Code Definitions

| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |
|------|------------|--------------------------|-------------------|-------------|
| Variable | A named container used to store a value that may change. | `var x = 5;` | score | Age |
| Constant | A fixed value that cannot change once set. | `const PI = 3.14;` |  |  |
| Date Type | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` |  |  |
|  String     | A sequence of characters used to represent words or text. | `"Hello World"` |  |  |
|   interger   | Whole number values. | `int age = 16;` |  |  |
|    double    | Number values with decimals. | `double age = 16.2;` |  |  |
|     boolean   | A value that can be true or false. | `bool isLoggedIn = false;` |  |  |
|   list   | A collection of values in a specific order. | `List<String> names = [];` |  |  |
|   null   | A special value that means “nothing.” | `String? name = null;` |  |  |
|   parameter     | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` |  |  |
|   function   | The information passed into a function to change how it works. | `greet(String name)` |  |  |
|   parameter   | The result a function gives back. | `return total;` |  |  |
|  return    | Where a variable or function can be used. | (No set syntax — concept-based) |  |  |
|  scope    | Blueprint for creating objects with specific structure and behavior. | `class Dog {}` |  |  |
|   class   | A specific version of a class. | `Dog myDog = Dog();` |  |  |
|  object   | A variable that belongs to a class/object. | `String name;` |  |  |
|  property    | A function that belongs to a class. | `void bark() {}` |  |  |
|   method   | A special function used to set up a class when it’s created. | `Dog(this.name);` |  |  |
|  constructor    | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) |  |  |
|   abstraction   | Changing how a built-in or inherited function behaves. | `@override` |  |  |
|    void  | A function that does not return a value. | `void printMessage() {}` |  |  |



## Day 1 
Notes for the day

## Day 2 
Notes for day 2

## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  
This ensures your notes are easy for you (and others) to read later.

---

## 🔹 Headings
**When to use:** Organize your notebook into sections (like days, topics, or projects).  
- `#` for the notebook title (use once at the top).  
- `##` for each day or major topic.  
- `###` for subsections (like "Notes", "Practice", "Reflections").  












