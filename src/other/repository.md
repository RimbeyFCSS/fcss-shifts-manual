# Repository
This is the "code" for the website, ie. what tells the Hosting component how to build the site and what to display when it's built.

This code is hosted on [Github](https://github.com/), and is retrieved by the Hosting component whenever it needs to rebuild the site.

## Frameworks

It uses something called [GatsbyJS](https://www.gatsbyjs.org/) as the *static site generator*, which defines how the program is structured as well as what it does. The the link above for more information.

## Data

[GraphQL](https://graphql.org/) is used to pull information from the database when it is built. This works by connecting the code to the database using a *key*, and then accessing the Base and appropriate Tables and Views based on their names. More info can be found [here](https://airtable.com/api).

Thus, if a View or Table's name on the database is changed, the data will likely be inaccessible!

## Visuals
The visuals are done using [TailwindCSS](https://tailwindcss.com/), which is a beautiful framework for building visuals for a web app. For example, you can see some of the colors used in the web app [here](https://tailwindcss.com/docs/background-color/#app).