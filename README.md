# SignalR-Instant-Messenger

This is the base code for the instant messenger created for Prosper I.T. Solutions. The company required that messages be stored in a database with a username, unique ID, datetime, and limited message length.

The ChatHub is a server side class that contains the functions called on by the users, which in-turn calls a javascript function located on all client connections. The View is the cshtml page that users see. The table/class utilized Entity Framework to map it to a database. All stored chat messages are queried using Linq.
