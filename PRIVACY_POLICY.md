# Privacy Policy for Smart Tab Organizer

Last updated: 2026-11-24

## Overview

Smart Tab Organizer helps you organize browser tabs into color-coded tab groups, save and restore workspaces, sleep inactive tabs to save memory, and remove duplicate tabs.

## What Data Is Processed

- **Open tab titles and URLs:** Read locally in your browser only when you inspect stats, trigger grouping/duplicate cleanup, sleep inactive tabs, or save a workspace.
- **Tab activity timestamps:** Stored locally to detect tabs that have been inactive for 30+ minutes when the optional Auto-Sleep RAM Saver is enabled.
- **Custom rules, workspaces, and preferences:** Stored locally in your browser via `chrome.storage.local`.
- **Optional Pro license key:** Stored locally if you activate a Pro license.

## How Data Is Stored and Transmitted

- All tab classification, grouping, workspace snapshots, and RAM-saving sleep checks run **100% locally on your device**.
- If you enable optional on-device Chrome AI classification and your browser supports Chrome's built-in local model, unknown tabs are classified locally on your device without sending data off-device.
- If you explicitly enter a Pro license key and click **Activate**, only the license key (and anonymous extension instance label) is sent over HTTPS to the configured licensing provider (`api.lemonsqueezy.com` or `api.gumroad.com`) to verify validity.
- Smart Tab Organizer does **not** transmit, upload, sell, or share any browsing history, tab URLs, or personal data to external servers or third parties.
- This extension does **not** use cookies, analytics, tracking, or advertising SDKs.

## Data Retention and Deletion

- Local rules, workspaces, timestamps, and preferences remain in browser storage until you clear them or uninstall the extension.

## Contact

For questions or privacy requests, please open an issue at:
https://github.com/rgunindi/smart-tab-organizer/issues
