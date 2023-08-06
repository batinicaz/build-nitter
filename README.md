# Build Nitter

Simple GHA to build and publish the latest version of [Nitter](https://github.com/zedeus/nitter) as the project [does not provide releases](https://github.com/zedeus/nitter/issues/309).

Job runs every day at 1AM creating a new release if the Nitter source has changed since the last release.
