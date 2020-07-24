# Web App Component

The web app component is the website that displays the information in the database. Specifically, it is built using something called a "static site generator", meaning the site does not update in real-time and instead is rebuilt from scratch every time it is told to do so. 

This leads to significant cost reductions since other than the times it is build it uses no resources and is simply a collection of "dumb" documents!

You may find the web app [here](https://shifts.rimbeyfcss.com/).

## Benefits and limitations of the web app's design

The pros of a static site are:

- Faster to browse, doesn't feel "slow" or unresponsive.
- Very cheap to run, as the site doesn't actually do anything 99% of the time
- Simpler in design, as you don't need to worry about scenarios where many people are accessing the site at once, or preventing overload.

The cons of a static site are:

- Limited in functionality, particularly "real-time" events. For example, messaging services.
- Rebuilds can take a few minutes, meaning that if the site is told to rebuild itself to display information, it will still take a few minutes to rebuild itself first. Again, this makes it not ideal for "real-time" scenarios.
