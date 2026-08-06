# PlacePark — Support

**App:** PlacePark — Place-aware parking sessions  
**Contact:** [surival987@gmail.com](mailto:surival987@gmail.com)

Thank you for using PlacePark. This page is the support destination for App Store listings and general help.

## Contact

Email: **[surival987@gmail.com](mailto:surival987@gmail.com)**

Please include:

- Your iOS version and device model (if relevant)
- A short description of the issue
- Screenshots if helpful

We typically reply within a few business days.

## Frequently Asked Questions

### What does PlacePark do?

PlacePark helps you run **place-aware parking sessions**: save where you parked, set a local timer reminder, and open walking directions in Apple Maps. You can also set **Place Rules** so automatic Save Parking (Siri / Shortcuts / CarPlay disconnect) skips Home or Work, while favorites can use a default reminder duration. Data stays on your device. No account is required.

### What are Place Rules?

Place Rules are locations you configure in the App:

- **Excluded** (for example Home or Work): auto-save will skip here to avoid false sessions.
- **Favorites** (for example a mall or hospital): optional default timer for auto-save and helpful prefills when you save manually.

Manual **Save Parking** in the App is never blocked by Place Rules.

### Why does PlacePark need Location?

Location (When In Use) is used to record your parking spot, show distance, match Place Rules near you, and support Save Parking from Siri / Shortcuts. PlacePark does not use Background Location for continuous tracking.

### Why do I need Notifications?

Reminders are **local notifications** scheduled on your device. The App may also notify you when auto-save is skipped because of Place Rules. Notifications do not require a PlacePark server. iOS may delay notifications in Low Power Mode or Focus modes.

### How do Siri and Shortcuts work?

PlacePark provides a **Save Parking** App Intent. You can run it from Siri or the Shortcuts app, including a personal automation when CarPlay disconnects. Use Duration **Default** to follow place/app defaults. Setup steps are also listed in the App under Settings → Siri & Shortcuts.

### What is PlacePark Pro?

PlacePark Pro is a **one-time** in-app purchase (not a subscription). It unlocks unlimited parking history, Home Screen widgets, and optional pre-reminders. Place Rules are available on the free tier (with a free place limit). Purchases are processed by Apple. Use **Restore Purchases** in the App after reinstalling or switching devices signed into the same Apple ID.

### Live Activity / Lock Screen timer

When you save parking, PlacePark may show a Live Activity on Lock Screen and Dynamic Island (if enabled in iOS Settings). You can turn Live Activities off system-wide; saving a spot still works.

### My GPS seems inaccurate indoors

Indoor parking often has poor GPS. Use a short note (floor / spot number) and an optional photo. PlacePark does not claim meter-level accuracy indoors.

### How do I delete my data?

Delete place profiles and history entries in the App, or uninstall PlacePark to remove app-stored local data (subject to iOS and your device backups).

### Privacy

See our [Privacy Policy](privacy.md). App Store privacy labels are intended to reflect **Data Not Collected** for PlacePark’s on-device design.

## App Store review / testing notes

If you are reviewing the App (including Guideline 4.3 differentiation):

1. Allow Location and Notifications when prompted.
2. On Home, use **+ Home** (or Manage places) to create an excluded place at your current location.
3. Run **Save Parking** via Shortcuts/Siri with Duration = Default near that place — auto-save should **skip**.
4. Tap **Save Parking** manually in the App — save should still succeed (Match banner may explain exclusion).
5. Optional: add a Favorite with a default duration and confirm Default duration follows that place.
6. Optional: purchase or restore **PlacePark Pro** (`com.surival.parkpin.pro`) in sandbox / TestFlight.

## Links

- [Privacy Policy](privacy.md)
- Email support: [surival987@gmail.com](mailto:surival987@gmail.com)
