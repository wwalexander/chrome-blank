bnt
=======

An extension for the chromium/Google Chrome browser that turns the new tab page (which is cluttered with logos, bookmarks, etc.) into a blank page.

To install the extension, browse to `chrome://extensions`, check "Developer mode" in the top-right corner, then click "Load unpacked extension...". In the file dialog, select the `src` folder. Check "Allow in incognito" below the extension to replace the new tab page in incognito mode as well. Optionally, uncheck "Developer mode" after the extension is loaded.

The `manifest.json` redirects the new tab page to a blank HTML file called `blank.html`. The `blank.html` string in `manifest.json` can be replaced with a different file.
