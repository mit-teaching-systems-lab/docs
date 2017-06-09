# Engineering onboarding

#### Use a password manager
- [LastPass](https://lastpass.com/) is one option, but use whatever tool you like.
- Treat account passwords as secrets.  Don't email passwords or share them in Slack.

#### GitHub
- Create GitHub user if you don’t have one
- Set up two-factor auth
- Ask someone to add you to our public GitHub organization (https://github.com/mit-teaching-systems-lab)
- Verify it works

#### Private MIT GitHub
- Create private MIT GitHub user if you don’t have one (http://kb.mit.edu/confluence/display/istcontrib/GitHub.mit.edu+Overview)
- Verify MIT kerberos is working
- Ask someone to invite you to our private MIT GitHub organization
- Verify it works

#### Amazon
- Ask someone to create a user for you in the `Developers` group and securely send you the login page and credentials.
- Set up two-factor auth
- Verify you can use services in AWS console (eg., S3).

#### Heroku
- Ask someone to invite you to the Heroku apps you need

#### Encrypt any research dat
- Install [gpg](https://gnupg.org/download/index.html)
- The receiver should [export their public key as ASCII](https://www.gnupg.org/gph/en/manual/x56.html) and email or Slack it to sender
- Sender [encrypts the message](https://www.gnupg.org/gph/en/manual/x110.html) and sends that along with their public key.
- Receiver decrypts.
