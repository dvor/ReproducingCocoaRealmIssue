Simple project to reproduce issue with using realm-cocoa in project with iOS and OS X targets.

Steps to reproduce issue:

- clone project
- run `pod install` (I was running CocoaPods 1.0.1)
- open and compile the project:
    - OS X target works fine
    - iOS target fails with `Undefined symbols for architecture x86_64` error.
