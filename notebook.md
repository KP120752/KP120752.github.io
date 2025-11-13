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
|   main()   | A function that runs when your app starts. It tells Flutter what app to show. | `void main() => runApp(MyApp());` |  | void main() => runApp(MyPortfolioApp()); |
|  MaterialApp    | The widget that sets up your whole app’s look and navigation. | `MaterialApp(...)` |  |  return MaterialApp( debugShowCheckedModeBanner: false, |
|    Scaffold  | A widget that gives you the basic layout: background, navigation bar, floating button, etc. | `Scaffold(...)` |  |   return Scaffold( body: Center( |
|  Column    | A widget that holds and displays your content in a straight line from top to bottom. | `Column(...)` |  | child: Column(   children: [        Text( |
|   Row   | A widget that shows things side-by-side. | `Row(...)` |  | child: Row(  children: [  |
|   Container   | A box that holds other widgets. You can add color, padding, borders, or size. | `Container(...)` |  | return Container( width: 160, |
|   Text   | A widget to display text on the screen. | `Text('Hello')` |  |children: [  Text(   title,  |
|   Image.network   | A widget to show an image using a link from the internet. | `Image.network('https://...')` |  | child: Image.network(imageUrl, width: 100, height: 100, fit: BoxFit.cover) |
|   ElevatedButton   | A clickable button that floats above content. You choose what happens when it's clicked. | `ElevatedButton(onPressed: ..., child: ...)` |  |  ),ElevatedButton(   onPressed: () |
|   onPressed   | The code that gets run when a button is tapped or something happens. | `onPressed: () => doSomething()` |  |  onPressed: () => Navigator.pushNamed |
|  StatelessWidget    | A class that creates widgets that never change. Good for static screens. | `class HomeScreen extends StatelessWidget` |  | class InfoCard extends StatelessWidget { |
|   Stateful Widget   | A class for widgets that can change while the app is running. | `class MyWidget extends StatefulWidget` |  |  |
|  Navigator    | Lets you move from one screen to another using route names. | `Navigator.pushNamed(context, '/about')` |  | onPressed: () => Navigator.pushNamed(context, |
|   padding   | Makes space around a widget inside its container. | `Padding(padding: EdgeInsets.all(8.0), child: ...)` |  |    padding: const EdgeInsets.all(12), |
|   Center   | Aligns content in the center of the screen or container. | `Center(child: ...)` |  | return Scaffold(body: Center( |
|  wrap  | Automatically puts widgets onto a new line when there's no space. | `Wrap(children: [...])` |  | Wrap(alignment: WrapAlignment.center, children: puppyUrls.map((url) => puppyImage(url)).toList()), |
|  @override    | This marks a method as one that’s replacing a method in a parent class. | `@override` |  | @overrideWidget build(BuildContext context) { |
|   build()   | The special function in every widget that describes what gets drawn on the screen. | `Widget build(BuildContext context) {...}` |  | @override Widget build(BuildContext context) { |
|  BuildContext    | Required in every widget class to describe what to show. | `build` |  | Widget build(BuildContext context) { |
|   superkey   | A variable that helps the widget know where it is and lets it communicate with the app. | `BuildContext context` |  |  |
|   const   | A keyword used to pass a value to the parent widget. | `super.key` |  |  margin: const EdgeInsets.symmetric(vertical: 8, horizontal: 16), |
|      | A keyword that means the value won't change and is set once. | `const` |  |  |




## Code Definitions

| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |
|------|------------|--------------------------|-------------------|-------------|
| Variable | A named container used to store a value that may change. | `var x = 5;` | score | main.dart title: 'TSA Portfolio', |
| Constant | A fixed value that cannot change once set. | `const PI = 3.14;` |  | main.dart  const MyPortfolioApp({super.key}); |
| Date Type | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` |  | main.dart, bool, debugShowCheckedModeBanner: false, |
|  String     | A sequence of characters used to represent words or text. | `"Hello World"` |  | main.dart, 'Hey there 👋\nHey there 👋, welcome to my Flutter demo!', |
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
| Scanner | Creates a scanner object to take input from user | Scanner in = new Scanner(System.in); | | |
| import Scanner | Gives access to Scanner class, required at top | import java.util.Scanner; | | |
| print line statement | prints the content in the parenthesis, adds line after | System.out.println(" "); | | |
| print statement | prints the content in the parenthesis | System.out.print(" "); | | |
| input nextLine | reads in a String from the user | input.nextLine(); | | |
| input nextInt | reads in an int from the user  | input.nextInt(); | | |
| input nextDouble |  reads in a double (decimal) from the user | input.nextDouble(); | | |
| input nextBoolean |  reads in a boolean (true/false) from the user | input.nextBoolean(); | | |
| Arithmetic operators |  -       *       /      % (modulus, returns the remainder from dividing) |  |  |  |
| Compound operators (applies the result to the variable) | +=      -=       *=      /=     %=   ++ (adds 1) |  |  |  |
| Maximum int | The max value an int can hold: 2147483647 | Integer.MAX_VALUE | | |
| Minimum int | The minimum value an int can hold: -2147483648 | Integer.MIN_VALUE | | |
| integer overflow | Integer.MAX_VALUE + 1 == MIN_VALUE, it wraps around | | | |
| Integer underflow | Integer.MIN_VALUE-1 == MAX_VALUE, it wraps around| | | |
| round-off error | an approx. of the actual value, result is rounded to the nearest value that fits within the available bits | | | |
| Algorithms | Define step by step processes to follow when completing a task or solving a problem | no syntax | Make a grilled cheese | Verify user |
| Sequencing | Define an order for when steps in an algorithm are completed | Follows 1, 2, 3 | which step comes first in making a grilled cheese | Get bread, add butter, add cheese |



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












