---
title: "Automatic Image Optimization"
date: "2022-08-26"
---

Starting with Next.js 10, the framework introduced a new helpful **Image** component and automatic image optimization.

Before Next.js introduced these two new features, we had to optimize every image using an external tool and then write down a complex _srcset_ property for every HTML _<img>_ tag to set responsive images for different screen sizes.

Indeed, automatic image optimization will take care of serving your images using modern formats (such as **WebP**) to all those browsers that support it. But it will also be able to fall back on older image formats, such as _png_ or _jpg_, in case the browser you're using doesn't support it. It also resizes your images to avoid serving heavy pictures to the client as it would negatively affect the asset's download speed.
