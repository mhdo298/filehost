# Hosting mod files
## Using the template
Just click on `Use this template` at the top of the repo, and you're basically done! After this, clone the repo to your desktop, modify files as needed, put them all in `files` (e.g. `files/cards/card_data_xxx`), then push the changes back to github. The files will be hosted at `https://username.github.io/reponame/`.
## Files that you need
### Mod files
As long as the original server is running, all you would need to host are the files you've already edited. Put them in this repository **EXACTLY** like this example, as if you're in the `files` directory of your device.
### `live.txt`
A "live" file is one that is enforced by the server, e.g. say you want to make sure that all users have the same game rule files. These files will be redownloaded every time the game is loaded, so keep the list of files short, and keep those files small (compress them again before sending them over!). `live.txt` stores the path to these files **WITHOUT** the version number.
