## Archive Layouts for YOOtheme 2.0.1

Update address only. Archive Layouts for YOOtheme now lives in its own repository, [WebG-it/archive-layouts](https://github.com/WebG-it/archive-layouts), and the plugin checks for updates there.

**What you do**: nothing special. Update from *System > Update > Extensions* (the old address announces this version too), or install `plg_system_yooarchive-2.0.1.zip` over the current one with *System > Install > Extensions > Upload Package File*. Your settings are kept.

**What changes**: only the update server address inside the plugin manifest (and the links in the docs and in the message of the update-blocked case, which now points to the Auto Archive repository). Same code, same behaviour as 2.0.0.

**Checked**: update from 2.0.0 on Joomla 5 and 6 in Docker: the update is offered, installs, and the site then lists the new update server; JED Checker `master` and `develop`.

Docs: [docs/yooarchive/USAGE.md](https://github.com/WebG-it/archive-layouts/blob/main/docs/yooarchive/USAGE.md)
