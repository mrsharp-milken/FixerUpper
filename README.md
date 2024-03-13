# Fixer Upper: HTML Edition

## The Goal

As anyone who has ever watched a home improvement or house hunting show can tell you, there's nothing wrong with a fixer upper. It's knowing how to identify the problems, and then fix them in an efficient way. This applies to houses, and coding... of every variety. In this lab we'll work to learn how to recognize and fix common problems in html code.

## The Lab

You'll be working in a different html file for each section of this lab. Part One will reference part_one.html and so on. We'll be looking at two common issues with html code:
  1. Formatting
  2. Syntax errors

The first, formatting, is not something that will impact your code compiling. Properly written html with improper formatting will still **compile**, but is infinitely harder to debug.

The second, Syntax errors, include things like unclosed or missing tags, improper nesting, and misspellings in tag names.

### Part One: Formatting
If you look in part_one.html you'll see a file of correct html that compiles. However, the formatting is messy and hard to read. Try fixing this format yourself so that there is:
* One opening tag on each line
* One closing tag on each line (a closing tag can be on the same line as its opening tag if there are no child elements)
* Each child element is indented one tab space further than its parent.

Once you think you've finished formatting this correctly, [online HTML validators like this one](https://jsonformatter.org/html-validator) offer a great way for you to check your work. Paste in your code and click "Format HTML." Make sure you finish yourself **before** checking your work so you can develop your own intuition for this.


### Part Two: Fixing Bugs
In this section of the lab we'll be working in several files. You'll be looking at correctly formatted code and fixing the bugs described so that your html code compiles. You'll know that your code is compiling when you can preview the html file. If your code format changes significantly (more than inserting a carrot or another line for a tag), then you've likely misplaced a new tag.

**File One: part_two_a.html**
  * This file has two missing closing tags. To understand what this means check out the example below:

  ```HTML
  <!-- This paragraph element is missing the closing paragraph tag -->
  <p> Paragraph woooooo!
  ```

  ```HTML
  <!-- hmm this is better -->
  <p> Paragraph woooooo! </p>
  ```

To give yourself additional tools to find the errors in this code consider using an [HTML validator](https://validator.w3.org/nu/#textarea). You can copy and paste in your html code and decipher to error messages provided when you try to validate it!

**File Two: part_two_b.html**
  * This file has one missing closing tag, one missing opening tag, and has two incomplete tags. An incomplete tag could be either of the below options:

  ```html
  <p Paragraph Content </p>
  p> Paragraph Content </p>
  <p> Paragraph Content <p>
  <p> Paragraph Content </p
  <!-- Or any other variety of these kinds of mistakes -->
  ```

You are welcome to use the HTML validator linked above to help with this file too!

### Part Three: Bringing it Together

In the previous bug finding tasks you've been given already formatted code, now let's take a look at how much more difficult it is to find bugs when code **isn't** formatted.

**File One: part_three_a.html**
* In this exercise you'll look at the part_three_part_a.html file. For the first half of this exercise **do not** fix the formatting.
* This file is missing one opening tag, has two incomplete tags, and one misspelled tag (this could be either in the opening or closing).

**File Two: part_three_b.html**
* In this exercise you'll look at the part_three_part_b.html file. In this file you **can** and **should** fix the formatting before you start debugging. Whether this is with auto format or your own formatting is up to you, but generally when trying to save time auto formatting is a useful help tool.
* This file is missing one closing tag, has one incomplete tag, one misspelled tag, and one tag missing an attribute (for example, an image tag needs both an src and a alt attribute)

Notice, both of these files had the same number of bugs, reflect on which was easier to debug!

### Extension
Swap computers with a neighbor and write your own html file on their computer. Follow the outline below for each level of this extension. After each level, swap back computers and use all of the tools discussed above to get the html up and running! In addition to the details provided in each level you can add as many formatting issues (white space related) as you want.

#### Level One:
* Up to three missing tags (opening or closing)
* One incomplete tag

#### Level Two:
* Up to three incomplete tags
* One misspelling
* Two tags missing attributes

#### Level Three:
* Up to five missing tags
* Up to four incomplete tags
* Up to three misspellings
* Up to three tags with missing attributes
