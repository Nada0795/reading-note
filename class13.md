# LOCAL STORAGE FOR WEB APPLICATIONS


### Cookies have three potentially dealbreaking downsides:

1. Cookies are included with every HTTP request, thereby slowing down
your web application by needlessly transmitting the same data over and over

2. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)


3. Cookies are limited to about 4 KB of data — enough to slow down your application, but not enough to be terribly useful.

> What we really want is a lot of storage space on the client that persists beyond a page refresh and isn’t transmitted to the server


* userData allows web pages to store up to 64 KB of data per domain,
in a hierarchical XML-based structure. (Trusted domains, such as intranet sites,
can store 10 times that amount. And hey, 640 KB ought to be enough for anybody.) 
IE does not present any form of permissions dialog, and there is no allowance for increasing the amount of storage available

### Gears

* its open source browser plugin aimed at providing additional capabilities in browsers.
* provides an API to an embedded SQL database based on SQLite. 
* After obtaining permission from the user once, Gears can store unlimited amounts of data per domain in SQL database tables.

# HTML5 Storage
* ** it’s a way for web pages to store named key/value pairs locally,
within the client web browser. Like cookies, this data persists even after you navigate away from the web site,
close your browser tab, exit your browser, or what have you.
Unlike cookies, this data is never transmitted to the remote web server.
Unlike all previous attempts at providing persistent local storage, 
it is implemented natively in web browsers, so it is available even when third-party browser plugins are not. **


* is a specification named Web Storage, which was at one time part of the HTML5 specification proper,
but was split out into its own specification for uninteresting political reasons.
Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.”
The naming situation is made even more complicated by some related, similarly-named, emerging standards.


## USING HTML5 STORAGE
* HTML5 Storage is based on named key/value pairs. You store data based on a named key,
then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript,
including strings, Booleans, integers, or floats.
However, the data is actually stored as a string. If you are storing and retrieving anything other than strings,
you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.


## HTML5 STORAGE IN ACTION
Recall the Halma game.There’s a small problem with the game: if you close the browser window mid-game, you’ll lose your progress.
But with HTML5 Storage, we can save the progress locally, within the browser itself.
Here is a live demonstration. Make a few moves, then close the browser tab, then re-open it.
If your browser supports HTML5 Storage, the demonstration page should magically remember your exact position within the game, 
including the number of moves you’ve made, the position of each of the pieces on the board, and even whether a particular piece is selected


# ** HTML5 storage: **

* HTML5 Storage specification
* Introduction to DOM Storage on MSDN
* Web Storage: easier, more powerful client-side data storage on Opera Developer Community
* DOM Storage on Mozilla Developer Center.
* Unlock local storage for mobile Web applications with HTML5, a tutorial on IBM DeveloperWorks

# ** Web SQL Database: **

* Web SQL Database specification
* Introducing Web SQL Databases
* Web Database demonstration
* persistence.js, an “asynchronous JavaScript ORM” built on top of Web SQL Database and Gears


# **IndexedDB: **

* Indexed Database API specification
* Beyond HTML5: Database APIs and the Road to IndexedDB
* Firefox 4: An early walk-through of IndexedDB