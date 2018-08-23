+++
title = "maintenance reboot"
date = 2018-08-23T08:59:57.000Z
severity = "under-maintenance"
affectedsystems = [
  "CloudAPI",
  "Docker API",
  "Spearhead Cloud CLI Tools"
]
resolved = true
+++
One of our management servers requires a reboot in order to perform an OS update. The update is expect to last several minutes during which time our API's will be unavailable.

**Update**: The issue has been fixed upstream in version 6.1.2 and merged into node-spearhead. We have not been able to reproduce this issue.  {{< track "2018-08-23T09:25:00.000Z" >}}