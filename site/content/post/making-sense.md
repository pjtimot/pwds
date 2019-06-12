---
title: Create editable Microsoft Office charts from R
date: 2016-12-17T15:04:10.000Z
description: By David Smith
image: /img/chart.png
---
R has a rich and infinitely flexible graphics system, and you can easily embed R graphics into Microsoft Office documents like PowerPoint or Word. The one thing I dread hearing after delivering such a document, though, is "how can I tweak that graphic?". I could change the colors or fonts or dimensions in R, of course, but sometimes people just want to watch the world burn tweak graphics to their hearts' content. If you're in that situation, you have a couple of options for using R to create Office documents with graphics, and make those graphics editable. Both options work in conjunction with the "officer" package, which lets you create Word and PowerPoint documents from R. 



The first option — the rvg package — lets you use traditional R graphics commands, but allows the PowerPoint or Word user to modify the components of those graphics. Labels become text elements; lines, points and bars become shapes; and so on. The recipient can then use the standard Office tools to change fonts, resize, rotate, recolor, or add other annotations.
