String.toDOM
====

A simple String method to convert a string into DOM nodes

How to use
----------

### Example:

    #JS
    var code = '<p>A link to <a href="http://www.mootools.net">Mootools.net</a></p>'.toDOM(); // Return a NodeList with the DOM nodes , code[0] is the <p>
    alert(code[0].getElement('a').get('href')); // alert "http://www.mootools.net"
    code.inject(document.body); // Inject the nodes into the body element