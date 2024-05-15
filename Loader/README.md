<h1>Loader component</h1>
<br>I created to use when have any data processing on power apps and want to block the user to create a qeue of actions.
<br><br>
<h2>How to Implement?</h2>
<p>
  Create a component;
  Insert a button, an image and a label;
  Configure them as the file;
  Insert in the front of all the screens;
  On the 'Visible' propertie of the component insert a variable;
  Everytime the app will process something, on the first row: "Set(varLoad, true)" and in the last row: "Set(varLoad, false)".
</p>
Everytime you perform that action the loader will appear in the screen, blocking the other components until it's done.

<h3>Hope you enjoy it!</h3>

![](https://github.com/guiiim/Power-Apps-Components/blob/main/Loader/clip.gif)
