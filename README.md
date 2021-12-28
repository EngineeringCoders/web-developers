# What is DOM?
-> The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

A web page is a document that can be either displayed in the browser window or as the HTML source. In both cases, it is the same document but the Document Object Model (DOM) representation allows it to be manipulated. As an object-oriented representation of the web page, it can be modified with a scripting language such as JavaScript.

# What is the difference between DOM & Virtual DOM?
->The updation process is relatively faster in Virtual DOM in comparision of normal DOM.
-> In VDOM only the specific part of area can be changed instead of updating the whole document.
->In DOM it creates a new DOM if elemets updates, In VDOM it just updates JSX if elements updates.
->DOM Manipulation can be expensive when compared to VDOM.
-> Wastage of memory is low in VDOM in comparision to DOM.
