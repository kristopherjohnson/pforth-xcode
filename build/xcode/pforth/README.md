This directory and its subdirectories contain Xcode workspace and project files for building the `pforth` and `pforth_standalone` targets.

To build from the command line, do the following:

    cd build/xcode/pforth
    xcodebuild

The executables will be in the build/xcode/pforth/build/Release directory.

To build from within Xcode, do the following:

1. Open Xcode
2. Open the `build/xcode/pforth.xcworkspace` workspace
3. If it is not already selected, select the `pforth_standalone` scheme
4. Select the *Product > Build For > Running* menu item

Note that the Xcode scheme will build the Debug configuration.

