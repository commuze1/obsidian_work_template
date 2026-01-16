---
tags:
  - <% tp.file.path(true).toLowerCase().replace(/ /g, "-").replace(/\/[^\/]+\.md$/, "") %>
aliases:
  - "#<% tp.file.path(true).toLowerCase().replace(/ /g, "-").replace(/\/[^\/]+\.md$/, "") %>"
---

## Waypoint
<%*
const waypoint = "%% Way" + "point %%";
tR += waypoint;
%>

## Tags
```query
tag:(#<% tp.file.path(true).toLowerCase().replace(/ /g, "-").replace(/\/[^\/]+\.md$/, "") %>)
```