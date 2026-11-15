# nicolelivingston.com

Nicole Livingston's personal site. Jekyll on GitHub Pages, served at https://nicolelivingston.com.

## Where things live

- `index.html`: the homepage content (intro, What I'm up to card, How I work).
- `_layouts/default.html`: the page shell (fonts, link preview tags, favicon, tile background).
- `assets/css/site.css`: all styles.
- `assets/img/`: photos (location data stripped), the favicon set, and `og-image.png`, the link preview picture.
- `_posts/`: notes go here later as `YYYY-MM-DD-title.md`. The RSS feed (`/feed.xml`) builds itself.

## Visitor stats

GoatCounter counts visits with no cookies and no personal data, so the site needs no cookie banner. The scripts are at the bottom of `_layouts/default.html` and the site code is `goatcounter` in `_config.yml`. Stats: https://nicolelivingston.goatcounter.com.

- **Where people come from:** the Referrers list on the dashboard.
- **Where people go:** every link that leaves the site is counted automatically, including links in future notes. Clicks show up as events named `out-` plus the address (for example `out-linkedin.com/in/nicolelivingston/`), and the event's referrer is the page the link was clicked on.
- **Your own visits:** open https://nicolelivingston.com/#toggle-goatcounter once on each browser you use, so they don't count.

## Updating What I'm up to

Edit the rows in the card table in `index.html`, and change the season in the header row (for example WINTER 2026).

## Rules

- Every change goes through a pull request on a side branch.
- No email address, employer, city, or photos of Nicole. Strip location data from every photo.
- The design system lives at https://claude.ai/artifact/L7BpHfKcdCa6LMNNa1CEG7.
