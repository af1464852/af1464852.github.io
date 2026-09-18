## Table of Contents
- [Blocks](#blocks)
- [Concepts](#concepts)
- [Vocabulary](#vocabulary)
- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)
  - [Headings](#headings)
  - [Text Formatting](#text-formatting)
 








## Blocks
### Hat Block 

Shape/Type: A block with a rounded top and a notch on the bottom.

What It Does: It senses specific triggers (like pressing a key or clicking the green flag) to start a script. It can only sit at the very top of a stack of commands.

Example: when green flag clicked

### Stack Block or Command Block

Shape/Type: Rectangular with a notch on top and a bump on the bottom.

What It Does: It performs a specific action or command. It connects by snapping underneath a Hat block or other Stack blocks to form a sequential list of actions.

Example: move 10 steps

### C-Block or Control/Loop Block

Shape/Type: Shaped like the letter "C" with an opening on the right side.

What It Does: The C-shape represents a loop or a condition. Blocks placed inside the opening will repeat or run based on the block's rules.

Example: repeat 10 the actions inside run 10 times

### Reporter Block
Shape/Type: Oval/Round.

What It Does: It holds and reports a value, such as a number or a piece of text. It cannot stand alone; it must be dropped inside the oval-shaped input slots of other blocks.

Example: x position or username

### Boolean Block
Shape/Type: Hexagonal six-sided with pointed ends.

What It Does: It reports whether a condition is strictly true or false. It has a unique pointed shape so programmers know it can only fit into hexagonal input slots (like conditions for loops and ifs).

Example: touching mouse-pointer?

### Repeat Block
Shape/Type: C-shape.

What It Does: It runs the blocks placed inside it a specific number of times. Stack blocks go inside its opening.

Example: A repeat 5 block containing a play sound block will play that sound exactly 5 times.

Name: Wait Until Block
Shape/Type: Rectangular Stack block with a hexagonal input slot.
What It Does: It pauses the execution of the script at that exact point. It needs a Boolean condition (true/false) to look at, and it will only let the script move forward once that condition becomes true.
Example: wait until <key space pressed?>

### If Then Block
Shape/Type: C-shape with a hexagonal input slot at the top.

What It Does: It checks a Boolean condition. If the condition is true, the program runs the blocks tucked inside the "C". If the condition is false, the program completely skips those blocks.

Example: if score  10 then  say "You Win!" 

### Forever Block
Shape/Type: C-shape with a smooth bottom no notch underneath

What It Does: It runs the blocks inside it in a continuous loop that never stops on its own. Programmers use it for actions that need constant checking or updating, like gravity mechanics or background music.

Example: forever  next costume, wait 0.1 seconds 






## Concepts








































## Vocabulary

















































## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  

This ensures your notes are easy for you (and others) to read later.

---

## Headings

**When to use:** Organize your notebook into sections (like days, topics, or projects).  

- `#` for the notebook title (use once at the top).  

- `##` for each day or major topic.  

- `###` for subsections (like "Notes", "Practice", "Reflections").  

# Example:

# My Coding Notebook

## Day 1

### Notes

### Practice

# Text Formatting

When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

# Example:

**Class** = a blueprint for objects  

*Remember:* always test your code  

Use `System.out.println()` to print

 

# Code Blocks

When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

# Example:

```java

public class Hello {

    public static void main(String[] args) {

        System.out.println("Hello World!");

    }

}

```

# Lists

When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

# Example:

Define the class
Write the main method
Test your program
Variables

- Loops

- Conditionals

 

# Checklists

When to use: Track progress on assignments or tasks.

# Example:

[x] Complete coding warm-up

- [ ] Finish project draft

- [ ] Reflect on learning

 

# Blockquotes

When to use: Call out notes, reminders, or teacher comments.

# Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

# Tables

When to use: Compare values, track progress, or organize data neatly.

# Example:

| Task        | Status   | Notes          |
|--------------|------------|-----------------| 
| Homework 1  | Done #  | Submitted      |
| Homework 2  | Pending  | Needs review   |

 

# Links & Images

When to use: Add references, resources, or visuals.

# Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

To make an image that is a link, paste the image, then add the following before it, replacing website address with the link:

<a href="website address">

And after the image info, add: </a>

# Collapsible Sections

When to use: Hide solutions, extended notes, or extra details.

# Example:

<details>

  <summary>Click to reveal solution</summary>

  

System.out.println("Answer: 42");

</details>

 

# Footnotes

When to use: Add references or side notes without cluttering the page.

# Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

# Style Rules

Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

 

# Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.
