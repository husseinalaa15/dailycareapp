DAILY CARE - installable app
=============================

What is in this folder
  index.html            the app
  manifest.webmanifest  name, colours and icons for "install"
  sw.js                 makes it work offline
  icons/                the sun-and-drop icon in every size
  fonts/                Barlow fonts, bundled so it looks right offline

Step 1: put it online (once, free, about 5 minutes). iPhone needs a real https link.

  Option A: Netlify Drop (fastest)
    1. Unzip this folder on your computer.
    2. Go to app.netlify.com/drop and drag the unzipped folder onto the page.
    3. Sign in with a free account so the site is kept. Copy the link it gives you.

  Option B: GitHub Pages (you already use GitHub)
    1. Create a new public repository, for example "daily-care".
    2. Upload everything in this folder (index.html at the top level, not inside another folder).
    3. Settings > Pages > Deploy from a branch > main / root > Save.
    4. Your link will be https://husseinalaa15.github.io/daily-care/

Step 2: install it on your iPhone
    1. Open the link in Safari.
    2. Tap Share, then "Add to Home Screen", then Add.
    3. Open it from the new Daily Care icon from now on.

Good to know
  - Your ticks, water and settings are saved on the phone, inside the installed app.
    The home-screen app and Safari keep separate data, so enter your weight and
    height inside the home-screen app.
  - Week > Settings > Backup and restore copies all your data as text.
    Paste it into Notes now and then, and paste it back to restore it.
  - If you edit any file later, change VERSION at the top of sw.js (for example to
    'daily-care-v2') so phones pick up the update.
