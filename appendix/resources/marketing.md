---
title: Marketing
---
<!-- Copyright 2000-2020 JetBrains s.r.o. and other contributors. Use of this source code is governed by the Apache 2.0 license that can be found in the LICENSE file. -->

> **TIP** Please make sure to follow these [Quality Guidelines](https://plugins.jetbrains.com/docs/marketplace/quality-guidelines.html) for the general presentation of your plugin on JetBrains Marketplace.

## Embeddable Widgets

[JetBrains Marketplace](https://plugins.jetbrains.com) provides embeddable widgets that you can place on your website with a simple code snippet:

- Embeddable **Plugin Card** - renders an information card with the plugin name, icon, description, last update, and downloads counter,
- Embeddable **Install Plugin** Button - provides a button that allows installing your plugin right in the user's IDE, if it is currently open.

For more details, please follow the [Embeddable Content](https://plugins.jetbrains.com/docs/marketplace/embeddable-content.html) section in the JetBrains Marketplace documentation.


## Readme Badges

Adding badges to the README files in open-source projects is common for providing additional information for users.

Below are listed a few related to the IntelliJ SDK and plugins development provided by [shields.io](https://shields.io) and [espend.de](https://www.espend.de):

> **NOTE** The following code snippets contain `:pluginId` and `:packageName` placeholders.
>
> `:pluginId` can be obtained from your plugin page URL, like: `https://plugins.jetbrains.com/plugin/6954-kotlin` - in this case, it's `6954`.
>
> `:pluginId` for shields.io also accepts a string ID that can be found in *Versions* tab, like `https://plugins.jetbrains.com/plugin/6954-kotlin/versions`.
>
> `:packageName` for ReSharper accepts only string ID.

### Downloads

**IntelliJ Plugins**

![Downloads](https://img.shields.io/badge/downloads-10M-brightgreen)
```markdown
![Downloads](https://img.shields.io/jetbrains/plugin/d/:pluginId)
```

![Downloads](https://img.shields.io/badge/downloads-10M-blue)
```markdown
![Downloads](http://phpstorm.espend.de/badge/:pluginId/downloads)
```

![Downloads Last Month](https://img.shields.io/badge/downloads-10%20k%20last%20month-blue)
```markdown
![Downloads Last Month](http://phpstorm.espend.de/badge/:pluginId/last-month)
```

**ReSharper Plugins**

![Downloads](https://img.shields.io/badge/downloads-90k-brightgreen)
```markdown
![Downloads](https://img.shields.io/resharper/dt/:packageName)
```


### Rating

**IntelliJ Plugin Numeric Rating**

![Rating](https://img.shields.io/badge/rating-4.5%2F5-brightgreen)
```markdown
![Rating](https://img.shields.io/jetbrains/plugin/r/rating/:pluginId)
```

**IntelliJ Plugin Stars Rating**

![Rating](https://img.shields.io/badge/rating-%E2%98%85%E2%98%85%E2%98%85%E2%98%85%C2%BD-brightgreen)
```markdown
![Rating](https://img.shields.io/jetbrains/plugin/r/stars/:pluginId)
```


### Version

**IntelliJ Plugins**

![Version](https://img.shields.io/badge/jetbrains%20plugin-v1.7-blue)
```markdown
![Version](https://img.shields.io/jetbrains/plugin/v/:pluginId)
```

![Version](https://img.shields.io/badge/version-v1.7-569AC7)
```markdown
![Version](http://phpstorm.espend.de/badge/:pluginId/version)
```

**ReSharper Plugins**

![Version](https://img.shields.io/badge/resharper-v2017.2.0-blue)
```markdown
![Version](https://img.shields.io/resharper/v/:packageName)
```

**ReSharper Plugins (incl. pre-releases)**

![Version](https://img.shields.io/badge/resharper-v2017.3.0--pre0001-yellow)
```markdown
![Version](https://img.shields.io/resharper/v/:packageName?include_prereleases)
```


### Other Badges

**GitHub Actions Workflow**

![Build](https://github.com/JetBrains/intellij-sdk-docs/workflows/Build/badge.svg)
```markdown
![Build](https://github.com/USERNAME/REPOSITORY_NAME/workflows/WORKFLOW_NAME/badge.svg)
```

**JetBrains IntelliJ Platform SDK Docs**

[![JetBrains IntelliJ Platform SDK Docs](https://jb.gg/badges/docs.svg)](http://www.jetbrains.org/intellij/sdk/docs)
```markdown
[![JetBrains IntelliJ Platform SDK Docs](https://jb.gg/badges/docs.svg)](http://www.jetbrains.org/intellij/sdk/docs)
```

**JetBrains Platform Slack**

[![Slack](https://img.shields.io/badge/Slack-%23intellij--platform-blue)](https://plugins.jetbrains.com/slack)
```markdown
[![Slack](https://img.shields.io/badge/Slack-%23intellij--platform-blue)](https://plugins.jetbrains.com/slack)
```

**@JBPlatform Twitter**

[![Twitter Follow](https://img.shields.io/twitter/follow/JBPlatform?style=flat)](https://twitter.com/JBPlatform)
```markdown
[![Twitter Follow](https://img.shields.io/twitter/follow/JBPlatform?style=flat)](https://twitter.com/JBPlatform)
```