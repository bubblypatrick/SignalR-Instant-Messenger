# SignalR-Instant-Messenger

This is an instant messenger using Microsofts Signal-R library in .NET Framework using an MVC style application.

The ChatHub is a server side class that contains the functions called on by the users, which in-turn calls a javascript function located are located on the clients html. The View is the cshtml page that users see. The table/class utilized Entity Framework to map it to a database. All stored chat messages are queried using Linq.

Because SignalR can call functions on all connected users updates happen in real time to all registered listeners.
