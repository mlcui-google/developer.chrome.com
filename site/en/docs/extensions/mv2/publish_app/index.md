---
layout: "layouts/doc-post.njk"
title: "Publish Your App"
#date: TODO
#updated: TODO
description: TODO
---

{% include 'partials/extensions/mv2-legacy-page.md' %}

<div class="aside aside--caution"><b>Important:</b> Chrome will be removing support for Chrome Apps on all platforms. Chrome browser and the Chrome Web Store will continue to support extensions. <a href="https://blog.chromium.org/2020/01/moving-forward-from-chrome-apps.html"><strong>Read the announcement</strong></a> and learn more about <a href="https://developers.chrome.com/apps/migration"><strong>migrating your app</strong></a>.</div>

# Publish Your App

Packaged apps are published in the same way as other types of apps in the Chrome Web Store. For
detailed instructions, see [Publishing Your App][3].

**Tip:** If your app uses [Native Client][4], you can structure your application directory hierarchy
and zip file in a way that reduces the size of the user download package. For details, see [Reducing
the size of the user download package][5].

[1]: https://blog.chromium.org/2020/01/moving-forward-from-chrome-apps.html
[2]: https://developers.chrome.com/apps/migration
[3]: https://developers.google.com/chrome/web-store/docs/publish
[4]: https://developers.google.com/native-client/
[5]: https://developers.google.com/native-client/dev/devguide/distributing#multi-platform-zip
