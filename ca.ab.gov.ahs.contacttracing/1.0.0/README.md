# ABTraceTogether

**Latest version:** 1.0.0

**Bundle ID:** ca.ab.gov.ahs.contacttracing

## Bluetooth
```xml
<key>NSBluetoothAlwaysUsageDescription</key>
<string>ABTraceTogether exchanges Bluetooth signals with nearby phones running the same app. These signals contain an anonymised ID, which is encrypted and changes continually to ensure your privacy.</string>
<key>NSBluetoothPeripheralUsageDescription</key>
<string>ABTraceTogether exchanges Bluetooth signals with nearby phones running the same app. These signals contain an anonymised ID, which is encrypted and changes continually to ensure your privacy.</string>
```

## PhotoLibrary
```xml
<key>NSPhotoLibraryUsageDescription</key>
<string>Grant ABTraceTogether permissions to access your photo library if you would like to upload a photo as part of a support request</string>
```

## Camera
```xml
<key>NSCameraUsageDescription</key>
<string>Grant ABTraceTogether permissions to access your camera if you would like to upload a photo as part of a support request</string>
```

## UIBackgroundModes
```<key>UIBackgroundModes</key>
<array>
	<string>bluetooth-central</string>
	<string>bluetooth-peripheral</string>
	<string>remote-notification</string>
</array>
```

## Frameworks
- IBMMobileFirstPlatformFoundation.framework
- IBMMobileFoundationSwift.framework
- Lottie.framework
