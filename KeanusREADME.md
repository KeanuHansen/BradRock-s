This project was to have the user learn about the stock market by selling and buying and holding a chosen stock over a period of time.

Below are a few screenshots of the code:

![image](https://user-images.githubusercontent.com/44275960/185009948-0182cc52-a67f-40d9-9625-978001666845.png)

![image](https://user-images.githubusercontent.com/44275960/185009980-48e64874-eea4-4519-919a-df033510e9f0.png)

The technology that we used was a SQL database connected to ASP.net MVC core with Razor pages. We ran into technical difficulties with the frequency of queries, and the database. It was crashing frequently. So we had to put some timers to keep the queries from running too quickly before the database could handle it again, while not making it take too long to load. We also had to figure out how to strategically open and close connections.

I worked on the functionality that made it connect various functions to the database, so it could call the database, pull data, and send it to the front end code. Such as looking for a date or stock price on a certain date, or updating a value during a hold.

Snippets of code I worked on are posted below:

![image](https://user-images.githubusercontent.com/44275960/185010493-b3ab9a2b-9722-46ec-b85a-8b4b06aaa004.png)

![image](https://user-images.githubusercontent.com/44275960/185010541-e2a13a6a-49dc-423a-8372-78d6040ddb25.png)

Download Code: [Download Code](https://github.com/KeanuHansen/BradRock-s/)
