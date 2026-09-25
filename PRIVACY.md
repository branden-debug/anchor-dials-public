# Anchor Dials privacy policy

Policy revision: 25 September 2026. Applies to the Anchor Dials watch app, its included dial collection and optional Android phone setup app.

Branded Abstract provides Anchor Dials (previously named Quiet Dials). Website: https://brandedabstract.com. For support, privacy questions or a deletion request, contact brandedabstract@gmail.com.

## Your saved anchor

When you choose to drop or move an anchor, the helper requests a precise location fix through Android and Google Play services. It stores one latitude, longitude, accuracy estimate and save time in its private storage on your watch. A short foreground location request may finish after the small request screen closes. A notification is shown during that request. Anchor Dials does not continuously follow your journey or request background-location permission.

Location is optional. You can use the watch face without saving an anchor. Declining precise location prevents the anchor from saving a reliable parking spot; it does not prevent the ordinary clock from working.

An anchor remains until you raise it, replace it, clear the helper's app storage or uninstall the helper. Raising clears its local coordinates immediately. Completing the crown, rotating-bezel or hold gesture confirms clearing. There is no second confirmation or Undo screen.

The helper also contains compatibility with an existing Anchor Dials installation on a paired device using Google's Wear Data Layer. A matching installation can receive the saved spot and deletion updates. The data transport is controlled by Wear OS and Google Play services. Sync may be delayed when devices are disconnected. A phone helper is not required for this watch setup. Clearing an offline device's app storage alone does not remotely delete an existing copy on another device. Raise the anchor while connected before removing an old paired installation, or clear that installation separately.

## Optional phone setup app

The phone setup app asks Google Play services for connected Wear OS devices, using their display names and connection identifiers to show setup buttons and open the Anchor Dials Play listing on your chosen watch. This connection information is used in memory, not stored by the app or sent to Branded Abstract. The phone app displays dial previews and setup instructions. It does not request location or health permissions, read or store your saved anchor, or provide an anchor backup. Google Play services handles the device connection under its own policies. The watch works without this optional phone app.

## Opening Google Maps

Choosing Watch, Phone or View saved place sends the chosen anchor coordinates to Google Maps, or a maps URL handler. This is your explicit request to show the pin or get walking directions. Google Maps and the phone's browser or link handler process that request under their own privacy policies and settings. Branded Abstract does not operate a location server.

Opening a pin is not the same as adding it to Google Maps' Saved list. If you choose Save inside Google Maps, that copy, its navigation and its history are controlled by Google Maps. Raising the Anchor Dials anchor cannot remove them. A dead watch cannot send its local anchor to your phone; save a phone copy before the battery runs out if you need one.

## Battery, settings and complications

Battery learning uses local charge levels, charging state and timestamps. The next sample prunes observations older than 24 hours. A cached drain-rate estimate is used for no longer than 24 hours, although its stored value may remain until replaced or app storage is cleared. Sampling is approximate and can be delayed by Wear OS.

If you start a battery comparison, the helper additionally records timestamps, elapsed time, charge level, charging state, Battery Saver state and the face/always-on labels you chose. These test records stay on your watch. At most 12 completed runs and 4,000 samples per run are retained. Delete them in Anchor Dials → Battery comparison → Delete test records. No test starts automatically.

The face displays time, native weather and values supplied by your chosen complication providers. Those providers control their own data, permissions and goals. Anchor Dials does not request health permissions, download your Fitbit account history or create fitness goals. The helper stores your display preferences and any daily time adjustment locally. Daily adjustments are pruned to a rolling window of 14 days either side of the current day on refresh. Display preferences remain until you change them, clear app storage or uninstall.

## Services and security

Anchor Dials includes AndroidX watch components, Google Play services Location and Wearable APIs, and the Wear remote-activity helper. These provide location and device communication. The app does not include an advertising, analytics or crash-reporting SDK, or send a copy of your anchor to Branded Abstract. Android, Google Play services, your weather/fitness providers and Google Maps may separately process data under their own policies and device settings. See https://policies.google.com/privacy.

The helper stores its files in Android's private app storage and disables Android cloud backup for its own app data. This is not a guarantee against someone who can unlock, debug or compromise the device. Keep your watch locked when it is not being worn. Developer test builds allow debugging; public release builds do not.

## Contact and deletion

You can delete the anchor by raising it, delete comparison records from the test screen, or remove all local helper records with Android's Clear storage or Uninstall controls. A paired copy and a place you saved separately in Maps must be deleted as described above. Revoking location permission stops new location requests but does not erase an already saved anchor.

If you email brandedabstract@gmail.com, we receive the address, message and any attachments you send through Gmail. Send only information needed for support. We use it to answer the request and keep support correspondence for up to 12 months after resolution, unless a legal obligation requires longer retention. Ask the same address for access, correction or deletion. We cannot remotely recover or erase a watch-only anchor we do not hold. Depending on your location, you may also have rights to object, restrict processing or complain to your data protection regulator, including the UK Information Commissioner's Office.

This policy will be updated when the app's data handling changes. The revision date identifies the current text.
