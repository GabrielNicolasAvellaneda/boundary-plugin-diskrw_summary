# Boundary Disk Read/Write Summary Plugin

This plugin scans one or more devices/drives for available disk space as a percentage.

### Prerequisites

#### Supported OS

|     OS    | Linux | Windows | SmartOS | OS X |
|:----------|:-----:|:-------:|:-------:|:----:|
| Supported |   v   |    v    |    v    |  v   |

#### Requires Boundary Meter versions v4.2 or greater 

- To install new meter go to Settings->Installation or [see instructons](https://help.boundary.com/hc/en-us/sections/200634331-Installation).
- To upgrade the meter to the latest version - [see instructons](https://help.boundary.com/hc/en-us/articles/201573102-Upgrading-the-Boundary-Meter).

### Plugin Setup

None

### Plugin Configuration Fields

|Field Name|Description                                       |
|:----------|:------------------------------------------------|
|Disk Name  |The name of the disk to be appended to the hostname to display in the legend for the Disk Use Summary data."|
|Mount Point|The mounted point to check for free space. (either this or the Mounted device need to be set for the plugin to function properly)|
|Device     |The mounted device to check for free space. (either this or the Mount Point directory need to be set for the plugin to function properly)|
|Poll Interval | How often to poll for metrics |

### Metrics Collected

|Metric Name            |Description               |
|:----------------------|:-------------------------|
|Total Disk Reads|The total number of disk reads at the moment|
|Total Disk Read Bytes|The total number of bytes read from disks at the moment|
|Total Disk Writes|The total number of disk writes at the moment|
|Total Disk Write Bytes|The total number of bytes written to disks at the moment|
|Disk Reads|The number of reads from the disk at the moment|
|Disk Read Bytes|The number of bytes read from the disk at the moment|
|Disk Writes|The number of writes to the disk at the moment|
|Disk Write Bytes|The number of bytes written to the disk at the moment|
|Disk IOs|The number of IO per second to the disk at the moment|

### Dashboards

Disk Read/Write Summary

### References

None
