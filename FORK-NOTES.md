# Fork notes

This fork combines upstream main with the English/Portuguese localization from [PR #43](https://github.com/RoutineMiku/apkstart/pull/43) and validates download ranges (see upstream issue #91). Thanks to the original contributors.

The fork uses the same `%APPDATA%\apkstart` settings and Android data as upstream. Back up existing data before testing. Program updates from upstream are disabled in this fork to prevent replacing the modified application. Runtime components are still downloaded from upstream sources. No Android image is included in the portable build.

The current changes have automated tests, including mocked Electron UI tests; they have not been verified with a real Android emulator or APK installation.
