# DomainGuard downloads

DomainGuard is an Android firewall with domain rules, delayed changes, and temporary pauses. It is a modified GPLv3 build of [HeartGuard](https://github.com/hoodedpaladin/HeartGuard), derived from [NetGuard](https://github.com/M66B/NetGuard).

[Download the latest APK](https://github.com/phooBarred/DomainGuard-downloads/releases/latest/download/DomainGuard.apk) · [Release notes and source archives](https://github.com/phooBarred/DomainGuard-downloads/releases) | [Source code](https://github.com/phooBarred-Apps/DomainGuard)

## Installing and updating

Install **DomainGuard.apk** on Android 5.1 or newer. If Android asks, allow the app opening the APK to install it, then confirm installation.

Open **Check for updates** in DomainGuard's menu. **Install update** downloads the newer release, verifies the APK, and opens Android's installation confirmation. The update screen also links to release history.

## Finding and copying domains

Hold the main magnifying glass and select **Search domains across apps**. Matching apps appear in the main list with their domains expanded. Each app has its own search, and a local search with no matches leaves the app visible.

**Copy domains** copies distinct domains from the displayed results, respecting the main search, each app's search, Hide allowed, and the displayed row limit. Each app also has its own Copy domains button. Scrollable rows in the displayed list are included.

## Allowing, blocking, and pausing

Tap a domain and choose **Allow** or **Block**. The globe in the dialog toggles whether the rule applies globally. The dropdown attached to the address offers parent domains, including shared-hosting domains such as githubusercontent.com.

**Global lists** opens the whitelist or blacklist, each with search and bulk entry. Domain rules include subdomains; URL paths and query strings are not separate rules. App-specific blocks can remain in force despite a global allow.

Allow and Block can be temporary. An app's **Info & controls** panel also offers a timed pause of protection for that app. Turning DomainGuard off offers automatic resumption. Temporary periods are limited to seven days, and the applicable rule delays still apply.

## Lists, controls, and delays

Sort and Filter offer **Set as default**. The circular-arrow Reset clears searches and restores saved filter defaults while preserving the current sort.

**Display settings** controls toolbar placement, domain search visibility, timestamps, and compact domain lists. The compact-list switch sets whether a height limit applies; tap its name to adjust the height or try the full-screen preview.

**Rule change delay** accepts seconds, minutes, hours, or days, with a readable duration. Decimal entries round to whole seconds. Each app can override the general delay; reducing a delay waits the difference before taking effect.

**Notify on global blocks** is off by default. Enable it to include access notifications for domains blocked by global rules.

## Source and license

[Browse the source code and development history](https://github.com/phooBarred-Apps/DomainGuard) in the public DomainGuard repository. Each release also includes its corresponding GPLv3 source archive and SHA-256 checksums. Original notices and [LICENSE](LICENSE) are retained.

DomainGuard is an independent modified build, not an official upstream release.
