# KeyboardAnywhere
Open android soft keyboard on demand.


# Usage
1. Download and Install the `.apk`
2. Give it accessability permissions.
3. Give it permission to draw over other apps.
4. Disable notifications for this app.
5. Enable the toggle button. (Show as a small green rectangle on the lower right corner of screen)
6. Tap on that rectangle to spawn or dismiss the keyboad.

# How it works
1. Its an `.apk` generated from another app called `Tasker` used for automation purposes.
2. Idea is that, this spawns an invisible `Activity` and then summons the keyboard and then immediately after that kills the activity and keyboard remains.
3. And if the keyboard is already open, it will close it.

# Issues
1. One major major issue is that it seems to be working only on my `Android 11` device, when tested on `Android 14` this does not work.
2. Reason for above seems to be that `Android 14` notices that activity that spawned the keyboard is gone so it dismisses the keyboard as well.
3. Well... apart from that its just an utility app without much of an UI. If it works for you, you probably will never open the main app again so no point working on that.


# Inspiration
Initially I wanted to see if I can spawn the keyboad on any screen and then see if i can somehow give some command shortcuts from it and create shortcuts. However when looking for such functionality, there was no app to be found except `Hacker's Keyboard` which uses a persistant notification to pop up a keyboard. Well, I wanted something that is just a click(touch) away and thus created this `hack` of an app. Believe me its just a hack, and does not work on all Androids, but works on mine which is sufficient for now. Any person who knows android development might create something better.

