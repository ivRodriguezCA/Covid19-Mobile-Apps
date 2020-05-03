# Rakning C-19

**Latest version:** 1.1.0

**Bundle ID:** is.landlaeknir.rakning

## Location
```xml
<key>NSLocationAlwaysAndWhenInUseUsageDescription</key>
<string>Rakning C-19 uses your location to track who you might have come in contact with who is infected.</string>
<key>NSLocationAlwaysUsageDescription</key>
<string>Rakning C-19 uses your location to track who you might have come in contact with who is infected.</string>
<key>NSLocationWhenInUseUsageDescription</key>
<string>Rakning C-19 uses your location to track who you might have come in contact with who is infected.</string>
```

## Accelerometer
```xml
<key>NSMotionUsageDescription</key>
<string>Allow Rakning C-19 to access your device's accelerometer to better track your location.</string>
```

## UIBackgroundModes
```xml
<array>
	<string>location</string>
	<string>remote-notification</string>
</array>
```

## NSAppTransportSecurity
```xml
<dict>
	<key>NSAllowsArbitraryLoads</key>
	<true/>
	<key>NSExceptionDomains</key>
	<dict>
		<key>localhost</key>
		<dict>
			<key>NSExceptionAllowsInsecureHTTPLoads</key>
			<true/>
		</dict>
	</dict>
</dict>
```
