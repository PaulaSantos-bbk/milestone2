Milestone definition
The purpose of Milestone 2 is to produce an HTML web page with: a ‘head’; a ‘title’; a ‘header’; a ‘form’; and responsive styling.

HTML tag
1.	The HTML document is initiated with a ‘<!DOCTYPE html>’. 
2.	The opening HTML tag goes immediately below the ‘doctype’ declaration, and it includes English as the language attribute. 
3.	Inside the HTML tag, there are two main tags: 
a.	‘head’; and 
b.	‘body’.

HTML ‘head’
4.	Inside the ‘head’ tag there are several ‘meta’ elements with the following attributes: 
a.	‘charset=”utf-8”: this is the default character encoding ‘meta’ attribute, and it is good practice to include it in the ‘head’.
b.	Name=”description”: this adds more information about the nature of the task
c.	Name=”keywords”: this adds a few keywords related to the task
d.	Name=”viewport”: this allows the HTML web page to be responsive in Chrome, with text wrapping around the window no matter what the screen size is
e.	Name=”author”: the name of the author
5.	Inside the ‘head’ tag there is also a ‘title’ element indicating what the title of the HTML document is (this will appear as the title in the browser tab).
6.	Finally, at the end of the ‘head’ tag there is the ‘link’ element referring to the CSS stylesheet.

HTML ‘body’
7.	The structure within the opening and closing ‘body’ tag is as follows:
a.	A ‘header’ section containing the ‘nav’ element, which includes listed items as links.
b.	A ‘main’ opening and closing section containing the following sub-sections:
i.	A section containing the ‘class=“banner-title”’ which contains the hero image and primary heading (H1) of the HTML document.
ii.	A section containing the ‘class=“about”’.
iii.	A section containing the ‘class=“publications”’.
iv.	A section containing the ‘class=“contact”’, which includes the Form.
c.	A ‘footer’ section which includes listed items as links.

HTML ‘form’
8.	The form contains the relevant HTML secondary heading (‘h2’) title with the opening and closing ‘form’ tag. 
9.	The form then includes a few ‘div’ tags to separate the following text field sections:
a.	A mandatory section to input the user’s email address, with the relevant ‘label’ and ‘input’ tags, in that order;
b.	A mandatory section for the first name of the user, with the relevant ‘label’ and ‘input’ tags, in that order;
c.	A mandatory section for the last name of the user, with the relevant ‘label’ and ‘input’ tags, in that order; 
d.	An optional section for the name of the user’s organisation, with the relevant ‘label’ and ‘input’ tags, in that order; 
10.	A heading 3 (‘h3’) introduces a further section with radio buttons, to choose from three possible options, with the relevant ‘input’ and ‘label’ tags, in that order. Finally, a heading 4 (‘h4’) introduces a text field option for the third radio button.
11.	A ‘submit‘ button completes the form.

Styling the document with CSS
12.	The styling of the document commences by giving the ‘body’ tag a sans-serif font, which is easier to read on screens and therefore more accessible. The choice of font throughout the document is in this case ‘Helvetica’. As the document is very short, consistency is preferred by using a single font.
13.	The ‘nav’ and ‘footer’ selectors have consistent formatting, initiating and closing the document with the same style, and good contrast between font and background colours, achieving a AA standard of Web Content Accessibility Guidelines 2.1.
14.	A transition property with a value of 0.5 seconds has been included in the ‘nav ul li a:hover’ selector, to make the top menus more dynamic. This is repeated in the ‘h1’ selector, with a transition property value of 1 second in this case. 
15.	Selectors ‘h2’, ‘h3’, and ‘h4’ are consistent in colour throughout the document, to give a sense of harmony.
16.	The paragraph (‘p’) selector has a good colour contrast with its background and good font size and line spacing to help people with dyslexia, achieving at least AA accessibility standards. 
17.	The transition from one sub-section of the HTML document to another is highlighted by alternating a white background in the ‘publications’ section with light brown backgrounds in the ‘about’ and ‘contact’ sections.
18.	There’s a ‘button’ tag at the end of the ‘publications’ sub-section with good colour contrast, achieving AA accessibility standards. 
19.	The form has the same font style and sizes as the rest of the HTML document for consistency, and text fields (‘input’) include minimum margins and become easier to read. Text fields also have a different white background to be easily differentiated from the brown background, and have a border-radius property of 10 pixels to make them smoother. 
20.	The ‘submit’ button has the same colour contrast as the ‘nav’ and ‘footer’ selectors, with its font being larger for easier recognition as a button.
 
Making CSS responsive
21.	Apart from the ‘viewport’ value included in the ‘head’ tag, which makes text wrap around in Google Chrome browser no matter what the screen size is, two media queries have been used on the ‘nav ul’ and ‘footer ul’ selectors to make the top menus and the footer links display as a column when the screen size is less than 416 pixels. 
