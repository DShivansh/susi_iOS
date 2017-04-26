# iOS App for Susi

[![Join the chat at https://gitter.im/fossasia/susi_iOS](https://badges.gitter.im/fossasia/susi_iOS.svg)](https://gitter.im/fossasia/susi_iOS?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://travis-ci.org/fossasia/susi_iOS.svg?branch=master)](https://travis-ci.org/fossasia/susi_iOS)

The main feature of the app is to provide a conversational interface to provide intelligent answers using the loklak/AskSusi infrastructure. The app also offers login functionalities to connect to other services and stored personal data. Additionally the application uses data provided by the user's phone to improve Susi answers. Geolocation information for example helps to offer better answers related to questions about "things nearby".

## Roadmap

Make the app functionality and UI/UX similar to the android app for Susi.

## iOS App Development Set up

- Clone / Fork the repo
- Run `pod install` to install the Pods (dependencies)
- Open `Susi.xcworkspace`
- Build and run in the simulator

## Communication

Please join our mailing list to discuss questions regarding the project: https://groups.google.com/forum/#!forum/loklak

Our chat channel is on gitter here: https://gitter.im/fossasia/susi_iOS

## Development

A native iOS app.

## Branch Policy

Note: For the initialization period all commits go directly to the master branch. In the next stages we follow the branch policy as below:

We have the following branches
* **ipa**
All the automatic builds generates, i.e., the ipas go into this branch
* **master**
This contains shipped code. After significant features/bugfixes are accumulated on development, we make a version update, and make a release.
* **development**
All development goes on in this branch. If you're making a contribution,
you are supposed to make a pull request to _development_.


## Code practices

Please help us follow the best practice to make it easy for the reviewer as well as the contributor. We want to focus on the code quality more than on managing pull request ethics. 

* Single commit per pull request
* Reference the issue numbers in the commit message. Follow the pattern ``` Fixes #<issue number> <commit message>```
* Follow uniform design practices. The design language must be consistent throughout the app.
* The pull request will not get merged until and unless the commits are squashed. In case there are multiple commits on the PR, the commit author needs to squash them and not the maintainers cherrypicking and merging squashes.
* If the PR is related to any front end change, please attach relevant screenshots in the pull request description.

## License

This project is currently licensed under the Apache License Version 2.0. A copy of [LICENSE.md](https://github.com/fossasia/susi_iOS/blob/master/LICENSE) should be present along with the source code. To obtain the software under a different license, please contact FOSSASIA.