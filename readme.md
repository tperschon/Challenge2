## USER STORY

* AS AN employer

* I WANT to view a potential employee's deployed portfolio of work samples

* SO THAT I can review samples of their work and assess whether they're a good candidate for an open position

### ACCEPTANCE CRITERIA

* GIVEN I need to sample a potential employee's previous work

* WHEN I load their portfolio

* THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them

* WHEN I click one of the links in the navigation

* THEN the UI scrolls to the corresponding section

* WHEN I click on the link to the section about their work

* THEN the UI scrolls to a section with titled images of the developer's applications

* WHEN I am presented with the developer's first application

* THEN that application's image should be larger in size than the others

* WHEN I click on the images of the applications

* THEN I am taken to that deployed application

* WHEN I resize the page or view the site on various screens and devices

* THEN I am presented with a responsive layout that adapts to my viewport

## Information on index.html
```
The document is linked to assets/css/style.css
Normalize.css is used as a css reset
Comments are found throughout the entirety of style.css

At the top of the page, there is a header with my name, portrait and a navigation bar
Scrolling over navigation bar items causes them to glow
Clicking on a navigation bar item takes you to different parts of the page corresponding to their HTML id
The first portfolio item in the portfolio section is larger than the rest, taking the entire width of the flex space
The rest of the portfolio items scale across the flex space
Each portfolio item takes you to a live site with an app
The about me section has many paragraphs with information about me
The paragraphs use flex to display in rows, and are each indented on their first line
The contact me section contains hyperlinks to different methods of contacting me
Each hyperlink is live and will navigate you, if possible, to a method of contacting me
The footer is included within the contact me section, intentionally as it fits quite nicely

Semantic elements are used within the document to give it accessibility
Images have alt text for accessibility
Changing screen sizes will cause the document to change responsively
Only one additional breakpoint is specified, more can be added but it did not seem necessary given how the page scales
```
## Information on portfolio.html
```
The document is linked to assets/css/main.css & assets/css/normalize.css
Normalize.css is used as a css reset
Comments are found throughout the entirety of main.css

This was my first pass at this assignment
I thought the look was a little dated so I wanted to make another version
Rather than start over, I decided to use link cross link the documents rather than simply use placeholders

At the top of the page, you can see my name
Below my name, you'll see a navigation bar
Hovering over items on the navigation bar will illuminate the entire around each navigation bar item
Clicking on a navigation bar item takes you to different parts of the page corresponding to their HTML id
Below the navigation bar is my portrait
Below my portrait, the page is sectioned vertically, with the about me section first
Each section of the page has a centered title with a background and border, giving it the appearance of a strip
When viewed on a large screen, the about me section used a column flex display to separate the paragraphs
Paragraphs are indented on their first line
When viewed on a smaller screen, the about me section goes to a vertical display
After the about me section is the portfolio section
Each portfolio item takes you to a live site with an app
Below the portfolio section is a strip that denotes the footer away from everything else
The footer contains the contact html id and a hyperlink to email me

Semantic elements are used within the document to give it accessibility
Images of halt text for accessibility
Changing screen sizes will cause the document to change responsively
Only one additional breakpoint is specified. I had more planned initially but decided to start index.html instead
```
## CSS Information
```
main.css has a set of rules at the bottom that are commented out
This ruleset provides a tool to see when different screen breakpoints take over
This tool displays one of three faded spans, whose visibility depends on the width, in the top right corner
These spans denote what device type is being attempted to cater for, between mobile, tablet and desktop
I did not include this tool in style.css as I had gotten more used to things by then
```
## Image Information
```
Images are shared between the documents
Images are of my own projects I built or of myself
```