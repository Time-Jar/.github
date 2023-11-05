# Time jar

## Overview 

With the emergence of pervasive computing devices as well as social networks such as Facebook, Instagram, TikTok, YouTube and so on, it has become increasingly difficult to maintain focus and productivity throughout the day. The constant distractions offered by these mobile devices and platforms, which are designed to capture our attention, have a significant impact on our ability to stay focused on our tasks and get our work done effectively. As a result, many people face challenges to their ability to manage their time optimally and therefore, it has significant repercussions on their overall well-being. 

While existing solutions such as screen time management applications provide statistics, they are unable to detect when applications should be blocked. This has many shortcomings: 

* Inability to differentiate between different purposes on the same app (for example work, school, and free time usage), 
* Inability to take the location and time into account: it is not distracting listening to music on a bus, 
* Inability to understand the users schedule and tasks: usage should be dependent based on its obligations (liabilities such as visiting parents, preparing for exam), 
* Unable to remind us of the work we should be doing. 

Blocking should be time, location and context agnostic. Non-productive time on apps should be minimized or potentially even eliminated. Watching TikTok should be time limited or available when you can’t do productive tasks (like on a bus). Watching YouTube should be limited for non-productive work, while productive wouldn’t be. Being at dinner with friends would block all non-necessary apps to prevent distractions. 

## Motivations and challenges 

This project aims to improve people’s productivity and well-being. This will be measured using a survey. Namely, understanding the user, its habits, schedule, and work, while coordinating it with history, current events, and lifestyle is proven to be difficult, as there is currently no app like it on the market. Our goal is not to block apps, but namely to enable users to adapt better usage habits by being more aware of their actions as well as reminding them of what is important. 

## Solution 

Our proposed solution is to develop an Android app, with Jarvis like features: 

* App asks questions after user closes app, regarding usage for better understanding of users' behavior and recognizing which apps and at what time they are used for productive and non-productive work. 
* Accelerometer and location tracking: for sensing users' movement by foot, car or being still. 
* App usage and context tracking. 
* Calander and TODO list reading (we expect to do this within the app, as we are highly unlikely to be able to get users that use the same calendar and TODO list apps); we would be gathering task priority, preparation time needed before the task and task title as well as description. 
* A machine learning model that continuously learns from user behavior. It mainly learns from users' feedback to questions and monitored behavior. There is no training data available with our specific use case, so we will need to gather it. 
