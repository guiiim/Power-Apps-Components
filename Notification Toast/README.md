<h1>Notification Toast component</h1>
<br>I created this component to substitte the Notify() function from Power Apps.
<br><br>
<h2>How to Implement?</h2>
<p>
    &emsp;Create a component;
<br>&emsp;Create two input text properties in the component ('type' and 'message');
<br>&emsp;Insert a button, an image and two labels;
<br>&emsp;Configure them as in the file;
<br>&emsp;Insert in the front of all the screens;
<br>&emsp;Create a variable with status, duration, type and message attributes;
<br>&emsp;To trigger the toast, set the variable: status: true, duration in seconds, type (Error, Information, Success or Warning), and the message.
</p>
Everytime you set the variable with those attibutes the toast will appear with the message.
<br>For the error messages, is necessary to click on the top icon to close it.
<br>The others messages, are going to be visible depending on the 'duration' value of the variable.

<h3>Hope you enjoy it!</h3>

![](https://github.com/guiiim/Power-Apps-Components/blob/main/Notification%20Toast/clip.gif)
