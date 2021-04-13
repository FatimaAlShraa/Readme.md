# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

persistent local storage is areas where native client applications have held an advantage over web applications
If your native client application needs local storage beyond key/value pairs, you can embed your own database, 
invent your own file format, or any number of other solutions.

so before HTML5 what we want :
+ a lot of storage space
+ on the client
+ that persists beyond a page refresh
+ and isn’t transmitted to the server

DHTML Behaviors 

great many things and included them in their browser-to-end-all-browser-wars, Internet Explorer

userData

allows web pages to store up to 64 KB of data per domain

In 2002, Adobe introduced a feature in Flash 6 the feature is properly known as Local Shared Objects. Briefly, it allows Flash objects 
to store up to 100 KB of data per domain.

In 2007, Google launched Gears ,Gears can store unlimited amounts of data per domain in SQL database tables.

HTML5 Storage” is a specification named Web Storage, which was at one time part of the HTML5 specification proper,so 
will we talk about HTML5 Storage way for web pages to store named key/value pairs locally, within the client web browser
The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats

interface Storage {
  getter any getItem(in DOMString key);
  setter creator void setItem(in DOMString key, in any data);
};
Calling setItem() with a named key

LIMITATIONS IN CURRENT BROWSERS
“5 megabytes” is how much storage space each origin gets by default
“QUOTA_EXCEEDED_ERR” is the exception that will get thrown if you exceed your storage quota of 5 megabytes. 

