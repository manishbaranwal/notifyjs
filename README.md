Notify.js
=====

> A simple, yet fully customizable notification library

See demos and full documentation at:

## http://notifyjs.com/

SYNOPSIS
====

Global Notifications
----

    $.notify("Hello World");

Element Notifications
----

    $(".elem-demo").notify("Hello World");
    
    // where x is one letter: [t]op, [b]ottom, [m]iddle
    // where y is one letter: [l]eft, [r]ight, [c]enter
    $(".elem-demo").notify("Hello World", {position: "x y"});

COPYRIGHT
====

Notify.js is released under the [MIT License](https://opensource.org/licenses/MIT).

Copyright © Jaime Pillora &lt;dev@jpillora.com&gt;
