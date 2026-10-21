# HeartGuard-MW downloads

HeartGuard-MW is a modified GPLv3 build of [HeartGuard](https://github.com/hoodedpaladin/HeartGuard), derived from [NetGuard](https://github.com/M66B/NetGuard).

[Download the latest APK](https://github.com/phooBarred/heartguard-mw-downloads/releases/latest/download/HeartGuard-MW.apk) · [Releases and corresponding source](https://github.com/phooBarred/heartguard-mw-downloads/releases)

## Installing and updating

Install HeartGuard-MW.apk on Android 5.1 or newer. If asked, allow your browser to install this download. This updates an existing HeartGuard-MW installation; the original HeartGuard is a separate app.

Open **Check for updates** in the app menu. **Install update** downloads the newer release, checks its checksum and signing identity, then opens Android's installer for your confirmation.

## Finding domains

Open **Search domains across apps** in the app menu. Enter a domain or paste a URL to see matching apps and their latest recorded allowed/blocked outcome. This search includes apps hidden by the main screen's filters. **Copy domains** copies all matching domains once each, including results outside the visible area.

Search within either global list to find existing entries, including parent-domain rules covering the searched host. For example, searching `images.example.com` also finds an `example.com` rule.

## Global lists and exceptions

Open **Global lists** in the app menu, then choose the whitelist or blacklist. Paste domains or HTTP/HTTPS URLs, one per line. Domains include their subdomains, across existing and future apps; URL paths and query strings are not separate rules. The whitelist also accepts exact IP addresses. **Done** or Android Back returns to the Global lists menu.

Use **Allow globally** from a domain's menu to add it to the whitelist, or **Block for this app** to create an app exception. Rule delays, global DNS blocks and lockdown still apply. Remove an app exception through **Rules**.

## App and domain lists

App searches, expanded apps and scroll position survive rule updates. Live domain rows retain their identity when traffic arrives. Sort and filter controls support saved defaults; Settings > Options lets you choose their placement. **Show in toolbar if room** keeps Filter and Sort together when they fit.

In each expanded app, the Sort icon sits beside **Hide allowed domains**. **Always show domain search per app** in Settings > Options keeps search visible by default; turn it off to open and close each app's search with the magnifying glass. Closing search clears that app's filter.

## Rule delays and notifications

**Rule change delay** accepts seconds, minutes, hours or days, with an exact duration preview. Existing delays still apply before a reduction takes effect.

**Hide global block notifications** in Settings > Options is off by default. Turn it on to suppress access notifications for active global blacklist matches, including subdomains. Blocking and access history remain unchanged.

## Source and license

Each release includes its exact corresponding source archive and SHA-256 checksums. Development takes place in a private repository, while the released source remains available here under GPLv3. Original notices are retained in the source archive and [LICENSE](LICENSE).

This is an independent modified build, not an official upstream release. Modifications for the first public MW release were made on October 20, 2026.
