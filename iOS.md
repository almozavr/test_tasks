#Twitter client with offline mode.

- As a user I can login to Twitter
- As a user I see my twitter name in the navigation bar
- As a user I can view my Twitter feed (fail plan: display error)
- As a user I can refresh my feed using pull-to-refresh (fail plan: display error)
- As a user I can view my Twitter feed without internet connection
- As a user I expect that feed will be automatically updated when network connection is available
- As a user I can tap on system compose button on the right of navigation bar and get to post new tweet screen
- As a user I can post new tweet (fail plan: display error)

#Technical requirements

- Feel free to use Accounts and Social frameworks - no explicit need to integrate twitter SDK
- iOS deployment target - 8.0+
- CocoaPods used as dependency manager
- App is built using MVVM approach, view is bound to view-model using [RAC v2.5](https://github.com/ReactiveCocoa/ReactiveCocoa/releases/tag/v2.5)
- Unit tests required, use [Kiwi](https://github.com/kiwi-bdd/Kiwi)
- CoreData used as a backing storage

#Outcome

- Link to the github repository

#Expectations

- We expect that you will show an ability to build flexible and scalable architecture, however don't do overenginering - think in the following way ("I may be asked to integrate som new twitter features in future. I may be asked to change design of display feed / post new tweet. I won't be asked to remake this into the instagram")
- Despite Unit Tests are required, we don't expect 100% code coverage. Judging on your opinion cover the most necessary parts of code
- We don't expect you will spend ages making this test task. Don't spend more than 8-10 hours on this. If you think you are overrunning the time but have already shown the right approach - write a short Readme.md on what is done, what have to be done, how would you do this.
