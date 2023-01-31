<head></head>
    Define meta contents of website

<meta name="viewport" content="width=device-width, initial-scale=1.0" />
    To style the page similarly on Mobile, Desktop, Laptop

<div></div>
    Mainly used for design layout purposes

<main></main>
    Specify as main content
<section></section>
    Isolating contect by section
<article></article>
    Contains multiple elements that have related information
<footer></footer>

<hr>
    Display a divider between contents

<h1></h1>
    Heading element: Applicable from 1-6, highest to lowest respectively

<p></p>
    Paragraph element

<strong></strong>
    Bold text: Used for Accessibility

<em></em>
    Italized text: Used for Accessibility

<!-- -->
    Commenting

<ol>
    <li></li>
</ol>
    Ordered list - List item

<ul>
    <li></li>
</ul>
    Unordered list - List item

<a href="">
    Anchor element: Linking
<a href="" target="_blank">
    Anchor element: Link to be opened in a new tab

<img src="" alt="">
    Image element: Source as relative/absolute path or URL, Alternate text

<figure>
    <img src="" alt="">
    <figcaption></figcaption>
</figure>
    Represents self-contained content to associate an image with a caption

<form action="https://domainname.domain">
    <fieldset>
    <legend>Description of fieldset</legend>
    <input id="it" type="radio" name="field" value="it" checked><label for="it">Information Technology</label>
    <input id="cs" type="radio" name="field" value="cs"><label for="cs">Computer Science</label>
    </fieldset>
    <fieldset>
    <legend>Description of fieldset</legend>
    <input id="html" type="checkbox" name="prog-lang" value="html" checked><label for="html">HTML</label>
    <input id="css" type="checkbox" name="prog-lang" value="css"><label for="css">CSS</label>
    <input id="js" type="checkbox" name="prog-lang" value="js"><label for="js">Javascript</label>
    </fieldset>
    <input type="text" name="firstName" placeholder="" required>
    <button type="submit">Submit</submit>
</form>
<label></label>         associates text for an input element with the input element itself
<fieldset></fieldset>   used to group related inputs and labels together in a web form
<legend></legend>       acts as a caption for the content for <fieldset> element