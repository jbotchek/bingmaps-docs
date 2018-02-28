---
title: "Route Object | Microsoft Docs"
ms.custom: ""
ms.date: "02/28/2018"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 06302eac-0542-47cb-b208-91ff26f9b92f
caps.latest.revision: 4
author: "rbrundritt"
ms.author: "richbrun"
manager: "stevelom"
---
# Route Object
Represents a route.

| Name	      | Type        | Description                                                                             |
|-------------|-------------|-----------------------------------------------------------------------------------------|
| `routeLegs` |	[RouteLeg](../v8-web-control/routeleg-object.md)[]	|The legs of the route. Each route leg represents the route between two waypoints. |
| `routePath` | [Location\[\]](https://msdn.microsoft.com/library/mt712687.aspx) | An array of locations that makes up the path of the route.