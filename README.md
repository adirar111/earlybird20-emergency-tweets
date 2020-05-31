# #EarlyBird20: New Twitter Replies Feature -- Emergency Tweets :bird:  :bangbang: :sos:

During #EarlyBird20, we were tasked to go through the Software Development Cycle and come up with a new feature to implement for Twitter's *Tweet Details* page. Our group decided to implement an emergency tweet feature.

 -   Twitter represents “what’s happening”, therefore it’s essential for this platform to show it’s concerns about current events by raising awareness to emergency causes.
-   Currently, there’s no visual difference between regular tweets and tweets that are “emergencies”.
-   We want to introduce an “emergency tweet” option for emergency tweets. An emergency icon at the top right of the tweet would highlight it as a concerning topic. (This will help catch the users attention).
-   Upon opening an emergency tweet, there will be an option to follow that tweet/thread (via a button) so that users can stay posted on the latest updates. Once following, users would receive notifications regarding that topic of the emergency tweet. (This will help the user engagement with the app)


## To properly run this project

- You should have npm and json-server installed on your computer. Further instructions on how to do this are detailed in: [https://github.com/typicode/json-server](https://github.com/typicode/json-server). 
- After having both of them installed, go to the directory where the project is located via Terminal/ Command Line and run 
>$ json-server db.js
- Visit [http://localhost:3000/falcon-collaborative.html](http://localhost:3000/falcon-collaborative.html) on your web browser, and you should see replies being displayed from replies.json onto the web page.

## What was added?

All your files and folders are presented as a tree in the file explorer. You can switch from one to another by clicking a file in the tree.

- Flashing emergency sign on top right of tweet that displays a description upon hover
- New *Follow Emergency* button.
- New menu icon to find all *Emergency Tweets* being posted in your area.

## Screenshots

### Hovering over the emergency symbol

<img src="screenshots/img_1" width = 200>

### Hovering over the follow emergency button

<img src="screenshots/img_2" width = 200>

### Clicking on follow emergency

<img src="screenshots/img_3" width = 200>
