# Shift Counter

A simple, mobile-friendly tap counter for keeping track of customer interactions during a retail shift. Tap to count engagements, demos, and sales as they happen, then use the totals to fill in your end-of-shift survey.

## Features

- Counters grouped into four sections: Engagements, Demos, In-store sales, and Ship-to-home/store sales
- Large **+** buttons for quick one-handed tapping, plus **−** to correct mistakes
- **Undo** button to reverse your last tap
- Counts are saved in your browser, so closing the page or locking your phone won't lose them
- Reminder to reset when you open the app on a new day
- **Copy summary** button to copy all your numbers at once
- Works in light and dark mode
- No sign-up, no server, no tracking: everything stays on your device

## How to use

1. Open the site on your phone.
2. Tap **+** each time you have an interaction, demo, or sale.
3. At the end of your shift, tap **Copy summary for survey** and use the numbers to fill in your survey.
4. Tap **Reset all to 0** before starting your next shift.

Tip: add the site to your home screen so it opens like an app.
- **iPhone (Safari):** Share → Add to Home Screen
- **Android (Chrome):** ⋮ menu → Add to Home screen

## Deploying with GitHub Pages

1. Upload `index.html` to this repository.
2. Go to **Settings → Pages**.
3. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
4. After a minute or two, the site will be live at:
   `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

## Customizing

All counter labels and survey questions are listed near the top of the `<script>` section in `index.html`, in the `SECTIONS` list. Edit the text there to rename, add, or remove counters.

## Notes

- Counts are stored in your browser's local storage, so use the same phone and browser for each shift.
- Clearing your browser data will erase saved counts.

## License

Free to use and modify.
