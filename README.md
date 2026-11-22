# Poker 2.0 dashboard

A static page that reads the group's "Poker 2.0 Tally" Google Sheet and shows standings, lifetime results, player histories, records and every logged game.

- The Sheet is the backend: the page fetches each tab through Google's visualization endpoint, so editing the Sheet updates the site on the next page load.
- The list of periods comes from the column headers on the Sheet's Lifetime tab. When a new period starts, add its tab and a matching column on the Lifetime tab and the dashboard picks it up.
- The Sheet has to be shared as "Anyone with the link can view" for the page to read it.
