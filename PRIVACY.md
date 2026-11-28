# Privacy

Holoholo stores your tabs, Spaces, pins, favorites, downloads list, closed-tab archive and per-site settings on your Mac, in `~/Library/Application Support/Browser`, together with the Chromium profile data (cookies, cache, extensions, site storage).

Holoholo has no accounts and no analytics, has no server of its own, and does not send your browsing history anywhere.

As with any Chromium-based browser, some requests go to third parties:
- the websites you open and the search engine you choose in Settings;
- search suggestions: while you type in the address bar, what you have typed so far is sent to that search engine to show suggestions, before you press Return. On by default; turn it off in Settings → Search → Search suggestions;
- the Chrome Web Store (Google) when you browse or install extensions, and extension updates;
- Chromium component updates, for example the Widevine module for protected video;
- update checks: Holoholo asks github.com for a small update feed (no system profile or personal data is sent);
- Safe Browsing: addresses are checked on your Mac against Google's lists; only a short fingerprint of a matching address is sent to Google;
- page translation: when you click the translate icon, the text of that page is sent to Google Translate;
- crash reports, only if you turn them on (off by default): a technical crash report (thread stacks, app and macOS version) is sent to Sentry (sentry.io, EU region). No addresses, page content or cookies are added, but fragments of them may be in memory captured with the crash. Without your consent, reports stay on your Mac and are deleted after 5 days;
- whatever the extensions you install do. Check their permissions before installing;
- companions (off by default): if you turn them on in Settings → Companions and allow a tool such as Claude Code, Claude Desktop or Cursor, it can read the tabs and pages in the Spaces you choose and, with "Read & act", act in them. What it reads may be sent to that tool's AI service; this is governed by the tool's own privacy policy, not by Holoholo.

Tab sorting uses an on-device model of macOS; nothing leaves your Mac.

Contact: alxxeu.dev@proton.me
