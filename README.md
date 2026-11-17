# MonoHomePage
A customisable browser start-page in a single HTML file: no install, account, or server needed. Resizable cards for bookmarks, search, world clocks, rain chart, weather &amp; forecast, countdown timers &amp; alarms, stopwatches (incl. create chess-style “relay” timers), counters, formatted notes &amp; a Kanban board (based on Nullboard).

## A warning on losing & saving data 
Everything added or changed within MonoHomePage is only saved in your web browser's page storage (e.g. localStorage). Clearing browsing data WILL delete your data. Using a private window will cause all data to be lost when you close it. Opening the page from a different folder, browser or profile will open a different instance. Back up regularly & don't use MonoHomePage for anything important or private.

If you save MonoHomePage locally, don't move or rename the folder after you start using it because the browser links your data with the page's address, so a moved page starts empty (your data should still be accessible via the old folder name and/or address at least).

## Data privacy
The page only contacts:
- Open-Meteo: weather and place search
- Buienradar: rain chart
- ipwho.is / geojs.io: automatic location from your internet address, if you use it
- Each bookmarked site for its icon. The background image's website. The search engine you search with. A Googlefont link if added.

## Credits and third-party licences
- Nullboard by Alexander Pankratov (swapped.ch) -> 2-clause BSD licence with the Commons Clause condition, see the [Nullboard licence](https://github.com/apankrat/nullboard/blob/master/LICENSE)
- Fonts in nullboard/extras/: Montserrat, Nunito Sans, Open Sans, Barlow, IBM Plex Sans, Maven Pro -> SIL Open Font License 1.1
- jQuery 3.6.0 (used by Nullboard) -> MIT licence
- Colour filter code from Stack Overflow -> CC BY-SA 4.0
- Weather data by Open-Meteo -> CC BY 4.0; rain forecast by Buienradar.

## Licence
MIT licence (MonoHomePage's own code).
