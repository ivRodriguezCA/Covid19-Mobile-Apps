# TraceTogether

**Latest version:** 1.6

**Bundle ID:** sg.gov.tech.bluetrace

## Bluetooth
```xml
<key>NSBluetoothAlwaysUsageDescription</key>
<string>TraceTogether exchanges Bluetooth signals with nearby phones running the same app. These signals contain an anonymised ID, which is encrypted and changes continually to ensure your privacy.</string>
<key>NSBluetoothPeripheralUsageDescription</key>
<string>TraceTogether exchanges Bluetooth signals with nearby phones running the same app. These signals contain an anonymised ID, which is encrypted and changes continually to ensure your privacy.</string>
```

## Camera
```xml
<key>NSCameraUsageDescription</key>
<string>Grant TraceTogether permissions to access your camera if you would like to upload a photo as part of a support request</string>
```

## NSPhotoLibraryUsageDescription
```xml
<key>NSPhotoLibraryUsageDescription</key>
<string>Grant TraceTogether permissions to access your photo library if you would like to upload a photo as part of a support request</string>
```

## UIBackgroundModes
```xml
<array>
	<string>bluetooth-central</string>
	<string>bluetooth-peripheral</string>
	<string>remote-notification</string>
</array>
```

## Frameworks
- CommonUISDK.framework
- FBLPromises.framework
- GoogleUtilities.framework
- GTMSessionFetcher.framework
- Lottie.framework
- MessagingAPI.framework
- MessagingSDK.framework
- nanopb.framework
- protobuf.framework
- SDKConfigurations.framework
- SupportProvidersSDK.framework
- SupportSDK.framework
- ZendeskCoreSDK.framework

## (Potential) Bluetooth Beacons Information
```xml
<key>TRACER_SVC_ID</key>
<string>B82AB3FC-1595-4F6A-80F0-FE094CC218F9</string>
<key>V2_CHARACTERISTIC_ID</key>
<string>117BDD58-57CE-4E7A-8E87-7CCCDDA2A804</string>
```
