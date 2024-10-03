# Carbon

Actual repo, [here](https://github.com/GriffinWJones/Carbon). It's set up this way because our workflow benefitted from primarily sharing files over managing git branches. As such, I otherwise wouldn't be listed as a contributor on the actual repo. Here's how the app works: Carbon is a social-media-like app that promotes eco-friendly travel by rewarding the users. You can add friends, track your bike rides and walks, and request and accept carpools from your nearby friends. When opting for a greener way to travel (bike or walk), our app tracks how far you traveled through the use of the INRIX routing API. Then, you'll be awarded a Carbon-Coin for each kilogram of CO₂ you save by not driving. Alongside this, each time you use an alternative transportation method, it will be posted onto your friends’ and your activity feed. I specifically worked on frontend screens such as the carpool bulletin where friends request and accept carpools from each other and the leaderboard where people can see who's been the most eco-friendly by comparing Carbon-Coins with each other locally and globally. The devpost for the project can be found [here](https://devpost.com/software/carbon-6785gb).

## Screenshots

<img src="./screenshots/simulator_screenshot_3.png" width="129" /> <img src="./screenshots/simulator_screenshot_4.png" width="129" /> <img src="./screenshots/simulator_screenshot_6.png" width="129" /> <img src="./screenshots/simulator_screenshot_7.png" width="129" /> <img src="./screenshots/simulator_screenshot_5.png" width="129" /> <img src="./screenshots/simulator_screenshot_9.png" width="129" />

## Inspiration
We wanted to create an innovative product that has the capability of amassing huge amounts of attention, as well as contributing towards a better environment and implementing INRIX API. We were inspired by Strava's system of an activity feed that displays activity posts from your friends, as well as yourself.

## Learnings
We learned how to work in a team using GitHub and many of us learned how to use Flutter for the first time. We also gained a better understanding of how to connect frontend and backend aspects.

## Challenges
We had issues with git merge conflicts and our original database SQLite. It took many hours for us to finally start a system that worked because of these problems. We also had trouble integrating the front end to the back end.

## Technologies Used
- **Flutter** - Frontend
  - Flutter was used for front-end development, utilizing its large widget library for a functional and refined application interface
- **Supabase** - Database
  - Managed authentication, database, and storage
  - Initially used SQLite, then switched to Supabase for its cloud database capabilities
- **INRIX API** - Routing
  - Used to display distance from carpool requests and track alternative travel methods
- **Google Maps API** - Mapping
  - For displaying maps within the application
