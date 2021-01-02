# Reading-notes-201-class06
## From the Duckett JS book
+ **Object Literals**:<br>
+ Object literal should be used if you want to create objects on the go with no intention of copying values to another object or maybe mapping one object to another.
If you will need to create multiple instances of a structure and perform operations based on predefined values, then you should use a function constructor — i.e., an instance object.<br>
+ **Document Object Model**: <br>
+ The DOM (Document Object Model) is an interface that represents how your HTML and XML documents are read by the browser. 
It allows a language (JavaScript) to manipulate, structure, and style your website. After the browser reads your HTML document,
it creates a representational tree called the Document Object Model and defines how that tree can be accessed.<br>
+ avaScript programs may inspect and interfere with the document that the browser is displaying through a data structure called the DOM. This data structure represents the browser’s model of the document, and a JavaScript program can modify it to change the visible document.<br>
+ The DOM is organized like a tree, in which elements are arranged hierarchically according to the structure of the document. The objects representing elements have properties such as parentNode and childNodes, which can be used to navigate through this tree.<br>
+ The way a document is displayed can be influenced by styling, both by attaching styles to nodes directly and by defining rules that match certain nodes. There are many different style properties, such as color or display. JavaScript code can manipulate an element’s style directly through its style property.
