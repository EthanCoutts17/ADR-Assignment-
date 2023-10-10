Title: Choosing a backend Language

## context 

Will be developing a mobile app for a retail company. The app's requirements include supporting offline mode, push notifications, payment gateway integration, analytics tracking, image display optimization, and localization. 
 Have already decided to develop the app as a Native application. Now, need to decide on the backend language for the native app.


 ## Decision 

 It was decided that node.js was going to be used for the backend/server side logic.


 ## Rationale

1. Scalability: Node.js is known for its scalability, which is essential for handling potential increases in user traffic as the retail company expands its customer base.
2. Real-Time Capabilities: If future requirements include real-time features like chat or notifications, Node.js's non-blocking architecture makes it usable for implementing those functionlitys.
3. Cross-Platform Compatibility: Node.js is available on various operating systems, ensuring flexibility in hosting and deployment options.
4. Familiarity: Development team has experience with JavaScript and Node.js, making it a easy choice to leverage our existing expertise.

## Consequences

Choosing Node.js as the backend language implies that we will be working with JavaScript on both the frontend and backend. it's important to consider potential challenges related to JavaScript's single-threaded nature,
which may require careful handling of CPU-intensive tasks.

Also, the team should be careful with security as the app wil handle transations and private informations of the customers.

## References 

https://nodejs.org/en/docs

https://www.w3schools.com/nodejs/nodejs_intro.asp


 

 
