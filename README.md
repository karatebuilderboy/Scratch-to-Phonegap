# Scratch to Phonegap

> ⚠️ **Warning:** This repository is no longer maintained and depends on Adobe PhoneGap, which has been shut down since August 2020, and Phosphorus, which does not work for projects made in Scratch 3.0.
>
> If you're still interested in trying to package Scratch projects to mobile apps, consider exploring [TurboWarp Packager](https://packager.turbowarp.org/) as a modern Phosphorus alternative and [Apache Cordova](https://cordova.apache.org/), the underlying framework of PhoneGap.

This is a PhoneGap project which uses Phosphorus to embed Scratch projects in mobile apps. See the tutorial here: [https://scratch.mit.edu/projects/116055504/](https://scratch.mit.edu/projects/116055504/)

This method uses Phosphorus, a JavaScript alternative to the Scratch 2.0 Flash player, and PhoneGap, a web to mobile app packager. Following this setup, you will only need to push updates to the Scratch project, which the app loads from the web at runtime. The app will always play the current version of the project found on Scratch.

For reference if you follow any other PhoneGap tutorials to further customize your app, this repository contains the entirety of Phosphorus source code (which is set to run your Scratch project) and the PhoneGap config.xml. If a tutorial says to add or edit any files, feel free to do so.

Good luck!  :)
