PhaseGuard AI Privacy Policy
Last updated: July 26, 2026

The short version: PhaseGuard AI collects nothing. All blocking, learning, and analysis happen on your device. We have no servers, and no inside extension analytics.

WHAT THE EXTENSION STORES
PhaseGuard AI saves the following, and only the following:

- Your settings and preferences
- Learned blocking rules and patterns
- Whitelist entries
- Repair history

WHERE IT IS STORED
All of the above is stored locally in your browser using Chrome's storage systems. It never leaves your device. The on-device AI model is downloaded once when needed and then runs entirely locally; after that download, no data is sent to the model provider or anyone else during use.

WHAT THE EXTENSION DOES NOT DO
PhaseGuard AI does not:

- Collect, transmit, sell, or share any personal information or browsing data
- Send browsing history, page content, or personal information to any server
- Send telemetry, error reports, crash reports, or usage statistics to the developers
- Use analytics, tracking, cookies, or third-party data services
- Run remote code
- Show ads

Any install counts or aggregate usage information visible to the developers come only from the Chrome Web Store dashboard provided by Google, not from the extension.

PERMISSIONS EXPLAINED
- Host access (all websites): required so the extension can inspect and block ads and trackers on the pages you visit. All blocking decisions happen on your device; nothing about the pages you visit is transmitted.
- storage: saves your settings, learned rules, whitelist entries, and repair history locally (see above).
- declarativeNetRequest: enforces blocking rules efficiently inside Chrome, entirely on-device.
- declarativeNetRequestFeedback: tells the extension which of its own rules matched, so it can learn patterns and show you per-site stats. This information stays on your device.
- webRequest: observes network requests on-device so the AI can learn tracker patterns. Request data is analyzed locally and never sent anywhere.
- webNavigation: detects page loads so per-site rules, whitelists, and breakage repair are applied to the right page at the right time.
- tabs: links blocked requests to the correct tab so the toolbar counter and per-tab controls work.
- offscreen: runs the on-device AI model in an isolated offscreen document, since Chrome service workers cannot run the model directly. The document has no network access to any server of ours.
- privacy: powers the anti-fingerprinting protection by tightening Chrome privacy settings such as third-party cookie and IP-leak protections.
- browsingData: lets the repair and cleanup features remove tracker cookies and stale site data when you ask them to.

THIRD-PARTY LINKS AND SERVICES
The AI model is downloaded once from its provider's servers. That initial download contains no user data; it is simply the model file being fetched to your device. After that, the model runs fully offline within the extension.

DATA RETENTION AND DELETION
Your data stays in your browser until you delete it. Resetting settings or clearing the whitelist removes those entries immediately. Uninstalling the extension removes all locally stored data.

CHANGES TO THIS POLICY
If this policy changes, the updated version will be posted at this address with a new date. The core promise will not change: no data collection.

DISCLAIMER
PhaseGuard AI is provided "as is" without warranty of any kind. Use at your own risk. The developers are not responsible for any issues that may arise from its use.

CONTACT
Questions? Email getphaseos@gmail.com.
