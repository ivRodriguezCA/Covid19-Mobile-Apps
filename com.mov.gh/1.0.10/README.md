# GH COVID19 Tracker

**Latest version:** 1.0.10

**Bundle ID:** com.mov.gh

## Location
```xml
<key>NSLocationAlwaysAndWhenInUseUsageDescription</key>
<string>Allow GH COVID19 Tracker to use your location to evaluate the impact of COVID19 in your region</string>
<key>NSLocationAlwaysUsageDescription</key>
<string>Allow GH COVID19 Tracker to use your location to evaluate the impact of COVID19 in your region</string>
<key>NSLocationWhenInUseUsageDescription</key>
<string>Allow GH COVID19 Tracker to use your location to evaluate the impact of COVID19 in your region</string>
```

## NSAppTransportSecurity
```xml
<dict>
	<key>NSAllowsArbitraryLoads</key>
	<false/>
	<key>NSExceptionDomains</key>
	<dict>
		<key>localhost</key>
		<dict>
			<key>NSExceptionAllowsInsecureHTTPLoads</key>
			<false/>
		</dict>
	</dict>
</dict>
```
