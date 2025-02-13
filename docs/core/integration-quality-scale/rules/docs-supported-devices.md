---
title: "The documentation describes known supported / unsupported devices"
---

## Reasoning

A lot of Home Assistant users buy devices based on if Home Assistant supports them.
To make it easier for users to find out if a device is supported, the documentation should describe the known supported or unsupported devices.
This will decrease the amount of bad experiences where the user finds out their device is not supported when they try to set it up.

## Example implementation

```markdown showLineNumbers

## Supported devices

The following devices are known to be supported by the integration:
- Device 1
- Device 2
- Every appliance that runs MyOS

## Unsupported devices

The following devices are not supported by the integration:
- Device 3
- Appliances built before 2010
```

## Exceptions

This rule does not apply to integrations that do not connect to a device or service.
This rule also does not apply to integrations that don't integrate physical devices.
