# Anchor Dials

Anchor Dials: Watch Faces is a Wear OS 6+ watch application by Branded Abstract.

Support: brandedabstract@gmail.com

**Want to try it? [Start with the beta guide](BETA.md).** It has the current access status, install steps and fixes for common setup problems.

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

The Google Play closed test is live. Joining the group is a signup, not a Play test opt-in or installation. **Free beta access is available from 25 September to 8 October 2026, with no promo code required.** A Galaxy Watch 8 Classic tester has confirmed a free installation. Install through Play Store on the watch, or select the watch in the computer browser listing. Some phone links show an incompatible-device sheet without offering the watch; the guide explains the alternatives. If a price appears during this period, stop and contact support. The [beta guide](BETA.md) is the current source for access and setup instructions.
