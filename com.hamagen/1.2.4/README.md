# המגן

**Latest version:** 1.2.4

**Bundle ID:** com.hamagen

## Location
```xml
<key>NSLocationAlwaysAndWhenInUseUsageDescription</key>
<string>יש לאפשר גישה למיקום על מנת להשוות את נתיבך אל מול נתיבי חולי קורונה מאומתים</string>
<key>NSLocationAlwaysUsageDescription</key>
<string>יש לאפשר גישה למיקום על מנת להשוות את נתיבך אל מול נתיבי חולי קורונה מאומתים</string>
<key>NSLocationWhenInUseUsageDescription</key>
<string>יש לאפשר גישה למיקום על מנת להשוות את נתיבך אל מול נתיבי חולי קורונה מאומתים</string>
```

## Accelerometer
```xml
<key>NSMotionUsageDescription</key>
<string>יש לאפשר גישה לחיישני תנועה על מנת להשוות את נתיבך אל מול נתיבי חולי קורונה מאומתים</string>
```

## UIBackgroundModes
```xml
<array>
	<string>fetch</string>
	<string>location</string>
	<string>processing</string>
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
