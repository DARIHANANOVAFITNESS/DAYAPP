MY DAY - how to put it on your phone
====================================

What's in this folder
- index.html .......... the app itself
- manifest.json ....... its name, colors and icon, so phones treat it like an app
- sw.js ............... lets it open without internet
- icons/ .............. the home-screen icon

1. PUT IT ONLINE (about 5 minutes, free)
   a. Unzip this file so you have a folder called "my-day-app".
   b. Go to https://app.netlify.com/drop and sign up for a free account
      (email or Google). Without an account the site disappears after an hour.
   c. Drag the whole "my-day-app" folder onto the page.
   d. Netlify gives you an address like https://something-random.netlify.app
      Tip: in Site settings you can rename it, e.g. maya-my-day.netlify.app

2. ADD IT TO YOUR HOME SCREEN
   iPhone: open the address in Safari (it must be Safari), tap the Share
           button, then "Add to Home Screen".
   Android: open the address in Chrome, tap the three-dot menu, then
           "Add to Home screen" or "Install app".
   From now on, open it from the icon, not from the browser.

3. MAKE IT YOURS
   - Tap "Clear examples" on the welcome note, or delete items one by one.
   - Tap "you" next to the greeting to type your name.
   - Add your usual routine on the My day screen. It repeats every day.
   - The first time you start a timer, allow notifications if asked.

GOOD TO KNOW
- Your data is saved on your phone only. It isn't sent anywhere, and it
  won't sync to your laptop. Deleting the app or clearing Safari/Chrome
  website data will erase it.
- Each morning the app starts a fresh day: finished tasks, body basics and
  wins clear; unfinished tasks, your routine and your brain dump stay.
- The timer chimes while the app is open. If you switch to another app or
  lock your phone, the alert may be late or silent, because phones pause web
  apps in the background. Proper lock-screen alarms need push notifications,
  which is a good first thing to hire a developer for later.

UPDATING LATER
If you (or I) change the app, open sw.js and change "my-day-v1" to
"my-day-v2", then on Netlify go to your site > Deploys and drag the updated
folder onto it. Your saved data stays.
