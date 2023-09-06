# MauiTestApp
to track bug for VS MAUI not generate .appinstall file when creating package
https://devdiv.visualstudio.com/DevDiv/_workitems/edit/1871846

Luke Westendorf
Thanks for mentioning that this is a MAUI app.  I see the behavior you mentioned, where the AppInstaller file and Index.html aren’t copied.  I opened a bug for this: Bug 1871846 MAUI Publish with automatic updates enabled doesn't include AppInstaller file or Index.html (visualstudio.com).  We will try to address this in 17.8.
