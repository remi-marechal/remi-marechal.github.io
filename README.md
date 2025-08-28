# Under (heavy) construction...

## Note to self

In order to test changes locally, modify and save necessary files, then run `bundle exec jekyll serve`. Also comment the `<meta http-equiv="refresh" content="0; URL=https://remi-marechal.github.io/index.html">` line in the `default.html` layout (otherwise I'll be redirected to the live page instead of looking at the local version of it); don't forget to decomment it after I'm finished.

After that, look for a line that says `Server address: [some address]`, and view the local changes there.

*Other note: don't bother doing Ctrl+C in git bash when doing successive local changes (simply modify files, save them, and refresh the server address in the web browser).*

When wanting to apply changes to the live website, just make sure every file is saved, then shut down the server with Ctrl+C, and go through the usual add/commit/push process. Finally, deploy the website by going [there](https://github.com/remi-marechal/remi-marechal.github.io/settings/pages), changing the branch from "master" to "None", clicking "Save", then changing "None" back to "master", clicking "Save" once more, waiting for a short moment, and observing actual changes [there](https://remi-marechal.github.io/) :)

## Or, you know, use feature branches :p
