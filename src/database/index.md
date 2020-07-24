# Database Component

The Database component currently uses [Airtable](https://airtable.com/) to store the data for the site. This makes the site far cheaper to host, and disconnects the data and visual components for better reliability and upgradeability.

**WARNING**: Do not rename or otherwise remove the fields (ie. the column headers), tables, or views. Otherwise the web app will not know where to look for the information! *Adding* fields, tables, or views is fine.

## How to Use Airtable
To learn more about Airtable, please look at their [Support Section](https://support.airtable.com/hc/en-us) for up-to-date information. This manual will try to cover the necessities, but the guides here may eventually become outdated.

Here are the essentials:
- [Intro video](https://player.vimeo.com/video/360419402?autoplay=1&title=0&byline=0&portrait=0)
- [What are Bases](https://support.airtable.com/hc/en-us/articles/360021518753-Getting-started-starting-with-the-base-ics)
- [What are tables, fields, and records](https://support.airtable.com/hc/en-us/articles/360021333094)
- [What are views](https://support.airtable.com/hc/en-us/articles/360021501754)
- [Collaboration](https://support.airtable.com/hc/en-us/articles/360021502454)

## Tables
The Database contains 5 tables:

1. **Schedule**: The default schedule for HCA staff.
2. **Requests**: Requests for shift changes.
3. **StartTimes**: Start times for each shift.
4. **Values**: Stored values for other tables to reference. If you wish to adjust the payroll start period, you may do so here.
5. **Feedback**: Feedback sent through the site.
6. **AllowList**: Emails whose accounts are allowed onto the site.