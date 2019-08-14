# SpinnerRowTest

### Running This Application

*Note*: Ensure you are on a Mac computer with Xcode 10.3 or higher installed. This also assume you have both the Cordova (8.X+) and Ionic (5.X+) CLIs installed globally on your machine.

1. Download the project ZIP
2. Unzip the file
3. Navigate to the project directory on your machine via Terminal / command line (for most users that will be `cd Downloads/<project name>`
4. Ensure you are in the root directory of the project
5. Run `npm install`
6. Run `ionic cordova build ios` (this may "fail" as signing credentials aren't set up, that's fine, proceed)
7. Open Xcode
8. Open the project in Xcode by navigating to the project directory, then opening the `platforms/ios/MyApp.xcworkspace` file (*not* the `.xcodeproj` file)
9. Add signing credentials as necessary in the project
10. Run on a simulator or device

Main source code can be found in the `home.page.html` file.
