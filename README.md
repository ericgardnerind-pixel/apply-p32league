# apply.p32league.com

Program intake page for the 2027 P32 / E32 / Jr. P32 circuits.
Submissions go to Google Apps Script, which writes them to the Google Sheet and emails the assigned rep.

## Files
- `index.html` — the whole page (logos are embedded). The only setting is `ENDPOINT` at the top of the script.
- `vercel.json` — basic Vercel settings.

## Changing the schedule
In `index.html`, find `const EVENTS = [` (dates, locations) and `const LEAGUES = {` (required events, number of regionals, excluded stops).
Commit the change and Vercel redeploys automatically.
