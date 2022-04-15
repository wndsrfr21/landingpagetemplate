# Landing Page Template

This template is meant to be a landing page starter kit. Only use this if the following fits your needs:
- Github stores the raw website files
- Google Firebase is the web server
- CircleCI automatically pushes Github changes to Firebase
- Cloudflare routes the domain

# The Steps
1) Clone this repository
2) Create a Google Firebase project
3) Change the Firebase project name within .firebaserc to your new firebase project name
4) Create a new firebase token with `firebase login:ci` and update the file ".circleci/config.yml"

# Email
sendgrid.com

# Firebase Token
If you need to regenrate a firebase token open a command line and type `firebase login:ci`
Here is the reference documentation: https://firebaseopensource.com/projects/firebase/firebase-tools/
