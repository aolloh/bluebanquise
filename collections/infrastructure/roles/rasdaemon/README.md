# Rasdaemon

## Description

The role install and start Rasdaemon tool to track hardware issues.

## External documentation

[Project sources on Github](https://github.com/mchehab/rasdaemon)
[Small tutorial on manual usage](https://www.setphaserstostun.org/posts/monitoring-ecc-memory-on-linux-with-rasdaemon/)

## Instructions

Simply apply the role, then check regularly (using a script or a monitoring
probe) that no errors are found, using command:

```
ras-mc-ctl --error-count
```

## Changelog

**Please now update CHANGELOG file at repository root instead of adding logs in this file.
These logs bellow are only kept for archive.**

* 1.0.0: Role creation. Benoit Leveugle <benoit.leveugle@gmail.com>
