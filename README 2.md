# MovieBoxPro Media Station X launcher (experimental)

This is a Media Station X configuration, not a native app or a MovieBoxPro client.
It displays an Open MovieBoxPro button that performs the documented Media Station X `link:` action.
Login, playback, cookie persistence and remote behavior have NOT been verified inside Media Station X.

## Setup using GitHub Pages

1. Create a public GitHub repository named `msx`.
2. Upload `start.json` (ONLY this file is required) to the repository root.
3. In GitHub repository Settings -> Pages, select Deploy from branch -> main -> /(root), and save.
4. Once published, test the URL `https://YOUR_GITHUB_USERNAME.github.io/msx/start.json` in a browser. It must display JSON text.
5. On LG TV, open Media Station X -> Settings -> Start Parameter -> Setup.
6. Enable the HTTPS security lock. Enter `YOUR_GITHUB_USERNAME.github.io` (hostname only, without scheme, slash or path).
7. Finish the start parameter setup; select Open MovieBoxPro on the TV.
8. If a link validation warning blocks the website, change Settings -> Validate Links to No.

If you are signed out in Media Station X, sign in directly in the site opened within that app; web browser sign-in may not carry over.
If you cannot return to Media Station X after opening the external website, use LG Home and reopen Media Station X. This is a documented limitation of external `link:` actions.

References:
https://msx.benzac.de/wiki/index.php?title=Setup_Start_Parameter
https://msx.benzac.de/wiki/index.php?title=Actions
https://msx.benzac.de/wiki/index.php?title=Tips_%26_Tricks#External_HTML5_Games/Apps
https://github.com/benzac-de/msx
