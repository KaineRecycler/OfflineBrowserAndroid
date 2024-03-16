# Offline Website Browser

This is a simple offline website browser that lets you browse a website
offline without Internet connection to the wifi

## Use

1. easy to use app first download a website either from the web or web archive.

2. compress the full website into a full zip file and name your offline website that is in a zip file.

3. transfer the full zipped website to Google drive app from your device or ipad.

4. open your website with the offline browser app and allow share access from Google drive app.

5. browse and interact with your offline website without Internet connection to the WiFi.



Note: if you use termux + curl to download files, you will have to set the
`allow-external-apps` property must be set to `true` in `~/.termux/termux.properties` in termux.

## Deep Links

Deep links to link into the app. Because the app is intentionally not communicating with servers or other apps, deep links do not work inside the app, so you can only link in from another app.

Debug builds of the app use a different deep link hostname (add .debug to the end of the hostname)

- [Delete a file](app://foss.zip.offline.browser.offlinezipbrowser/action/delete-file)
- [Rename a file](app://foss.zip.offline.browser.offlinezipbrowser/action/rename-file)
- Deep link to play a game app://foss.zip.offline.browser.offlinezipbrowser/play/Your_game_here.html

### `RENAME_FILE`

rename a file

### `DELETE_FILE`

delete a file

