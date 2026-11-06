# Speak Mastery: web app

A 90-day interactive speaking course you can install on your phone like a normal app. It works offline after the first visit.

Important: the app can only be installed from a web address that starts with https://. Opening `index.html` or the zip directly on your phone shows the course, but it can't be installed that way. First put these files online (free), then install from that address.

## Files (all 8 go online together)

index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, icon-maskable-512.png, apple-touch-icon.png, README.md

## Put it online from your phone (GitHub Pages, free, about 10 minutes)

1. In **My Files**, tap the zip and choose **Extract**.
2. In Chrome, go to github.com and create a free account.
3. Tap **+** then **New repository**. Name it `speak`, keep it **Public**, and tap **Create repository**.
4. On the new repository page, tap **uploading an existing file**. Select all 8 files from the extracted folder and tap **Commit changes**.
5. Open **Settings → Pages**. Under Source choose **Deploy from a branch**, pick branch **main** and folder **/ (root)**, then **Save**.
   If you can't see Settings, open Chrome’s ⋮ menu and turn on **Desktop site**.
6. Wait one or two minutes. Your app is live at `https://YOUR-USERNAME.github.io/speak/`

## Or from a computer (2 minutes)

Unzip, then drag the folder onto https://app.netlify.com/drop and claim the site with a free account.

## Install on Android (Samsung Galaxy)

Open your https address directly in **Samsung Internet** or **Chrome** (not inside WhatsApp or Gmail).

- Samsung Internet: tap the **Install** icon in the address bar, or **☰ → Add page to → Apps screen / Home screen**.
- Chrome: **⋮ → Install app**, or use the Install button in the app’s Me tab.

## Bring your progress across

In the claude.ai version: **More → Me → Copy backup text**. In the installed app: paste it into **Restore from pasted text**.

## Good to know

- The AI coach, sparring and roleplays run only in the claude.ai version. Everything else works in the app, including offline.
- Progress is stored on your phone. Use **Download backup** in the Me tab now and then.
- To update the app later, upload a new `index.html` and change `speak-mastery-v2` at the top of `sw.js` to a new name.
