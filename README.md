# modal-window
Use the functionality of adding and removing classes in order to change the 
appearance of elements.

Using "Esc" to close the modal window. Keyboard events are so-called global 
events because they do not happen on one specific element. For global events 
like keyboard events we usually listen on the whole DOCUMENT. 
(documetn.addEventListener)

For Keyboard events we have three listener: keydown, keyup, keypress

The function in addEventListener has access to the Event.
document.addEventListener('keydown', function(e) {})

learning about classList and its methods like "remove", "add" or contain. 
Useing class "hidden" to show and hide an Element. Using for loop to handle 
Event for Elements with same class using "document.querySelectorAll".

CSS styling for overlay, box-shadow and absolute positioned Elements. 
