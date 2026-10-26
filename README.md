1. Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The client was The Gaming Room, a company that wanted to expand its existing Android game, *Draw It or Lose It*, into a web-based application that could run on multiple platforms. The game involves teams competing to guess images as they are gradually revealed. The client wanted the application to support multiple games, teams, and players while keeping names and IDs unique. They also needed the application to work across different operating systems, including Windows, Mac, Linux, Android, and iOS. The goal was to create a reliable and scalable application that players could access through a web browser.

2. What did you do particularly well in developing this documentation?

I think I did particularly well at organizing the information and explaining the differences between the operating systems. The evaluation section helped me compare Linux, Windows, Mac, and mobile devices in terms of their advantages, disadvantages, and development requirements. I also think I did well at connecting the recommendations to what the client actually needed instead of just describing each operating system. For example, I recommended Linux because it could support a growing number of players while keeping licensing costs relatively low.

3. What about the process of working through a design document did you find helpful when developing the code?

Working through the design document helped me better understand how the different parts of the application were supposed to work together. The UML diagram was especially helpful because it showed the relationships between the Game, Team, Player, and Entity classes. It made it easier to understand how inheritance could reduce repeated code and how the GameService class could manage the games. Having the structure planned out before coding also made it easier to see where the Singleton and Iterator patterns were needed.

4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one part of my work, I would probably improve the evaluation section. Although I compared the different operating systems and their advantages and disadvantages, I think I could have included more specific examples of how each platform would perform when supporting thousands of players. I would also spend more time researching server costs, scalability, and performance to make the comparisons more detailed. This would help make the final recommendation stronger and give the client more information when deciding which platform to use.

5. How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I interpreted the client's needs by focusing on making the game accessible, organized, and capable of supporting multiple players. Since the client wanted to expand beyond Android, I recommended a web-based approach so users could access the game from different devices without needing separate applications. In the code, I used inheritance to organize shared information between games, teams, and players. I also used the Singleton pattern to manage the GameService instance and Iterators to check for duplicate names. Considering the user's needs is important because even if an application works technically, it may not be useful if it does not meet the requirements of the people using it.

6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached the software design process by first understanding the client's requirements and then breaking the application into smaller parts. The UML diagram helped me visualize the relationships between classes before working on the Java code. I also looked at different operating systems to understand which platform would be the best choice for the application. In the future, I would continue using UML diagrams, object-oriented programming principles, and design patterns to organize my work. I would also spend more time planning and testing different parts of the application before putting everything together. I think having a clear design from the beginning makes development easier and helps prevent problems later.
