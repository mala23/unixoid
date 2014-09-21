Env vars seem to be the pieces of code (I've use $PATH=foo before) terminal seems to load on start of the app. So probably they are the ones found in ~/.bash_profile and ~/.profile and so on.

The regex needed for step 6 is "/(^\T.*)/gm", run with an m flag, for multiline.
