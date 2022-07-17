# Live-HTML-interpreter
Hypertext Markup Language” abbreviated as HTML, is the standard markup language for creating webpages. Still, most of the time, we have witnessed that we require an editor of some sort to write a simple HTML code. SO let's create a live interpreter, where you can write and check out the HTML output at the same time. 

To understand,

There are namely two divisions in the code:- a div with“d1” id, here, we have a text area element which executes the function show() on the event: onkeyup, implying that the function show() will be executed on clicking a key, in the text area.

The second div with id “d2” is to show the output, where the show() function after execution will display the output.

The show() function: the main cardholder for the interpreter,

x= document.getElementById("d2");

z=document.getElementById("textArea");

x.innerHTML = z.value;

The above lines are the ones, that take your input in the text area and display it in the other half of your screen
