MILESTONE DEFINITION
The purpose of Milestone 2 is to produce an HTML web page with: a ‘head’; a ‘title’; a ‘header’; a ‘form’; and responsive styling.

HTML TAG
1.	The HTML document is initiated with a ‘<!DOCTYPE html>’. 
2.	The opening HTML tag goes immediately below the ‘doctype’ declaration, and it includes English as the language attribute. 
3.	Inside the HTML tag, there are two main tags: 
    a.	‘head’; and 
    b.	‘body’.

‘HEAD’ TAG
4.	Inside the ‘head’ tag there are several ‘meta’ elements with the following attributes: 
    a.	‘charset=”utf-8”: this is the default character encoding ‘meta’ attribute, and it is good practice to include it in the ‘head’.
    b.	Name=”description”: this adds more information about the nature of the task
    c.	Name=”keywords”: this adds a few keywords related to the task
    d.	Name=”viewport”: this allows the content on the HTML web page to avoid overflow, no matter what the screen size is
    e.	Name=”author”: the name of the author
5.	Inside the ‘head’ tag there is also a ‘title’ element indicating what the title of the HTML document is (this will appear as the title in the browser tab).
6.	Finally, at the end of the ‘head’ tag there is the ‘link’ element referring to the CSS stylesheet.

HTML ‘BODY’
7.	The structure within the opening and closing ‘body’ tag is as follows:
    a.	A ‘header’ section containing the ‘nav’ element, which includes listed items as links.
    b.	A ‘main’ opening and closing section containing the following sub-sections:
        i.	A section containing the ‘class=“banner-title”’ which contains the hero image and primary heading (H1) of the HTML document.
        ii.	A section containing the ‘class=“about”’.
        iii.	A section containing the ‘class=“publications”’.
        iv.	A section containing the ‘class=“contact”’, which includes the Form.
    c.	A ‘footer’ section which includes listed items as links.

HTML ‘FORM’
8.	The form contains the relevant HTML secondary heading (‘h2’) title with the opening and closing ‘form’ tag. 
9.	The form then includes a few ‘div’ tags to separate the following sections:
    a.	A mandatory text field to input the user’s email address, with the relevant ‘label’ and ‘input’ tags, in that order;
    b.	A mandatory text field for the first name of the user, with the relevant ‘label’ and ‘input’ tags, in that order;
    c.	A mandatory text field for the last name of the user, with the relevant ‘label’ and ‘input’ tags, in that order; 
    d.	An optional text field for the name of the user’s organisation, with the relevant ‘label’ and ‘input’ tags, in that order; 
10.	A heading 3 (‘h3’) introduces a further section with radio buttons, to choose from three possible options, with the relevant ‘input’ and ‘label’ tags, in that order. Finally, a heading 4 (‘h4’) introduces a text field option for the third radio button.
11.	A ‘submit‘ button completes the form.
STYLING THE DOCUMENT WITH CSS
12.	The styling of the document commences by giving the ‘body’ tag a sans-serif font, which is easier to read on screens and therefore more accessible. The choice of font throughout the document is in this case ‘Helvetica’. As the document is very short, consistency is preferred by using a single font.
13.	The ‘nav’ and ‘footer’ selectors have consistent formatting, initiating and closing the document with the same style, and good contrast between font and background colours, achieving AA standards of Web Content Accessibility Guidelines (WCAG) 2.1. On ‘hover’ the WCAG standard achieved is AAA.
14.	A transition property with a value of 0.5 seconds has been included in the ‘nav ul li a:hover’ selector, to make the top menus more dynamic on desktop. This is repeated in the ‘h1’ selector, with a transition property value of 1 second in this case. 
15.	Selectors ‘h2’, ‘h3’, and ‘h4’ are consistent in colour throughout the document, to give a sense of harmony.
16.	The paragraph (‘p’) selector has a good colour contrast with its background and good font size and line spacing to help people with dyslexia, achieving AAA WCAG accessibility standards both in the white background area (‘publications’) and in the shaded areas (‘about’ and ‘contact’).
17.	The transition from one sub-section of the HTML document to another is highlighted by alternating a white background in the ‘publications’ section with light brown backgrounds in the ‘about’ and ‘contact’ sections. 
18.	There’s a ‘button’ tag at the end of the ‘publications’ sub-section with good colour contrast, achieving AA accessibility standards with normal text. 
19.	The form has the same font style and sizes as the rest of the HTML document for consistency, and text fields (‘input’) include minimum margins to become easier separate and read. Text fields also have a different white background to be easily differentiated from the shaded section background, and have a border-radius property of 10 pixels to make them smoother. 
20.	The ‘submit’ button has the same colour contrast as the ‘nav’ and ‘footer’ selectors, with its font being larger for easier recognition as a button. 

RESPONSIVE CSS
21.	A ‘viewport’ value has been included in the ‘head’ tag so that text does not overflow, no matter what the screen size is. 
22.	Relative measurements (‘rem’ units) have been used for font sizes throughout the document, so that font adapts better to any device screen size. 
23.	Relative percentage measurements have also been used with padding and margins so that they relate to the width of the parent element and are more responsive. 
24.	Two media queries have been used on the ‘nav ul’ and ‘footer ul’ selectors to make the top menus and the footer links display as a column when the device screen size is under 416 pixels. 
