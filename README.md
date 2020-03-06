# Goal
Build a (hopefully native) iOS application for testing and promotion.

# Concrete process and Timeline
0. Main functions:
    Currently known functions:
    * Allowing user to take photos and upload to a cloud server
    * Link to a questionnaire (will use typeform)
1. Sketch
Create a mockup of the app layout, UI, and a description of UX. In this step,
    * The UI elements will not be fine grained
    * The UI elements may not be positioned at the exact positions
    * The color schemes and effects would be pretty basic

    Shall be finished by **2020/03/08**. Drafts using papers are welcome. Will use Adobe XD to finalize a sketch.

2. Implement
Based on the sketch and functions, develop a usable app using one of the following services:
    * [creolabs](https://creolabs.com/)
    * ~~[thunkable](https://x.thunkable.com/)~~
    * ~~[appypie](https://www.appypie.com/)~~

    A first verions hopefully before **2020/03/15**

    This service will cost us ~~20~60~~  29 USD per month.

3. Fine design
 
    This step is intertwined with step 2. To be specified later

4. Review

    TBD

5. Release

    A MVP version before the end of March.

This is not a linear process. We will repeate between 2 and 5.


# Explanation
It is possible to classify the ways to develop an app to the following two categories.

1. Develop an app from scratch by deleopers in our team, using open source app development tools and/or official IDEs. We will have full control over the app.
    * Initial fund cost: zero or low
    * Knowledge requirements: high, sharp learning curve
    * Duration: Medium to long
2. Using an app builder. There are many of them.
    * Initial fund cost: medium or high
    * Knowledge requirements: low, quick learning possible
    * Duration: Short

Techniquely, a team need to go through the following steps to build a native app:

1. Idea
2. Selection of platform: Swift/Kotlin
3. Servers
4. Authentication
5. Data Storage
6. User Management
7. Analytics
8. Admin Dashboard
9. Mobile App

By using an app building service, steps 3-8 can be handled by the provider and we will be able to manage it before scaling up.

# Budget

TBD

# Tools used for native iOS app development
Will use XCode 12 beta. Use Swift UI
See [this tutorial](https://developer.apple.com/tutorials) for further reference.

[UI components](https://ionicframework.com/)


# Plans to build an android app

Will develop an android app if the prototype proves to be welcomed by the market.
Develop a hybrid app using [React native](https://reactnative.dev/) or [Flutter](https://flutter.dev/), and publish an android version. Or hire an android developer.


# Reference

On comparing different tools: [Mobile App Development Tools: A Detailed Comparison](https://buildfire.com/mobile-app-development-tools/)

On explaining the workflow: [App development workflow, from the customers’ eyes](https://appus.software/blog/app-development-workflow-from-the-customers-eyes)

On the workflow to unifying UX of multiple platforms [A Simple Design & Development Workflow for Building Better Apps](https://doist.com/blog/design-development-workflow/)