# Jenkins Installer for Mac OS X

This project aims to create a Mac OS installer package for setting up Jenkins on a Mac.

Right now it is just a simple MacRuby script, but it has most of the features that the installer will have.

- Jenkins is installed to `/Library/Application Support/Jenkins`
- The JENKINS\_HOME is set to `/Library/Application Support/Jenkins/working\_dir`
- Logs are sent to `/Library/Logs/Jenkins`
- A launchd plist is created and installed for Jenkins

## Contributing to keychain

* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it
* Fork the project
* Start a feature/bugfix branch
* Commit and push until you are happy with your contribution

## Copyright

Copyright (c) 2011 Mark Rada. See LICENSE.txt for further details.