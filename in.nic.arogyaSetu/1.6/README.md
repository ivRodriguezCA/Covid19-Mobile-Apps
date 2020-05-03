# Aarogya Setu

**Latest version:** 1.6

**Bundle ID:** in.nic.arogyaSetu

## Location
```xml
<key>NSLocationAlwaysAndWhenInUseUsageDescription</key>
<string>Accessed by GoI only to enable relevant and timely medical intervention for COVID-19</string>
<key>NSLocationAlwaysUsageDescription</key>
<string>Accessed by GoI only to enable relevant and timely medical intervention for COVID-19</string>
<key>NSLocationUsageDescription</key>
<string>Accessed by GoI only to enable relevant and timely medical intervention for COVID-19</string>
<key>NSLocationWhenInUseUsageDescription</key>
<string>Accessed by GoI only to enable relevant and timely medical intervention for COVID-19</string>
```

## Bluetooth
```xml
<key>NSBluetoothAlwaysUsageDescription</key>
<string>Monitors your device’s proximity to another mobile device. It is recommended that you keep it on at all times.</string>
<key>NSBluetoothPeripheralUsageDescription</key>
<string>Monitors your device’s proximity to another mobile device. It is recommended that you keep it on at all times.</string>
```

## UIBackgroundModes
```xml
<array>
	<string>bluetooth-central</string>
	<string>bluetooth-peripheral</string>
	<string>fetch</string>
	<string>location</string>
	<string>remote-notification</string>
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
- FBLPromises.framework
- GoogleUtilities.framework
- Gzip.framework
- KeychainSwift.framework
- nanopb.framework
- protobuf.framework
- SVProgressHUD.framework
