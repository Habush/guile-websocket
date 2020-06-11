# guile-websocket

This is the fork of David Thompson's `guile-websocket` library. You can find the original code at https://git.dthompson.us/guile-websocket.git

Guile-WebSocket is an implementation of the WebSocket protocol as
defined by [[https://tools.ietf.org/html/rfc6455][RFC 6455]].

* Test it out

Run the example server:

#+BEGIN_SRC sh
  GUILE_LOAD_PATH="$PWD:$GUILE_LOAD_PATH" guile test.scm
#+END_SRC

Then, open the =text.html= page in your web browser.  If everything
works, "!ereht ,olleH" will be written to the JavaScript console.