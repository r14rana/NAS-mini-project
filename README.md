This is a code for building a network attached storage using nodemcu.
which is intefaced with an sd card module and oled disply.
The main inteface of the website allow a user to directly access the files inside the sd card.
HOW THE CODE WORKS:
the main code which is uploaded to the nodemcu connects to the wifi with the predefined 
credenstials.We will receive the ip address of our nodemcu when connected with the wifi,
then the code try to find if an sd card is initialized or not, with that info the code
connects the index.html file and displays the website over the ip address of the nodemcu.
and we are able to access all the files inside the sd card through the website.
