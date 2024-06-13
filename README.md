# Online_voting-frontend

The repository stores the frontend of an online voting application.

The html is hosted inside github pages: [Online voting](https://florian98n.github.io/Online_voting-frontend/)

Programming languages used: HTML, JavaScript, CSS.

The communication shall be realized using Websockets(untested).

Steps:
1. when the page is loaded after the creation of the objects the frontend will create a websocket connection with backend
2. the frontend sends an message requesting an captcha image and shows the image in tha page
3. the user inputs the information and the frontend will send the data only after it's own validation
4. the backend shall test tnhe captcha text for the current session, test the database for ID and send back the verdict
5. the frontend will display the verdict received from the backend 