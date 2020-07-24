# Quick Start

The guide to getting set up on the website side can be found [here](https://rimbeyfcss.github.io/presentations/rfcss-shifts.html#/).

The rest of the manual will be for administration.

## Map of RFCSS Shifts
![Map of RFCSS Shifts](static/service_map.jpeg)
This is a map of all the components that make up RFCSS Shifts. The most important ones to take note of are the web app, the database, and the automation. The rest are taken care of by the software engineer(s). We will quickly go over these components in the quick start.

The general idea of the web app, database, and automation is as follows: 

- The database is the "meat" of RFCSS Shifts which holds all of the info
- The web app is a "camera lens" that looks at the info and presents it in a convenient way
- The automation contains all of the "actions" that does things like tell the web app to build itself when there is new info in the database, or email someone when there is a new shift.

## Web App
The web app is the visual, the website that let's you see what the database holds. Without it we would have to use the database to try and make sense of who has what shift, which would *not* be convenient!

You can find more information on the website in the [Web App Component section](web_app/index.md), and can see the website itself at [shifts.rimbeyfcss.com](https://shifts.rimbeyfcss.com/).

## Database (Airtable)
The database holds the information for the website, and without it the website would not work!

You can access the database by clicking [here](https://airtable.com/tblMMlV4LPKSQ6gWt/viwvpNOsMnnqNYsKA?blocks=hide) or by searching in your web browser for "Airtable". Log in if it asks you to do so, and then click on "FCSS Scheduling".

Information is organized by tables and views. For more information on *how* Airtable works and how to use the database, there are resources linked in the [Database Component section](/database).

## Automation
Aside from submitting the forms for shift requests, automation takes care of all of the website's "actions". This includes all emails, and re-building the website when there is new information in the database.

You can find the automation service at [automate.io](https://automate.io/app/dashboard).

If you ever need to change how the emailing system works, or want to change when the site rebuilds, you can do so at the link above.

**WARNING**: Be careful when making changes to the automation. These changes do not require expert knowledge, but they do require patience and a clear understanding of what each automation does. If unsure, ask for a second opinion or help from someone else in the office.
