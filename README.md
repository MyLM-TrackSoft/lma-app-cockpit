# Salesforce LMA App Cockpit 
<a href="https://githubsfdeploy.herokuapp.com">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">

## TL;DR - Show me a demo!

[![](http://img.youtube.com/vi/GTy0Lr19z34/0.jpg)](http://www.youtube.com/watch?v=GTy0Lr19z34 "")

## What is the App Cockpit?

The App Cockpit is a native Salesforce App that extends the Salesforce LMA and helps you monitor the health of your apps and proactively support your subscribers in error cases.

Managed Packages have an option to send out app errors to an email address defined during Package upload. We use this mechanism and let our App receive and parse those emails. In combination with the information in the LMA app, we can perfectly assign each incoming error to a customer account, a package, package version, and license. But we can do more. We also extract information about the type of error and where it occurred.

All this information is stored in a single Custom Object and can be easily used for reporting and sophisticated support workflows.

## How can I use and extends this?

The project was built as a flexible unnamespaced SFDX project. The repo contains all the scripts to automatically build dev scratch orgs with the LMA installed and sample data to play with.

From there you can either build Unlocked Packages from it or even push it into a Packaging org using the deployMetadata.sh script.

Feel free to fork the repo and extend it. We would love to get improvements as Pull Request from you. Or create issues when you find a problem but don't want to fix it on your own.
