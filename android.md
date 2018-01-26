# Twitter Client with Offline Mode

## Functional Requirements

- [ ] As a user I can login to Twitter;
- [ ] As a user I see my twitter name in the actionbar;
- [ ] As a user I can view my Twitter feed;
- [ ] As a user I can refresh my feed using pull-to-refresh;
- [ ] As a user I can view my Twitter feed without internet connection;
- [ ] As a user I expect that feed will be automatically updated when network connection is available;
- [ ] As a user I can tap on 'compose' FAB and get to post new tweet screen;
- [ ] As a user I can post new tweet;

- [ ] Every data-bound operation should have one of those states at UI: 
  - empty state
  - in progress
  - failed
  - success (data shown)

## Technical Requirements

#### Architectural

- [ ] Kotlin is a huge plus;
- [ ] Clean Architecture / RIB / Flux patterns is mandatory;
- [ ] DI system like Dagger (kodein is a plus);
- [ ] Android Architecture Components or any MVP/MVVM/VIPER solution is Ok;

#### UI-level

- [ ] com.android.support.* packages are mandatory
  - appcompat
  - design
  - recyclerview
  - constraint-layout
- [ ] Fragment-less design is a pluss (plain views are preferred);
- [ ] Ogranized Routing (with or without any framework) is a plus;

#### 3rd-party dependencies

- [ ] RxJava(1/2) is mandatory
- [ ] Any persistence approach is ok (e.g.: Room, Realm, SqlBrite, etc)
- [ ] Logging is not required but is a plus

#### Tests

- [ ] Unit-testing is mandatory (Spek is a huge plus)

## Outcome

- Link to the github repository

## Expectations

- We expect that you will show an ability to build flexible and scalable architecture, however don't do overenginering - think in the following way ("I may be asked to integrate som new twitter features in the future. I may be asked to change design of display feed / post new tweet. I won't be asked to remake this into the instagram");
- Despite Unit Tests are required, we don't expect 100% code coverage. Judging on your opinion cover the most necessary parts of code;
- We don't expect you will spend ages making this test task. Don't spend more than 10–15 hours on this. If you think you are overrunning the time but have already shown the right approach - write a short Readme.md on what is done, what have to be done, how would you do this.
