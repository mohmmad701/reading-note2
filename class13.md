Local Storage:
in web applications, cookies can be used to store limited data, but there are disadvantages.
cookies are part of the http request, which means they slow the web app down by transmitting repeated data, and they send data unencrypted.
cookies are limigted to 4 KB of data.
Storage Hacks:
Dynamic HTML Behaviors were introduced in Internet Explorer
one of these beheviors was userData
userData allows a web page to sture up to 64KB of data per domain.
this data is stored in a XML-based structure.
Adobe had Flash cookies, or Local Shared Objects.which allows 100 KB per domain.
HTML5 Storage:
HTML5 Storage is a way for web pages to store named key/value pairs locally, within client web browser.
it is implemented natievly in the web browser, and the data persists.
use the below code to check it html5 storage is supported

if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}
the Storage Interafce:

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.
interface Storage {
  getter any getItem(in DOMString key);
  setter creator void setItem(in DOMString key, in any data);

  /*
  methods for removing and clearing the value from a given key and clearing storage area

  deleter void removeItem(in DOMString key);
  void clear();

  */
};


var foo = Storage.getItem("bar");
// ...
Storage.setItem("bar", foo);
If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.
Notes During Class:
data is created and collected using JS, but refreshing the page kills all of that data.

in this class, our data is not going to leave the browser.

we will use Local Storage.

API, just like document, but is used to store data and allow it to persist within out file system.
there is a directory in the browser that can store this data.
Example: username/password tokens are stored in this directory.
only accessible via the web-browser.
each url has its own spot in localStorage files.

5 MB limit for data. and it is always stored in Key/Value format. and as a string.

localStorage.setItem(key, value) method for placing something in local staorage.

localStorage.getItem(key,value) method for grabbing something from local storage.

localStorage.clear() method for clearing data from storage.

JSON object is another API for manipulating javascript objets.

JSON.stringify turns a Javascript object or array into a string.

JSON.parse turns a string that contains js-object notation and converts it back into a js-object.

Example:

var nick = {
  name: "nick",
  age: "26",
};
//stringfy to set the item to storage
var nickString = JSON.stringify(nick);
localStorage.setItem("nick", nickString);

//parse the item after getting it back
localStorage.getItem("nick");
var getbackNick = JSON.parse(nickString);