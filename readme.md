---
title: Building a JobScheduler
duration: "1:30"
creator:
    name: Alan Caceres
    city: NYC
---
# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Build a JobScheduler to update some data in our apps

<a name="introduction"></a>
## Introduction

> Note: This should be done independently

We've gone over implementing the different components a JobScheduler needs to perform background tasks
under certain requirements. There are other requirements that we could have given our JobScheduler to run tasks under more strict guidelines. A major feature of JobScheduler that we can take advantage of in our apps is batching various jobs together to run under our requirements. Effectively, saving the user's battery life / data usage.

In this lab, you will create multiple JobServices to update various pieces of info in your app.

<a name="exercise"></a>
## Exercise
***

### Minimum Requirements

- Create at least 2 jobs that update two different pieces of information under the same constraints

- Create a third job that updates a third piece of information under a different constraint.

- Display both the data prior to the job running and the data that is replacing it after the job runs. If the job has not run yet, show nothing for the replacement data.

### Bonus
- Update an ImageView with an acceptable random image from the Internet, under different job constraints
- Use the CalendarContract content provider to update another view with an event that is created. (Provide the title of the event)

***

<a name="deliverable"></a>
## Deliverable

You will need to create a new Android project for this lab.

A working application that meets the requirements above.
***

### ADDITIONAL RESOURCES
- [Background Optimization with JobScheduler](https://developer.android.com/preview/features/background-optimization.html)
- [CalendarProvider](https://developer.android.com/guide/topics/providers/calendar-provider.html)
- [Glide Image Loader](https://github.com/bumptech/glide)
