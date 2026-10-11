# Recall APK distribution

This repository is private. Source and the public web app remain in [Recall2](https://github.com/Peter7004/Recall2).

[Download the latest signed Recall.apk](https://github.com/Peter7004/Recall-APK-Private/releases/latest/download/Recall.apk)

## Updating

Production package: `io.github.peter7004.recall`. Keep the permanent signing key, increase the pubspec.yaml build number, and dispatch `signed-apk.yml` with the full reviewed source commit SHA. Download and verify the private build artifact, then publish it as the next stable release using asset name `Recall.apk`. Never upload keystores, passwords, or build secrets as assets.

Install newer production APKs over the existing production app without uninstalling. Settings provides full JSON data backup and confirmed restore.

## First migration from the legacy test app

The old `com.example.recall` runner-generated debug key is unavailable. The signed app installs beside it rather than deleting or replacing its data. Keep the old installation and reimport your original CSV. Old bookmarks and study history are not moved automatically. Public test copies are retained as explicitly requested by the owner.

The original v1.0.0-test.1/Recall-test.apk URL is maintained as a compatibility download for 1.0.1. Its legacy APK is retained under Recall-legacy-test.apk.
