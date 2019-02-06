# sort application

<ol><li>Which algorithm is faster?
<br>Bucket sort is faster than Quick sort
<li>Where is the entry point of the application? (The place execution begins - provide the fully qualified class name and method name)<br>

<li>What is the name of the code file that displays the main form?<br>
<li>What method does the main form constructor call?  Hint: look at frmMain.cs, right-click if necessary to "View Code", and then find the constructor (the constructor method name is the same as the class name.)<br>
<li>What is the fully qualified name of the class from which the main form is derived? <br>
<li>Add code to the Form1_Load method - use intellisense and your IDE to determine: What is this.tbSamples.Value? Set the default value to 10x your team number (if team 1, use 100). If this causes an error, read the error message carefully and make changes as needed.<br>
<li>What is this.cboAlg1?  Set its SelectedIndex to an integer so that the default is Bucket Sort.<br>
<li>What is this.cboAlg2? Set its SelectedIndex to an integer so that the default is Quick Sort.<br>
<li>Use AppDomain.CurrentDomain.BaseDirectory.ToString() to get the base directory. <br>
<li>Create a new method called InitializeOutputFolder() and call it - see the suggested content below. What does this method do? <br>
<li>What is this.cmdShuffle?  Call its PerformClick() method before exiting Form1_Load.<br>
<li>What is this.cmdSort?  Change its appearance (e.g. ForeColor or BackColor) to highlight it so users will click it. <br>
<li>Make at least one other obvious improvement or customization as desired.<br>
We have changed the color of lines in the application from black to brown