# Software Design README 
Final Reflection: Software Design for The Gaming Room

The Gaming Room is a company that originally created a game called Draw It or Lose It for Android devices. They approached us because they wanted to expand their game into a web-based, cross-platform version that would support many users at once across different operating systems like Windows, Mac, Linux, and mobile devices. Their software requirements included creating a scalable, distributed system that could handle multiple game instances at the same time, ensure unique names for games, teams, and players, and prioritize speed, storage, and security.

One thing I feel I did particularly well was organizing the documentation clearly and explaining technical choices (like using Linux servers, cloud storage, and serverless architecture) in a way that both technical and non-technical audiences could understand. Also, creating the UML diagrams and walking through the Singleton and Iterator patterns really helped clarify how the application would be built.

Working through the software design document before coding was very helpful because it forced me to think through the structure and logic of the application first. Having a clear domain model and understanding storage, memory, and scalability needs made coding the classes like GameService and Entity much easier because the groundwork was already mapped out.

If I could revise one part of my work, I would spend more time breaking down potential scalability issues earlier, like how the game might behave under very heavy load. I would improve this by adding more research into load balancing and auto-scaling cloud services right from the initial planning stages.

When interpreting the user's needs, I kept coming back to usability, scalability, and security. It was important to constantly ask, "How will the players experience this?" and "How can this system grow if more users join?" Considering user needs is critical because a product that doesn't work well for its audience—or doesn't grow with them—will eventually fail, no matter how good the initial code is.

In designing the software, I approached it step-by-step: understand the user's requirements, map out the system structure, choose the best technologies, and then code based on that blueprint. In the future, I would continue to use techniques like creating UML diagrams early, planning scalability strategies ahead of time, and choosing design patterns (like Singleton and Iterator) that match the software's needs.

