# READ ME

## CSS: Positioning


### Objectives

- Use positioning properties (`position`, `left`, `right`, `top`, `bottom`, `z-index`).


### Instructions

Clone this repository by clicking "Clone or Download". Select "Download ZIP".

Included in the `exercise-10` (or `exercise-10-master`) directory are the following files:

- README.md (this file)
- css
  - style.css
- index.html

Do not move any files outside of this directory.

Add new files to the `exercise-10` directory.

**Never copy and paste code; always type it in by hand.**


### Tasks

All work needs to be done in the `exercise-10` folder. (It may be named `exercise-10-master`.)

1. Open `css/style.css` in Atom and `index.html` in your browser.

2. Create a CSS block which changes every `em` inside the section with an `id` of `relative` as follows: Set the background color to `#ccc`, position `em` as `relative`, move it 20 pixels up and 30 pixels right. (Yes, it is going to look really weird.)

3. Create a CSS block which turns `nav` into a fixed element. Set its width to `100%` and its background color as `rgb(219,81,73)`. Set its positioning as `fixed`. Move it all the way to the top and all the way to the left. (Bonus: As you can see, the `header` is hidden underneath the `nav`. Create a CSS block for `header` and use the correct box model property to adjust the header so it shows up just below the sticky nav.)

4. Create a CSS block for `div` which sets its width at 200 pixels and its height at 200 pixels. Create an `id` selector for **each** div which sets the background color accordingly (i.e. for 'red', use a shade of red). All `div`s are to be contained within `article`.

5. Add a 2 pixel, solid, dark gray border to `article`. Set its minimum height to be 500 pixels.

6. Position the `red` block in the bottom right corner and offset it by 20 pixels from the right. Position the `yellow` div in the top right corner and offset it 20 pixels from the top. Position the `green` div in the top left corner and offset it 20 pixels from the top and 20 pixels from the left. Position the `blue` div in the bottom left corner. There are no offsets for the `blue` div.

7. When the page scrolls, our relatively positioned `em`s hover over our sticky nav. Change the `z-index` property of `nav` so it will always be in front of the content on the page.


### How to tackle this project

Decide what you need to do, one step at a time.

Write down each task as you go. When you complete it, check it off. Decide on the next task to tackle.

Once you get into marking up content within the body, it is okay if you get stuck. Set aside that task and move on to another. Note the item you struggled with (so you can spend time on it later) and keep moving forward.

### Am I done?

Again, it is not expected for you to complete this exercise in class. If you finish, have your professor give it a look. If you are finished, re-download the repository files and go through the fixes again. Practice, repetition is an excellent way to learn.

### Why isn't X working?

Before asking for help, try working through the problem first. Refer to your notes, book or any resources made available to you for this course.

When something does not appear to work as you expect, ask yourself:

- Did I forget to close a tag?
- Are there typos in element, attribute, value names?
- Did I forget to include quotes around attributes?
- Are my file names, directory paths correct?
- Does my code validate?
- Are there typos in my file name?
- Is the file in the correct directory?
- Is my style sheet properly linked?
- Are my selectors correct?
- Do my properties exist? Are there typos?
- Does the property accept the value I am giving it?
- Is all my CSS punctuation there?

Remember, you can always refer to your notes, book or any resources made available to you for this course.

**Good luck!**
