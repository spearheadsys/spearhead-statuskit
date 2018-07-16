+++
title = "possible configuration issues"
date = 2018-07-02T08:53:33.000Z
severity = "partial-outage"
affectedsystems = [
  "Spearhead Cloud CLI Tools"
]
resolved = false
+++
Unable to remove volumes using spearhead cli.

**Update**: The issue is limited to spearhead volume rm command. Using spearhead-docker volume rm works as intented. This will be tracked upstream shortly.

Until a final solution is available we recommend using spearhead-docker to work with volumes. If additional support is required please send an email to help@spearhead.systems. {{< track "2018-07-02T9:34:00.000Z" >}}