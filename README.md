forked version of [put.io for roku](https://github.com/putdotio/putioroku)
===

please note that this is a **non-maintained version for my own purposes and may not pull from upstream very often**.

for now there's some novel features:

- show if an mp4 is available in episode lists (before accessing the individual video page)
- show if a file has been accessed

this build also has some better exclusion features in building - it should drop the packaged size down by **80%**! woot!

installation
===

this version makes use of the [roku sdk](http://wwwimg.roku.com/static/sdk/RokuSDK.zip) (zip link) and the nice `make install` command it provides. drop this folder into `{sdk}/examples/source/`, then run `make` and `make install`.
