# AutoMute
A MacOS menu bar app that mutes the sound on headphones disconnect / awake from sleep.

## Marketing blurb
As long as AutoMute is running, whenever your Mac goes to sleep, wakes up, or a pair of headphones gets disconnected - the sound is automatically muted.

Works with bluetooth headphones as well!

This is meant to prevent those embarrassing moments when you're arriving at your perfectly silent office or school, opening up your mac, only to find out your beloved "Best of Shakira" playlist is still playing at full volume from last night...

It will also prevent the classic "walk too far away with your bluetooth headset" scenario, where again your mac will take over the sound and allow your co-workers to bask in your embarrassment.

## Download / Install

Best to just get it from the Mac App Store and support the original author:

[> **AutoMute on Mac App Store** <](https://itunes.apple.com/us/app/automute-preventing-awkward-situations/id1118136179)

The alternate option is to download and install the [latest release](https://github.com/nnathan/automute/releases/latest).

## Build Instructions

## Using CLI

To build from command line (without any signing crap):

    xcodebuild archive -workspace automute.xcworkspace -scheme AutoMute -archivePath ./build CODE_SIGN_IDENTITY="" CODE_SIGNING_REQUIRED=NO

### Using Xcode

Simply open the workspace file in Xcode and build "AutoMute", everything *should* work. You will need to configure a codesign certificate. This can be fiddly.

## Screenshots
![Screenshot1](https://user-images.githubusercontent.com/31284/49688097-ac653900-fb15-11e8-9c48-3db96df5dcbf.png)
![Screenshot2](https://user-images.githubusercontent.com/31284/49688098-ae2efc80-fb15-11e8-8034-14c67fb69d90.png)

## Thankies
[StartAtLoginController](https://github.com/alexzielenski/StartAtLoginController) by Alex Zielenski and Travis Tilley was super helpful!
