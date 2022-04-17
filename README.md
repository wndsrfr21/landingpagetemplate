# Landing Page Template

This template is meant to be a landing page starter kit. Only use this if the following fits your needs:
- Github stores the raw website files
- Google Firebase is the web server
- CircleCI automatically pushes Github changes to Firebase
- Cloudflare routes the domain
- A domain name has been purchased 

# The Steps
1) Clone this repository to your github and make sure that this project is set to private
2) Create FIREBASE Web Server - Create a new Google Firebase project and note the server name
3) Update FIREBASE Config Files - Update .firebaserc with your new firebase server name
4) Update CIRCLECI Config Files - Create a new firebase token with `firebase login:ci` in a terminal window and update the file ".circleci/config.yml"
5) Create FIREBASE Domain Link - Go to firebase. On left nav bar click HOSTING. In new section on the right, click the blue ADD CUSTOM DOMAIN. Follow instructions. Note down the IP address and DNS setup instructions for the next step
6) Create CLOUDFLARE DNS entries - Update Cloudflare DNS routes Create an "A" and point the target address to IP address listed in the previous step. Make sure PROXY IS OFF.
7) Wait painfully for DNS records to propogate

# Email
sendgrid.com

# Firebase Token
If you need to regenrate a firebase token open a command line and type `firebase login:ci`
Here is the reference documentation: https://firebaseopensource.com/projects/firebase/firebase-tools/
