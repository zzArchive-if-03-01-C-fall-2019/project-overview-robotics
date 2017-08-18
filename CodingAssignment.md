# IF.03.01 Basic Web Technique Winter 2017

## Objective
The goal of this assignment is to practice all concepts of html and css we have done so far.

Another goal is to initially reflect the content of your project. You should provide a project overview in one html page which should be very well structured and nicely designed.

## Materials
If you work under macOS you will be already very familiar with the environment using

- Atom
- Chrome or Safari
- GitHub.

If you are working on a Windows machine then you need an alternative editor. Atom is available also on Windows. Furthermore you can use [Notepad++](https://notepad-plus-plus.org/download/v7.5.html). Working with GitHub and Chrome is basically the same as under macOS.

Furthermore you may require your cheat sheets you have prepared so far or you consult the links in the prior ReadingAssignments in case you get in troubles with html/css issues.

## Required Tasks
1. Outline the basic structure of your project.
   - What will be the big headlines of your information website?
   - Put every headline in a separate section
   - Describe the intended content of each section by a paragraph or two.
   - Take care of a good structure. Use lists, tables and other structuring Html elements to make your document easy to read and to understand.
   - Add images to illustrate your intents.
2. Validate your Html code.
3. Check your Html code whether it is properly formatted. Take care of proper indentation
3. Style your document
   - Take care to use different styling elements for fonts, text, backgrounds, lists, tables, etc.


## Hints
- Keep yourself limited to one html page, although this page might get a bit lengthy. We just want to play around with the basics. Do not think about navigation yet. This will come soon.
- Since you for sure will have more than one file to submit for this coding assignment it is required to create an extra folder in the repository where all your project files go in:
   - One html and one css file
   - Several image files

## Things to Learn
- Using basic Html and Css
- Structuring a mid-sized text with Html
- Styling a mid-sized text with css

## Evaluation
All coding assignments will get checked. Most common reasons that your assignment is marked down are:

- Project's Html pages do not validate
- One or more items in the *Required Tasks* section are not satisfied
- Submitted code is visually sloppy and hard to read

Finally check the [Rubrics](Rubrics.md) (Units 1 to 3 and "All" at the end of the table) to remember which criteria we use when checking your code.

## Extra Credit
Check out the page about [counters](https://www.w3schools.com/css/css_counters.asp) to make your document numbering its sections automatically. Consider the following snippet of html code.

```html
<article>
  <h1>Web Techniques</h1>
  <section>
    <h2>History</h2>
    <section>
      <h2>Early Years</h2>
      <p>Web started ...</p>
    </section>
    <section>
      <h2>Going Dynamic</h2>
      <p>...</p>
    </section>
  </section>
  <section>
    <h2>Important Contributors</h2>
    <dl>
      ...
    </dl>
  </section>
</article>
```

The rendered page should then have its sections as follows:
### Web Techniques
#### 1 History
##### 1.1 Early Years
Web started ...
##### 1.2 Going Dynamic
...
#### 2 Important Contributors
...

The concrete layout is of course a matter of your creativity. The point to get the extra credit is to get the numbering fixed.
