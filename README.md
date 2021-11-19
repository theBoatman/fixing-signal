These are unofficial 3rd party releases, containing modified code, and are not associated in any way with Signal&trade; Foundation.  

## Important

My patch is now merged, so it is no longer needed to run my modified builds. As there seems to be a bug in the official version of signal around version 4.49.17 that leads to possibly damaged backups,
I provided a build of version 4.50.5, which should have this bug fixed. For migrating back to the official builds I recommend to install my build of 4.50.5 first, then take a backup and proceed
changing to the official version. Good luck everyone!   


## Signal-website-release-4.NN.N-sleepfix.apk
contains [a minimal patch#70](https://github.com/signalapp/libsignal-service-java/pull/70) to allow RealtimeSleepTimer to work in multiple threads 

*  please read [The Big Disclaimer](https://community.signalusers.org/t/call-for-testing-fixing-realtimesleeptimer-to-work-in-concurrent-threads/7189), use at your own risk, no warranty 
*  if you have android 4.4 or above, use the highest-numbered version 
*  if you have android 4.1 thru 4.3, use the release-4.36.2-sleepfix.apk 
*  before installing, please upload a debuglog from your EXISTING signalapp in a new [forum-comment](https://community.signalusers.org/t/call-for-testing-fixing-realtimesleeptimer-to-work-in-concurrent-threads/7189) , you can login with your github credentials or use a protonmail/tutanota/similar webmail to signup for a forum-login 
*  after installing, use the sleepfix APK for a few hours, and then please upload a debuglog from your SLEEPFIX apk by clicking the :fountain_pen: edit button on your existing [forum-comment](https://community.signalusers.org/t/call-for-testing-fixing-realtimesleeptimer-to-work-in-concurrent-threads/7189) 
*  if you only have time to upload one debuglog, that is fine :-)  both is better but one is still helpful 

## Hint

My patch is now included in the inofficial signal builds of johanw666, who builds more frequently than I do. I suggest if you are just testing the patch to use my build, but if you plan to use it for a longer period you should use johanw666s builds because of the more frequent builds he offers.

Get it here: https://github.com/johanw666/Signal-Android/releases

## Signal-website-release-4.35.3-fix8230.apk
contains [Patch 8230](https://github.com/signalapp/signal-android/pull/8230) (signal-android) and [patch 62](https://github.com/signalapp/libsignal-service-java/pull/62) (libsignal-service-java)

## Edit
Cleared out all the old APKs. Left the repository for reference.
