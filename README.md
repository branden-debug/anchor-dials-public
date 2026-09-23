# Anchor Dials review materials

Anchor Dials: Watch Faces is a Wear OS 6+ watch application by Branded Abstract.

Support: brandedabstract@gmail.com

## Location foreground service demonstration

[Watch the permission and anchor demonstration](https://raw.githubusercontent.com/branden-debug/anchor-dials-public/main/anchor-permission-demo.mp4)

This is a direct screen recording of release 0.21.2-beta1 (version code 23) running on the official Wear OS 6 emulator. The location is a synthetic London test coordinate, not a user's private location. The recording shows:

1. Tapping the anchor on the watch face.
2. The first-use location explanation and Android's precise-location permission prompt.
3. The drop animation and return to the watch face.
4. Opening the saved-anchor screen on a subsequent tap.
5. Holding the anchor to clear the saved spot.

The foreground service starts only after the user chooses to drop an anchor and grants precise location. It requests one fresh accurate fix, displays a location notification while working, then removes the notification and stops. Its timeout is 32 seconds. It does not track a journey or run continuously. Opening Google Maps is a separate user action.

## Privacy

[Read the privacy policy](PRIVACY.md).

## Beta recruitment

[Join the beta signup group](https://groups.google.com/g/quiet-dials-beta/about).

Joining the group is a signup, not an installation. The Google Play test release is being prepared. An installation link will be provided once available. Requires Wear OS 6 or newer.
