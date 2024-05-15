<h1>Loader component</h1>
<br>I created to use when have any data processing on power apps and want to block the user to create a qeue of actions.
<br><br>
<h2>How to Implement?</h2>
<p>
<br>&emsp;Create a component;
<br>&emsp;Insert a button, an image and a label;
<br>&emsp;Configure them as the file;
<br>&emsp;Insert in the front of all the screens;
<br>&emsp;On the 'Visible' propertie of the component insert a variable;
<br>&emsp;Everytime the app will process something, on the first row: "Set(varLoad, true)" and in the last row: "Set(varLoad, false)".
</p>
Everytime you perform that action the loader will appear in the screen, blocking the other components until it's done.

<h3>Hope you enjoy it!</h3>

![](https://github.com/guiiim/Power-Apps-Components/blob/main/Loader/clip.gif)
