Idea is to be able to create a community app (non-profit) which is self managed in regards to financial resources due to the fact that it monitors the activity of the users. The users then pay their share depending of the receipt they receive from the app.

You should monitor in a db table the below attributes:`

-Threads that are correlated with the user session
-Database connections with the user session
-Database CRUD operations with the user session
-Time spent communicating with the DB (you can see the overall load that this user brings to the app)
