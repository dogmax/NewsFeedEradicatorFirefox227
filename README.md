# News Feed Eradicator (Legacy Archive Fork)

> **This is a fork of an older version of [News Feed Eradicator](https://github.com/jordwest/news-feed-eradicator) by [Jordan West (jordwest)](https://github.com/jordwest), forked to preserve and build upon the per-site enable/disable feature. The older version was found at [Mozilla's addon site](https://addons.mozilla.org/en-US/firefox/addon/news-feed-eradicator/versions/).**


---

## About

News Feed Eradicator is a browser extension that replaces social media news feeds with an inspiring quote, helping reduce distraction and mindless scrolling.

This repository is a fork based on an older release of the original project. This fork exists to preserve the per-site behaviour available in v2.2.7 and may be developed further. The .xpi does not contain a LICENSE file; the MIT License declaration is documented on the official [AMO release page](https://addons.mozilla.org/en-US/firefox/addon/news-feed-eradicator/versions/) and confirmed in [Jordan West's own repository at the v2.2.7 tag](https://github.com/jordwest/news-feed-eradicator/blob/v2.2.7/LICENSE).

For the actively maintained version, please visit the original project:
**[https://github.com/jordwest/news-feed-eradicator](https://github.com/jordwest/news-feed-eradicator)**

---

## Why this fork?

This fork is based on **v2.2.7**, released on June 9, 2024, which was distributed under the MIT License as confirmed on the [Firefox Add-ons page](https://addons.mozilla.org/en-US/firefox/addon/news-feed-eradicator/versions/) as per the 9th of April 2026, and in [Jordan West's own repository at the v2.2.7 tag](https://github.com/jordwest/news-feed-eradicator/blob/v2.2.7/LICENSE). It does not incorporate any code from v3 or later of the project.

v2.2.7 includes a **per-site enable/disable** feature, which allows you to temporarily re-enable the news feed on a specific site without affecting any other sites. In v3, this was changed to a global toggle that enables or disables the feed across all sites at once. The per-site enable/disable behaviour has been raised in [the original project's discussion tracker](https://github.com/jordwest/news-feed-eradicator/discussions/515#discussioncomment-15774924). The maintainer has acknowledged it was an intentional change and indicated it may potentially be reintroduced as an optional setting, but it is not currently planned as a priority.

This is a regression for users who want fine-grained control. For example, if you temporarily enable the news feed on YouTube, you should not be simultaneously exposed to feeds on Facebook, LinkedIn, Reddit, and every other supported site — which is exactly what the global toggle causes. That kind of all-or-nothing approach undermines the whole point of the extension and encourages the doom scrolling it is meant to prevent.

This fork exists to preserve the per-site behaviour available in v2.2.7 and may be developed further. No changes have been made to the original source code at this time.

---

## Installation

The `.xpi` file is available to download from the [**Releases page**](../../releases).

**Option A — Direct open (simplest)**

Download the `.xpi` file and open it directly in Firefox. Firefox will prompt you to install it.

**Option B — Install from file**

1. Download the `.xpi` file from the [Releases](../../releases) page.
2. In Firefox, go to `about:addons`.
3. Click the gear icon and select **Install Add-on From File...**.
4. Select the downloaded `.xpi` file.

---

## License

This project is licensed under the **MIT License**.

Original work:
Copyright (c) 2013 Jordan West

Fork created by Dogmax

The license text is copied verbatim from [Jordan West's repository at the v2.2.7 tag](https://github.com/jordwest/news-feed-eradicator/blob/v2.2.7/LICENSE) ([archived April 9, 2026](https://web.archive.org/web/20260409101140/https://github.com/jordwest/news-feed-eradicator/blob/v2.2.7/LICENSE)) and is included in the [LICENSE](./LICENSE) file in this repository.

Note: Later versions of News Feed Eradicator (v3 and above) have been released under the [GNU Affero General Public License v3.0 (AGPL-3.0)](https://github.com/jordwest/news-feed-eradicator/blob/main/LICENSE). This fork is based solely on v2.2.7, which was released under the MIT License, and contains no code from any later version.

---

## Credits

All original credit goes to **[Jordan West (jordwest)](https://github.com/jordwest)** for creating and maintaining News Feed Eradicator. This fork exists primarily to preserve an older version of their work.
