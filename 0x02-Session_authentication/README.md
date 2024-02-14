# AUTHENTICATION

Authentication technology provides access control for systems by checking to see if a user's credentials match the credentials in a database of authorized users or a data authentication server.

# SESSION AUTHENTICATION

This means that a session record must be kept on both the server and the client side. The server will keep track of active user sessions and store them in memory or in a database, and the browser will have the session ID in a cookie.

# COOKIES

A piece of data from a website that is stored within a web browser that the website can retrieve at a later time. Cookies are used to tell the server that users have returned to a particular website.

# SENDING COOKIES

Cookies are created when a new webpage is loaded. The website server sends a Set-Cookie header to the user's browser, which then stores the cookie on the user's device. The next time the user visits the same website, the browser sends the cookie back to the server in a Cookie header.

# PARSING COOKIES

Parse an HTTP Cookie header string and returning an object of all cookie name-value pairs. The str argument is the string representing a Cookie header value and options is an optional object containing additional parsing options.
