# Hosting mod files
## Files that you need
### Mod files
As long as the original server is running, all you would need to host are the files you've already edited. Put them in this repository **EXACTLY** like this example, as if you're in the `files` directory of your device.
### `live.txt`
A "live" file is one that is enforced by the server, e.g. say you want to make sure that all users have the same game rule files. These files will be redownloaded every time the game is loaded, so keep the list of files short, and keep those files small (compress them again before sending them over!). `live.txt` stores the path to these files **WITHOUT** the version number.
### `.nojekyll`
You're just storing static files, there's really no need to build anything. Feel free to throw this away if you want to get fancy.
## Setting up the GitHub page
Reference the official documentation [HERE](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-from-a-branch).