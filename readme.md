# Angular 8+ & Cordova with ios, browser, and Electron platforms

This boiler plate provides Angular and Cordova integration out of the gate. Angular workspace has no Apps/Modules and is setup to run build to Cordova workspace.
This boiler plate was built using: https://medium.com/@nacojohn/convert-your-angular-project-to-mobile-app-using-cordova-f0384a7711a6 as a loose guide...
When I say loose I mean I didn't actually read this, but skimmed it for fact checking... key points are the the device ready hook and final steps of setup

You will need to run: ng g application MyApp
And, you will need to set the build output path to the www folder in order to have cordova hook the final output.
