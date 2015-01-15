# anchor2post

(deutsch weiter unten / German text below)

USAGE:
provide the key-value pairs as anchor to this html-script
use anchor2posturl=url to specify the url to post the query to
use anchor2postfavicon=path/to/favicon to specify a favicon
example: anchor2post.html#anchor2posturl=https://ixquick.de/do/search&anchor2postfavicon=https://eu.ixquick.com/favicon.ico&query=searchterm

advantages/ disadvantages:
- there is cookie support to determine whether to auto submit the form or not. this is useful when you go back to this site (via browser history) because then you most likely do not want to submit the form again. if there is no cookie support a very simple test using the history length will be done
- there is favicon support to have a nice icon when this is saved as a bookmark in the browser. it is not working very well since the favicon is added dynamically. this could result in an empty icon after a browser restart.
- the server should not see the query since it is only an anchor and so not send to the server, but you need javascript enabled for this html-script to work and thus trust the server that delivers the html
- for comfort reasons you might also need cookies enabled and perhaps from the value in the cookie the anchor can be recalculated.
- there might be problems if there is a # in the query string

== Deutsch / German ==

steht noch hier: (https://www.fpunktk.de/project-anchor2post.html)
