# Restaurant Recommender

For part of my coursework during the third & final year for my degree (2017), I with a group of two others were tasked to design and develop a recommender system.

We decided to create a restaurant recommender web app for those having trouble choosing a restaurant to eat at using user preferences.

Users can use inputs to choose their preferences and then submit to receive recommendation based on their preferences.

**The inputs:**

*   Postcode

*   Food Category (Mexican, French etc.)

*   What day to eat.

*   What time to eat.

*   What distance willing to travel

The system will then output the top 5 restaurants for user's preferences ranked on the rating on Yelp.

We decided to use these filters because these we believe are the most important factors when choosing a place to eat, and as there isn't a system which takes in all this information when recommending.

We used the Yelp API to get restaurants of user tastes around the user within the distance inputted.

We used Google Maps API to get the opening & closing times of the restaurants and use it to only recommend restaurants open on time and day specified.

We decided to use the Bootstrap Framework to give users a better experience.

Built using HTML5, Bootstrap, Google Maps API & Node.js with packages Express, Yelp for the Yelp Search API.
