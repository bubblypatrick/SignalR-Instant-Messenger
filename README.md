# SignalR-Instant-Messenger

This is an instant messenger I created for Prosper I.T. Solutions. The company required that messages be stored in a database with a username, unique ID, datetime, and limited message length. It involved using Microsofts SignalR's code library, a set that begins with an HTTP request and upgrades to websockets if available for constant connection. This messenger uses html, bootstrap, javascript and C#, and ties together many concepts taught at The Tech Academy.

The ChatHub is a server side class that contains the functions called on by the users, which in-turn calls a javascript function located are located on the clients html. The View is the cshtml page that users see. The table/class utilized Entity Framework to map it to a database. All stored chat messages are queried using Linq.

Because SignalR can call functions on all connected users computers, this technology could be used in much more advanced ways that could help alert all people in an office with any messages that happen on a server or client, and would keep everyone on the same page for troubleshooting purposes.
