Main Functionality Of Browser:-

A web browser takes you anywhere on the internet. It retrieves information from other parts of the web and displays it on your  desktop or mobile device.
The information is transferred using the Hypertext Transfer Protocol, which defines how text, images and video are transmitted on the web.
When the user inputs any URL (uniform resource locator) in the web browser, the user is navigated to that website by the browser quickly.

Main functions of the internet browser:-

1. Sending requests to and retrieving data from the server:-
Internet browsers are used to fetch and retrieve hypertext mark-up text from the internet to the user device.
It can be static like the HTML pages only or dynamic data like data from the form.
When the user clicks a button or page it is retrieved from the server and the web browser displays the same content.

2. Displaying webpage content:-
Web browsers act as an interface for users to interact with web pages. Different internet browsers may display the same web page differently. 
This depends on how it is designed. 

3. Caching of most frequently accessed data to increase browsing speed.
The web browser saves the content that users retrieve frequently to save time when retrieving data from the server. 
Instead of getting the page from the server, it retrieves some components that were saved in the client computer for fast operation.
The content or components that are saved are those that are less frequently changed. The period of data cached depends on how the browser is set.

4. Provide a secure method of accessing content over the internet
The internet browser provides secure methods for accessing data over the internet. 
It used different protocols that ensure data is encrypted when it is being transferred from server to client computer

High Level Components of browser:-
1) The user interface:- This includes the address bar, back/forward button, bookmarking menu, etc. 
   Every part of the browser display except the window where you see the requested page.
   
2) The browser engine:- The actions between the UI and the rendering engine.

3) The rendering engine:- Responsible for displaying requested content. 
   For example if the requested content is HTML, the rendering engine parses HTML and CSS, and displays the parsed content on the screen.
   
4) Networking:- for network calls such as HTTP requests, using different implementations for different platform behind a platform-independent interface.

5) UI backend:- used for drawing basic widgets like combo boxes and windows. This backend exposes a generic interface that is not platform specific.
   Underneath it uses operating system user interface methods.
   
6) JavaScript:- interpreter. Used to parse and execute JavaScript code.

7) Data storage:- This is a persistence layer. The browser may need to save all sorts of data locally, such as cookies. 
  Browsers also support storage mechanisms such as localStorage, IndexedDB, WebSQL and FileSystem.
  
Rendering engine :-
A rendering engine is software that draws text and images on the screen. The engine draws structured text from a document (often HTML), 
and formats it properly based on the given style declarations (often given in CSS). 
A rendering engine, also known as a browser engine or layout engine, is an essential software component of every major web browser.
It deftly combines structure and style to draw the web page on your screen and determines which bits of it are interactive.

HTML Parser does following things in the order:-
1.parse HTML character by character
2.tokenize HTML tag by tag
3.create the nodes of DOM Tree from the tokens, and mount the nodes on the tree
4.compute CSS rules and apply them on the nodes of the DOM Tree.

Parsing means analyzing and converting a program into an internal format that a runtime environment can actually run, 
for example the JavaScript engine inside browsers. 
The browser parses HTML into a DOM tree. HTML parsing involves tokenization and tree construction.

Script Processor:-
 script processor executes Javascript code to process an event. The processor uses a pure Go implementation of ECMAScript 5.1 and has no external dependencies. 
 This can be useful in situations where one of the other processors doesn't provide the functionality you need to filter events.
 
Tree Construction:-
A tree data structure is defined as a collection of objects or entities known as nodes that are linked together to represent or simulate hierarchy. 
A tree data structure is a non-linear data structure because it does not store in a sequential manner.
It is a hierarchical structure as elements in a Tree are arranged in multiple levels.
In the Tree data structure, the topmost node is known as a root node. Each node contains some data, and data can be of any type. 
In the above tree structure, the node contains the name of the employee, so the type of data would be a string.
Each node contains some data and the link or reference of other nodes that can be called children.

Order of script processing:-
In order to assess the consequences of any such decision, it helps to understand how browsers work: When the browser processes an HTML document, it does so from top to bottom. Upon encountering a <script> tag, it halts (“blocks”) further processing[2] in order to download the referenced script file. Only after that download has completed and the respective JavaScript code has been processed, HTML processing continues.

DOM Layout:-
The Document Object Model (DOM) is a cross-platform and language-independent interface that treats an XML or HTML document as a tree structure wherein each node is an object representing a part of the document. The DOM represents a document with a logical tree.Each branch of the tree ends in a node, and each node contains objects. DOM methods allow programmatic access to the tree; with them one can change the structure, style or content of a document.Nodes can have event handlers attached to them. Once an event is triggered, the event handlers get executed.

DOM painting:-
Browser uses dom to decide what to display. In react, this is referred to as painting, because whenever something is added to a dom, browser has to re-paint the screen.Browser computes the geometry of the layout and its elements based on the render tree. Browser paints pixel by pixel to create the visual representation we see on the screen.
  

