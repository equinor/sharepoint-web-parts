# sharepoint-web-parts

_POC for custom web parts in Sharepoint_

This repository is about exploring how to solve an issue for a client that needs to visualise ongoing activities in Sharepoint. These activities will be divided into three categories:

1. Upcoming
2. Ongoing
3. Completed
4. On hold

The upcoming and completed categories will be displayed as lists, while ongoing will be displayed as an area with a finite number of slots, where each activity will potentially span more than one slot to visualise the scope of the activity. When an activity is completed it will be moved to completed, and the remaining empty slots will be filled with activities from the upcoming list. The ongoing area can not have more activities than the number of available slots.

We have identified four possible solutions: 

1. Create a React app, host it in Radix, and embed it using an iframe
1. Create a PowerBI report and embed it as a PowerBI web part
1. Create a Power App and embed it as a Power App web part
1. Create a web part in React and deploy it to the app catalog

We’ll with an MVP using a Sharepoint List as a data source, then look into either Power BI or a Power App.

#Power App link:

https://eu.create.powerapps.com/studio/
