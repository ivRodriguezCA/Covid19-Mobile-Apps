# StayHomeSafe

**Latest version:** 1.0.7

**Bundle ID:** hk.gov.ogcio.EQuaratine

## Location
```xml
<key>NSLocationAlwaysAndWhenInUseUsageDescription</key>
<string>This app needs location permission to detect your designated quarantine zone. And the zone detection will continue to make sure you remain in the quarantine zone until the completion of your quarantine period. Without the zone detection, this app cannot ensure your compliance with the quarantine program.</string>
<key>NSLocationAlwaysUsageDescription</key>
<string>This app needs location permission to detect your designated quarantine zone. And the zone detection will continue to make sure you remain in the quarantine zone until the completion of your quarantine period. Without the zone detection, this app cannot ensure your compliance with the quarantine program.</string>
<key>NSLocationWhenInUseUsageDescription</key>
<string>This app needs location permission to detect your designated quarantine zone. And the zone detection will continue to make sure you remain in the quarantine zone until the completion of your quarantine period. Without the zone detection, this app cannot ensure your compliance with the quarantine program.</string>
```

## Bluetooth
```xml
<key>NSBluetoothAlwaysUsageDescription</key>
<string>This app needs access to your Bluetooth connection to detect your assigned wristband during the quarantine period.</string>
<key>NSBluetoothPeripheralUsageDescription</key>
<string>This app needs access to your Bluetooth connection to detect your assigned wristband during the quarantine period.</string>
```

## Camera
```xml
<key>NSCameraUsageDescription</key>
<string>This app needs permission to access the camera. The camera is used to scan QR codes and to take photos of your wristband for verifications. Otherwise, you cannot complete the activation of this app.</string>
```

## Microphone
```xml
<key>NSMicrophoneUsageDescription</key>
<string>This app needs microphone permission for voice recognition.</string>
```

## UIBackgroundModes
```xml
<array>
	<string>fetch</string>
	<string>location</string>
	<string>processing</string>
	<string>remote-notification</string>
	<string>bluetooth-central</string>
</array>
```
