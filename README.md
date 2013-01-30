WebGLBook [JongleurX fork]
==========================

*** So far, the only real difference between this fork and the original version is that
*** some HTML files have been added for navigation. It turns out that having a navigation
*** pane that is located at the "local root" of the code samples and includes links to the
*** various sample demos is enough to get around the CORS security restrictions of at least
*** Firefox. There are still a few demos that require the SimpleHTTPServer to run correctly,
*** but most of them work fine. This may be helpful for those folks who do not have admin
*** rights to install Python or run a local web server.
***
*** Eventually, some additional examples and tweaked verisons of the demos will be added
*** based on feedback from the participants of the WebGL study group using this book as a
*** reference in Redmond, WA.

Little Tweaks to the Code Examples for Tony Parisi's Book, WebGL Up and Running.

You can grab the stable version that corresponds with August 2012 release of the book by getting the tag v1.0 (see Tags).

Please note that currently these examples are based on an older version of Three.js (r46). A snapshot of that 
version is included as libs/Three.js. I am currently working on upgrading to the latest stable Three.js (r50). Thanks
for your patience!

VERY IMPORTANT TECH NOTE: It seems that folks are missing my little tech tip at the bottom of page 19,
in the section titled "Setting up Three.js." These examples *must* be run from a web server such as 
Apache. localhost:// is fine but it needs to be coming from a server or loading external files such as 
textures and JSON for models simply won't work because of browser security restrictions. Or, if you have
Python installed on your machine, you can run the simple web server module and serve up files that way:

cd <path to the example files>
python -m SimpleHTTPServer

Then point your web browser at

http://localhost:8000/

Happy coding!
