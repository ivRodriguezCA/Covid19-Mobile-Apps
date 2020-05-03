# COVA

**Latest version:** 1.0.16

**Bundle ID:** com.production.punjabCova

## Location
```xml
<key>NSLocationAlwaysUsageDescription</key>
<string>Location is required to show directions from current location to selected location</string>
<key>NSLocationWhenInUseUsageDescription</key>
<string>Location is required to show directions from current location to selected location</string>
```

## Bluetooth
```xml
<key>NSBluetoothAlwaysUsageDescription</key>
<string>Application needs Bluetooth access in order to notify you in-case you come close to any Corona infected/suspected</string>
<key>NSBluetoothPeripheralUsageDescription</key>
<string>Application needs Bluetooth access in order to notify you in-case you come close to any Corona infected/suspected</string>
```

## Camera
```xml
<key>NSCameraUsageDescription</key>
<string>This app requires access to the camera to click picture while uploading documents</string>
```

## NSPhotoLibraryUsageDescription
```xml
<key>NSPhotoLibraryUsageDescription</key>
<string>This app requires access to the photo library to choose picture while uploading documents</string>
```

## UIBackgroundModes
```xml
<array>
	<string>bluetooth-central</string>
	<string>bluetooth-peripheral</string>
	<string>location</string>
	<string>processing</string>
</array>
```

## NSAppTransportSecurity
```xml
<dict>
	<key>NSAllowsArbitraryLoads</key>
	<true/>
</dict>
```

## Frameworks
- GoogleUtilities.framework
- IQKeyboardManager.framework
- nanopb.framework
- protobuf.framework
- SDWebImage.framework
