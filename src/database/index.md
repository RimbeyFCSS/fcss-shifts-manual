# Database Component

The Database component currently uses [Airtable](https://airtable.com/) to store the data for the site. This makes the site far cheaper to host, and disconnects the data and visual components for better reliability and upgradeability.

To learn more about Airtable, please look at their [Support Section](https://support.airtable.com/hc/en-us) for up-to-date information. This manual will try to cover the necessities, but the guides here may eventually become outdated.

The Database contains 5 tables:

1. **Schedule**: The default schedule for HCA staff.
2. **Requests**: Requests for shift changes.
3. **Values**: Stored values for other tables to reference. If you wish to adjust the payroll start period, you may do so here.
4. **Feedback**: Feedback sent through the site.
5. **AllowList**: Emails whose accounts are allowed onto the site.