# android-codespace

WIPoC &mdash; An adventure in irritation, frustration, and (geriatric) persistence

Set up a codespace for Android development with VSCode + Java/Kotlin (the default interface _is_ vscode, it made sense to leverage what was there ... oops ...).  No problem, right?  IDE is popular.  Languages are popular.  Codespaces are popular.

After trying more github templates than necessary, each one promising a "basic, fully installed android SDK development environment" ... I gave up.  I have no idea if the following statement is true, but it _seems_ like there are more and more cases of "it works on _my_ machine" happening than I remember in the opensource world.

Are we *really* getting ***that*** sloppy?

Anyway, this is a learning experiment in creating a working, full-featured codespace development container for android development that *isn't* build on Flutter (because I want to be able to create things like live wallpapers, and Flutter/Dart can't do those, from everything I've encountered so far), containing:

- VSCode extensions for Kotlin, Java, Android, etc.
- The latest (TODO:  configurable) Android SDK, installed and set up for global (container) access.
- Any other `apt-get` packages deemed necessary
- Convenient ADB/debugging support of android app

