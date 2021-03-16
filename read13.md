
# *THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS*

### INTRODUCING HTML5 STORAGE
what is HTML5 Storage? Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.

**but How can we USING HTML5 STORAGE**
you will need to use functions like parseInt( or parseFloat( to coerce your retrieved data into the expected JavaScript datatype.Calling setItem( with a named key that already exists will silently overwrite the previous value. Calling getItem( with a non-existent key will return null rather than throw an exception.

[C:\Users\STUDENT\Desktop\htmlmmm.PNG]

Like other JavaScript objects, you can treat the localStorage object as an associative array. Instead of using the getItem() and setItem() methods, you can simply use square brackets

**TRACKING CHANGES TO THE HTML5 STORAGE AREA**
The storage event is fired on the window object whenever setItem, removeItem(, or clear( is called and actually changes something. For example, if you set an item to its existing value or call clear( when there are no named keys, the storage event will not fire, because nothing actually changed in the storage area.

[C:\Users\STUDENT\Desktop\hhhh.PNG]


**HTML5 STORAGE IN ACTION**
Let’s see HTML5 Storage in action. Recall the Halma game we constructed in the canvas chapter. There’s a small problem with the game: if you close the browser window mid-game, you’ll lose your progress. But with HTML5 Storage, we can save the progress locally, within the browser itself. Here is a live demonstration. Make a few moves, then close the browser tab, then re-open it. If your browser supports HTML5 Storage, the demonstration page should magically remember your exact position within the game, including the number of moves you’ve made, the position of each of the pieces on the board, and even whether a particular piece is selected.

(C:\Users\STUDENT\Desktop\sss.PNG)