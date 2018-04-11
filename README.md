# activityspy

## Requirements 
It should run on IceCreamSandwich.
Package your app as "edu.washington.<yourNetID>.activityspy"
As a user, when I launch the application, it should display “Greetings, UW!"
As a developer, when I launch the application, it should write “on{event-name} event fired” to the INFO level of the diagnostic log for this application. If there is additional data with that event, it should also be written to the log.
As a developer, when I close the application, it should write “We’re going down, Captain!” to the ERROR level of the diagnostic log in response to the onDestroy event.

- [x] All your code should be in a GitHub repo under your account
- [x] Repo should be called 'activityspy'
- [x] Repo should contain all necessary build artifacts
- [x] Include a directory called "screenshots", including 
- [x] Screenshot of app running on emulator
- [x] Text-file contents of diagnostic log ('diagnostic.txt') after a run
