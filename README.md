# Expo CLI Android Build Hang

This repository demonstrates a bug where the Expo CLI hangs indefinitely when building an Android app. The issue is intermittent and only reproducible on certain machines, making it hard to debug. The build process shows no specific errors, only that it never completes. 

## Setup

1. Clone this repository.
2. `npm install`
3. Try to build the android app using `expo prebuild` followed by `expo build:android`.  The build should hang.

## Potential Solutions

This problem is machine-specific, which suggests environmental factors may be causing the issue. Potential solutions might involve:
* Checking Android SDK and build tools versions and updating them to the latest.
* Checking Java versions, ensuring they are compatible with the Android SDK.
* Ensuring that there are sufficient resources such as RAM and disk space.
* Investigating the system's anti-virus or security software for any interference. 
* Trying different Android build tools.
* Clearing the Gradle cache.