<head></head>
    Define meta contents of website

<meta charset="UTF-8" />
    Tells the browser how to encode characters

<meta name="viewport" content="width=device-width, initial-scale=1.0" />
    To make the page looks the same on all mobile devices

<title></title>
    Gives search engines extra information about the page, and tab name

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

FORMS
-it is a good practice to provide each submittable element with a name attribute, to identify the element in the form submission
<form action="https://domainname.domain">
method attribute specifies how to send form-data to the URL specified in the action attribute
<form method="post" action="https://register-demo.freecodecamp.org">        form-data sent as data in the request body
<form method="get" action="https://register-demo.freecodecamp.org">         form-data sent as URL parameters
    <fieldset>
        <legend>Input Types</legends>
        <input type="text">
        <input type="email">
        <input type="password">
            minlength="n"
            pattern="[a-z0-5]{8,}"
        <input type="submit" value="Submit">        automatically set to submit its nearest parent form element
        <input type="radio">
        <input type="checkbox">
        <input type="file">
        <input type="number">
            min="n"
            max="n"
    </fieldset>
    <fieldset>
        <legend>Using the Input element</legend>
            <label for="first-name">Enter your first name: <input id="first-name" type="text" name="first-name" placeholder="" required></label>
    </fieldset>
    <fieldset>
        <legend>Using the Input type Radio</legend>
            <label for=""><input id="" type="" name="" value="" required checked>Select Me</label>
    </fieldset>
    <fieldset>
        <legend>Using the Select element</legend>
        <label for="">
            <select id="" name="">
                <option value=""></option>
            </select>
        </label>
    </fieldset>
    <fieldset>
        <legend>Using the TextArea Element</legend>
        <textarea id="" rows="n" cols="n"></textarea>
    </fieldset>
    <button type="submit">Submit</submit>
</form>
<label></label>         associates text for an input element with the input element itself
<fieldset></fieldset>   used to group related inputs and labels together in a web form
<legend></legend>       acts as a caption for the content for <fieldset> element