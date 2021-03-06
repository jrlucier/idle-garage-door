# Overview
Idle Garage Door SmartApp is a SmartApp for the SmartThings platform that will close your garage door(s) after a set period of inactivity.  Inactivity is determined by motion sensors in your garage.

## Installation Instructions:

### Manually:
1. Log in to the <a href="https://graph.api.smartthings.com/">SmartThings IDE</a>. If you don't have a login yet, create one.
2. Load contents of <a href="https://github.com/jrlucier/idle-garage-door/blob/master/smartapps/jrlucier/idle-garage-door.src/idle-garage-door.groovy">Idle Garage Door</a> in SmartApps section. From IDE, navigate to <a href="https://graph.api.smartthings.com/ide/app/create#from-code">My SmartApps > + New SmartApp > From Code</a>. Click Save. Click Publish > "For Me"
3. In your mobile app, tap the "+", go to "My Apps" and select Idle Garage Door. Then just choose your motion sensors, garage doors, and timeout.  Congrats, it should work now!

### SmartThings IDE GitHub Integration:

If you have not set up the GitHub integration yet or do not know about it, take a look at the SmartThings documentation [here](http://docs.smartthings.com/en/latest/tools-and-ide/github-integration.html). Note that if you do not have a GitHub account or are not familiar with GitHub, the manual method of installation is recommended.

1. Add a new repository with user `jrlucier`, repository `idle-garage-door`, and branch `master`. This can be done in the "My SmartApps" and clicking "Settings"
2. Go to "My SmartApps". Click "Update from Repo". Select the "idle-garage-door" repository. You should see the SmartApp in the "New (only in GitHub)" section. Check both boxes next to them. Check the "Publish" checkbox in the bottom right hand corner. Click "Execute Update".
3. In your mobile app, tap the "+", go to "My Apps", furnish your log in details and pick your gateway brand, and a list of devices will be available for you to pick.

In the future, should you wish to update, simply repeat step 3. The only difference is you will see the SmartApp show up in the "Obsolete (updated in GitHub)" column instead.
