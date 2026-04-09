# News Feed Eradicator (Legacy Archive Fork)

> **This is a fork of an older version of [News Feed Eradicator](https://github.com/jordwest/news-feed-eradicator) by [Jordan West (jordwest)](https://github.com/jordwest), preserved for personal/archival use.**

---

## About

News Feed Eradicator is a browser extension that replaces social media news feeds with an inspiring quote, helping reduce distraction and mindless scrolling.

This repository is a fork based on an older release of the original project. It has been archived here to preserve that version of the extension.

For the actively maintained version, please visit the original project:
**[https://github.com/jordwest/news-feed-eradicator](https://github.com/jordwest/news-feed-eradicator)**

---

## Why this fork?

This fork is based on **v2.2.7**, released on June 9, 2024, which was distributed under the MIT License as confirmed on the [Firefox Add-ons page](https://addons.mozilla.org/en-US/firefox/addon/news-feed-eradicator/versions/). It does not incorporate any code from v3 or later of the project.

v2.2.7 includes a **per-site enable/disable** feature, which allows you to temporarily re-enable the news feed on a specific site without affecting any other sites. In v3, this was changed to a global toggle that enables or disables the feed across all sites at once.

This is a regression for users who want fine-grained control. For example, if you temporarily enable the news feed on YouTube, you should not be simultaneously exposed to feeds on Facebook, LinkedIn, Reddit, and every other supported site — which is exactly what the global toggle causes. That kind of all-or-nothing approach undermines the whole point of the extension and encourages the doom scrolling it is meant to prevent.

This fork exists to preserve the per-site behaviour available in v2.2.7. No changes have been made to the original source code.

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

> **Note for repo maintainer:** To make the `.xpi` available on the Releases page, go to your repository on GitHub, click **Releases → Create a new release**, tag it (e.g. `v2.2.7`), and attach the `.xpi` file as a release asset before publishing.

---

## License

This project is licensed under the **MIT License**.

Original work:
Copyright (c) Jordan West

Fork maintained by:
Copyright (c) [YOUR NAME OR USERNAME]

See the full license text in the [LICENSE](./LICENSE) file.

---

## Credits

All original credit goes to **[Jordan West (jordwest)](https://github.com/jordwest)** for creating and maintaining News Feed Eradicator. This fork exists solely to preserve an older version of their work.
