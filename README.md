# Codewars (Just for Fun)
This is my gallery for Codewars challenges. The Java code in this repository is intended for educational purposes.

### Goal
Sometimes we are stuck thinking and thinking how to solve something in particular and we end up going nowhere and discouraged.

The purpose of these code extracts is to give other developers some ideas in how to solve certain challenges.

### Important Notes
If you are learning how to code, just copying a whole solution from others is not going to help you learn, but there is no harm in analysing others code for learning purposes.

### How to run the application
1) cd to the project root folder in the command line
2) `mvn compile`
3) `mvn exec:java -Dexec.mainClass=clan.techreturners.katas.Main`

To run tests:
1) `mvn test`

## Technology
This project was built using:
- Java 17.0.2
- JUnit 5.8.2
- Maven 3.8.5
- IntelliJ 2021.3.2 (Community Edition).

---
## Gallery

### Split Strings

Split an input string into pairs of 2 characters, add underscore if the last letter is single.

**Language:** Java

**Example:**
```
"mine"  ->  ["mi", "ne"]
"yours" ->  ["yo", "ur", "s_"]
```

[View Solution](src/main/java/clan/techreturners/katas/SplitStrings.java)

- - -
### Total pages in a book

Given a number (summary) that is the sum of all digits of all the pages in a book, return the number of pages.

**Language:** Java

**Example:**

When summary = *15*, then the number of pages is **12**, as the numbers 1 to 12 have 15 digits in total: ``123456789101112`` 

```
15 ->  12
31 ->  20
```

[View Solution](src/main/java/clan/techreturners/katas/PagesInABook.java)

- - -
### Simple Pig Latin

The first letter of each word must be moved to the end of it and also add "ay", punctuation marks remain untouched.

**Language:** Java

**Example:**

```
"Peppa likes Latin" ->  "eppaPay ikeslay atinLay"
"This is so cool !" ->  "hisTay siay osay oolcay !"
```

[View Solution](src/main/java/clan/techreturners/katas/SimplePigLatin.java)

- - -
### Strip Comments

Strip all the text following any set of comment markers passed in. White spaces at the end of the line should be trimmed.

**Language:** Java

**Example:**

For the following given string:
```
Comment !word stripped
same here
tomato, avocado # and tangerine
```

The expected output would be:
```
Comment
same here
tomato, avocado
```

[View Solution](src/main/java/clan/techreturners/katas/StripComments.java)

- - -
### Mexican wave

The goal is to turn a string into a Mexican wave, where an uppercase letter would be like a person standing. 

Input will always be in lowercase and if there is any whitespace then just pass it over.  

**Language:** Java

**Example:**

```
"wave me!" ->  ["Wave me!", "wAve me!", "waVe me!", "wavE me!", "wave Me!", "wave mE!"]
```

[View Solution](src/main/java/clan/techreturners/katas/MexicanWave.java)

- - -
### Roman numerals encoder

Create a function taking a positive integer as its parameter and returning a string containing the Roman Numeral representation of that integer.

**Language:** Java

**Examples:**

```
1000 ->  M
452 ->  CDLII
```

[View Solution](src/main/java/clan/techreturners/katas/RomanNumeralsEncoder.java)

- - -
### Roman numerals decoder

Create a function that takes a roman numeral as parameter and returns its representation in arabic number.

**Language:** Java

**Examples:**

```
M -> 1000
CDLII -> 452  
```

[View Solution](src/main/java/clan/techreturners/katas/RomanNumeralsDecoder.java)

- - -
### Make Spiral

Create an NxN spiral with a given N size, where the snake made with '1' cannot touch itself.

**Language:** Java

**Examples:**

For N = 5, the spiral returned will look like this:
```
[[1, 1, 1, 1, 1],
 [0, 0, 0, 0, 1],
 [1, 1, 1, 0, 1],
 [1, 0, 0, 0, 1],
 [1, 1, 1, 1, 1]]
```

[View Solution](src/main/java/clan/techreturners/katas/MakeSpiral.java)

