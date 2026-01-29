# BlackBerry KEY2 LineageOS development

## What works?
### Athena
| Feature     | Status | Notes |
|-------------|--------|-------|
| Audio       | ✅     |Works fine.|
| Bluetooth   | ✅     |Works. Audio too.|
| Charging    | ✅     |Works fine. Maybe can log a bit too much.|
| Keyboard    | ✅❓   |Works okay, but the touchpad does not disable itself when typing makes it unusable. Maybe a custom HAL will fix it. Etason.|
| Lights      | ✅     |Works.|
| Wifi        | ✅     |Works fine. Both 2.4 and 5GHz.|
| GPS         | ✅❓   |Used to work, but not tested as of January 2026.|
| Camera      | ✅❓   |Ditto GPS. Definitely broken because of being disabled (for Luna). Maybe worth enabling for athena.|
| RIL         | ✅     |Works. Sometimes doesn't start. Sometimes crashes device. When device is booted, it may not get signal until a few mins. Apart from that, stable.|
| Call audio  | ✅     |Works.|
| SDCard      | ✅     |Works okay.|
| Fingerprint | ✅     |Ditto.|
| IMS         | ✅❓   |Starts. Not tested farther.|
| NFC         | ✅     |Works fine.|
| SELinux     | ❌     |LOL|

### Luna
| Feature     | Status | Notes |
|-------------|--------|-------|
| Audio       | ✅❓   |Works fine?! My device has BROKEN audio for some reason, can't test.|
| Bluetooth   | ✅     |Starts. Pairs. Works ok.|
| Charging    | ✅     |Works fine. Maybe can log a bit too much.|
| Keyboard    | ✅     |Works okay.|
| Lights      | ❓     |Lights HAL being written|
| Wifi        | ✅     |Works fine. Both 2.4 and 5GHz.|
| GPS         | ✅❓   |Used to work, but not tested as of January 2026.|
| Camera      | ❌     |Does not work.|
| RIL         | ✅❓   |Works. Sometimes doesn't start. When device is booted, it may not get signal until a few mins. Apart from that, stable.|
| Call audio  | ❌     |Mic does not work. Audio only via speaker.|
| SDCard      | ✅     |Works okay.|
| Fingerprint | ❌     |Service not added.|
| IMS         | ✅❓   |Starts. Not tested farther.|
| NFC         | ❌     |Service not even added.|
| SELinux     | ❌     |LOL|

## Device repos
| Device         | Repo |
|----------------|------|
| Common         |[android_device_blackberry_sdm660-common](https://github.com/FumoEnterprises/android_device_blackberry_sdm660-common)|
| Key2 (athena)  |[android_device_blackberry_athena](https://github.com/FumoEnterprises/android_device_blackberry_athena)|
| Key2 LE (luna) |[android_device_blackberry_luna](https://github.com/FumoEnterprises/android_device_blackberry_luna)|

## Vendor repos
| Device         | Repo |
|----------------|------|
| Common         |[android_vendor_blackberry_sdm660-common](https://github.com/FumoEnterprises/android_vendor_blackberry_sdm660-common)|
| Key2 (athena)  |[android_vendor_blackberry_athena](https://github.com/FumoEnterprises/android_vendor_blackberry_athena)|
| Key2 LE (luna) |[android_vendor_blackberry_luna](https://github.com/FumoEnterprises/android_vendor_blackberry_luna)|
