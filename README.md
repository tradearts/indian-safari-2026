# Indian safari — November 2026

Mobile-friendly static trip website. No accounts, external libraries, trackers or build step. All illustrations and assets are local.

## Preview

Run `python3 -m http.server 8765 --bind 127.0.0.1` in this directory and open http://127.0.0.1:8765/. Opening the HTML as a file will not load the JSON in most browsers.

## Publish on GitHub Pages

1. Review `trip.json` with Bryce and approve public visibility. Ordinary GitHub Pages sites are publicly accessible, even with a private source repository on eligible plans. `noindex` and robots.txt are not access controls.
2. Upload only this website directory's contents to a dedicated trip repository. Never upload the parent project, local private brief, passport, confirmation screenshots or financial comparisons.
3. In repository Settings → Pages, choose Deploy from a branch, `main`, `/ (root)` and Save.
4. Verify the resulting HTTPS URL, itinerary, mobile layout and update flow before sending the link to the group.

## Update

The shared source is `trip.json`. Edit it in GitHub and commit, or use the site's Update the plan form to prepare a browser-local draft and download replacement JSON. Upload/commit that file to the repository to publish. Local drafts do not sync to other people or overwrite the shared site. Group editors need repository access; no GitHub token is stored in the browser. Prices, private contact details, passport information and booking references must stay outside this website.

The initial page distinguishes confirmed dates/flight bookings from proposed travel and unbooked accommodation. Rail times are timetable references checked 25 October 2026, not a live availability result. Max's response to the final wedding timing question is pending. Preserve these distinctions when updating.
