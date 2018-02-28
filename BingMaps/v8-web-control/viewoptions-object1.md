---
title: "ViewOptions Object1 | Microsoft Docs"
ms.custom: ""
ms.date: "02/28/2018"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: df0accb2-08e3-44b0-bd7a-4ca103aa0130
caps.latest.revision: 7
author: "rbrundritt"
ms.author: "richbrun"
manager: "stevelom"
---
# ViewOptions Object
The following view options that can be used when loading the map or when using the **setView** function.

Name          | Type            | Description
------------- | --------------- | -----------------------------------
`bounds`        | [LocationRect](LocationRect%20Class.md)    | The bounding rectangle of the map view. If both bounds and center are specified, bounds takes precedence over center.
`center`        | [Location](Location%20Class.md)        | The location of the center of the map view. If both bounds and center are specified, bounds takes precedence over center.
`centerOffset` | [Point](https://msdn.microsoft.com/library/mt712693.aspx) | The amount the center is shifted in pixels. This property is ignored if center is not specified.
`heading`       | number          | The directional heading of the map. The heading is represented in geometric degrees with 0 or 360 = North, 90 = East, 180 = South, and 270 = West.
`labelOverlay`  | [LabelOverlay](https://msdn.microsoft.com/library/mt736396.aspx) | Indicates how the map labels are displayed.
`mapTypeId`     | [MapTypeId](MapTypeId%20Enumeration.md)       | The map type of the view. 
`padding`       | number          | The amount of padding in pixels to be added to each side of the bounds of the map view.
`pitch`         | number          | The angle relative to the horizon to tilt a streetside panorama image.
`zoom`          | number          | The zoom level of the map view.