# Ice Hockey — Y8 Build

This branch packages the existing Ice Hockey.io client and assets with the Y8 JavaScript SDK loader and initialization.

## Before uploading
1. Open `index.html`.
2. Find `const Y8_APP_ID = 'YOUR_Y8_APP_ID';`.
3. Replace the placeholder with the App ID shown in your Y8 Developer Portal under your game's **SDK Initialization** tab.
4. This build does **not** include Y8 ads yet; no Game ID is needed unless you integrate ads.
5. Test the build on Y8's preview before submitting.

## Download
Open the repository's branch dropdown and choose `y8-build`, or use:
https://github.com/ice-hockey-owner/Ice-Hockey.io/archive/refs/heads/y8-build.zip

This is a dedicated build branch, not a separate GitHub repository. The GitHub connection available here can create branches and files but does not expose repository creation. The existing main branch is not modified by this Y8 branch.

SDK source and documentation:
- https://docs.y8.com/sdk/intro/
- https://docs.y8.com/studio/sdk-initialization/

The online multiplayer still relies on the existing game server URL configured in the client; verify that server is live and accessible from Y8 before publishing.
