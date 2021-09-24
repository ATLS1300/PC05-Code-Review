# Week 5 & 6 - Code Review & more!

The theme of this week is "You know more than you think you know!" This week, you'll build confidence by learning how to debugging your code. You'll also learn about how to upgrade old code in a code review. *Please note that times and information seen here cannot easily be updated. Please follow Canvas dates and times in the event of any changes!*

## In this repository:
1. **Practice For Loops.ipynb** - Jupyter Notebook file containing a walk through of how to use for loops. If you are still struggling with for loops, download this and start anew! Practice practice practice! **Submit your completed code to this repository (instructions under Debugging).**
2. **debugPractice.py** - A Python script containing 5 bugs. You will have to debug the code (following the instructions laid out [here](https://canvas.colorado.edu/courses/75648/assignments/1182628)), and submit the code that is both **debugged** (has no errors when run) and the fixed code is **commented** describing what was changed. You will receive 1 point for every correctly debugged line of code!
3. **badCode.py** - For PC05 (Code Review), you will upgrade some code that you have previously submitted. This new code must have good [code quality], and a few extra things (like flow control and comments). If you don't want to work your own code, you can work with this code that Dr. Z made for this purpose.

## Debugging - Due Monday, September 27th at 10pm
Bugs are a natural, normal part of the code. Strong programmers know that when they run newly built code, they should anticipate errors. There is an absurd number of memes on this topic. I encourage you to think this way, too: **You will make broken code first, then fix it.**
Please walk through the assignment [linked on Canvas](https://canvas.colorado.edu/courses/75648/assignments/1182628) for clear instructions. Then download the code in this repository and fix it with your newfound skills. 
**Submit the code by adding it to this repository.** 
Click the "Add Code" button, then select "Upload New File". You can drag and drop your file into the window that opens.

## PC05 Code Review - Due Wednesday, October 6th at 10pm
### What is Code Review?

Code Review is a way of looking at previously-written scripts (code that runs tasks) with a goal of improving code quality. In this class, we're not only going to focus on broad features, like organization, variable naming and spacing, but also whether our code is Pythonic-following traditions and expectations in programming style. These features of quality are listed in the section below.

Click [here](https://google.github.io/eng-practices/review/reviewer/), for more on how to do a code review.

Use the following text as a check list. Go through your code 4 times, following each of these points as the focus each time.
### Quality Code...
1. **does what it's supposed to do.** To ensure this, you should:
  1. Make sure there is a description at the top of the code, so you know if the code does what it should or not.
  2. Scan the side for warnings (exclamation point triangle) and errors (red circle). Make sure you understand each warning. Edit the code to remove errors and as many warnings as possible. If you keep warnings know why it's worth doing so.
  3. Run the code and make sure that the description matches the result. If it doesn't, edit the description.

2. **doesn't contain defects and problems.** To check for this in the code, you should: 
  1. Run the code and look a the command line output for errors. Use the error report to navigate to the bad line of code and fix or delete it.
  2. Examine the code for poor syntax or organization. (Are all of your variables defined together? Are tasks commented with descriptions? Do you have cleanup at the end of your code?)

3. **is easy to read, maintain or extend.** Most likely where you'll spend the most time. To check for this, you should:
  1. Organize by section: imports (get libraries), setup (make turtles, panel, etc.), define variables, create functions, perform tasks
  2. Use empty lines to separate sections.
  3. Use comments to 1) label sections (variables, drawing, etc.), 2) describe an important variable, like a turtle, and what it will do, 3) describe what a loop does, or what a conditional checks for.
  4. Use negative space! Don't cram all your code into one block. Use empty lines and spaces between values to make your code easy to read. 

4. **is [D.R.Y](https://www.softwareyoga.com/is-your-code-dry-or-wet/) (Don't Repeat Yourself)**, and not W.E.T. (Write Everything Twice)
  1. Go through the code and look for repeating patterns. Do you see the same block of code repeated several times to make a pattern? Put in in a loop! See the same value used throughout the code? Save it to a variable! Do you see many turtles doing something 1 turtle can do? Consider consolidating.

### For full credit you should:
    1. Use Github or Spyder to review 
        1. Your old code (PC02-04)
        2. A classmate's code (PC02-04)
        3. Dr. Z's Bad Code (in this repo)
    2. Go through the code, making line-by-line edits. You must add at least one flow control into the code (for loop, if statment, while loop). (If there is no place to do so, add something to the code!) [Video tutorial here](https://drive.google.com/file/d/1GUof2Q7bomjw_qBU2b4jONUhBUjbEreu/view?usp=sharing_.
    Include a Criticism Sandwich in the summary review.
        *A Criticism Sandwich:*
            Open with a statement about the code quality the code had before your edits
            Provide constructive criticism--executable ideas on how to improve the code, and
            what you edited in Github to help achieve this,
            Close with 2-3 things you especially liked about the original code and/or how you think the program(mer) is progressing. 

    3. **Be kind!** It's hard to look back at code, and we're all still learning (even your LAs and Dr. Z). Don't be angry or embarrassed with yourself for not making code perfectly the first time. You and your peers have done a lot, and this is the chance to level up!
    **Note: Any derogatory or (self) abusive language may reduce your score.**

    4. You may also provide artistic feedback, with commentary on color choice, use of space (composition) and style.

    5. In the text entry on Canvas, submit the link to the code (Github repo) you will be reviewing. Please also submit the text "completed" when you have submitted your review on Github. 

 

## EXTRA CREDIT:

0.5 pt - Talk it out: AFTER submitting your code edits, meet with the original programmer and share your feedback with them. Have a discussion about what the programmer wanted to do and how they succeeded or failed. In a """triple quote comment""" write what struggles and successes you both have in common. (Not applicable for self-reviews.)

1 pt - Get feedback: Show the output of the code that you're reviewing to a friend (hooray for sharing screens), and have them give you some feedback on the art. Add what they said as a """triple quote comment""" at the bottom of the edited code.

1 pt - Upgrade: Sit with the original programmer and find out what they would expand their code to do, then add it into your edits. Meet with them again and add their feedback to the changes in a """triple quote comment""" at the bottom of the code. For your own code, add your reasons for the expansion, and in the """triple quote comment""".

1 pt - Overachieve: Do more than one code review. You may do 1 extra credit option for that assignment.
