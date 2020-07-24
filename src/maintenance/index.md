# Troubleshooting

This section covers some tips for troubleshooting errors that may occur in the site.

The most common sign of an issue are:
- The site refuses to update / load
- A shift is incorrectly displayed

Both of these issues can almost *always* be solved by:
1. Taking a look at the corresponding data in the "Requests" and "Schedule" tables on the database. If any of the requests are in a strange order (for example the taken shift was submitted before the offered shift, or the original offer was not from the original owner of the shift), fix those issues first by either rejecting the appropriate requests or changing their data.
2. Check the spelling of names, etc. If a name has so much as a space or different capitalization it will not be considered the same name! Likewise, if two names are spelt very similarly it might be best to add a last name so that they are not mixed up.
3. Check if any row in any table is empty. If so, delete it. If a cell in the Schedule, StartTimes, or Values is empty, fill it with the appropriate value.

Then wait a few minutes for the site to rebuild, or press the rebuild button on the site if you are an admin.

If you are still having issues, see the remaining pages in this section for more help.