---
title: Removing Samples from an AEM Maven project
description: Learn how to clean-up and remove sample code from an AEM Project generated by the AEM Project Archetype.
version: Cloud Service
topic: Development
feature: AEM Project Archetype
role: Developer
level: Beginner
kt: 9092
thumbnail: 337263.jpeg
exl-id: 4e10c2b7-41b6-41a0-b8d4-9207a9d3f9c8
---
# Removing samples from an AEM Maven project

Learn how to clean-up and remove generated sample code from an AEM Project generated by the AEM Project Archetype.

>[!VIDEO](https://video.tv.adobe.com/v/337263/?quality=12&learn=on)


## Resources

+ [AEM Maven Project Archetype](https://github.com/adobe/aem-project-archetype)

## Commands

The following commands can be executed to remove the generated sample files from the AEM Maven Project:

```
rm -rf core/src/main/java/com/adobe/aem/wknd/examples/core/filters \
rm -rf core/src/main/java/com/adobe/aem/wknd/examples/core/listeners \
rm -rf core/src/main/java/com/adobe/aem/wknd/examples/core/models \
rm -rf core/src/main/java/com/adobe/aem/wknd/examples/core/schedulers \
rm -rf core/src/main/java/com/adobe/aem/wknd/examples/core/servlets \
rm -rf core/src/test/java/com/adobe/aem/wknd/examples/core/* \
rm -rf ui.apps/src/main/content/jcr_root/apps/wknd-examples/components/helloworld \
rm -rf ui.frontend/src/main/webpack/components/_helloworld.js \
rm -rf ui.frontend/src/main/webpack/components/_helloworld.css
```

## Edits

Remove the `<div class="helloworld" ...></div>` from:

```
ui.frontend/src/main/webpack/static/index.html
```

Remove the `<helloworld>` component instance definition from:

```
ui.content/src/main/content/jcr_root/content/wknd-examples/us/en/.content.xml
```