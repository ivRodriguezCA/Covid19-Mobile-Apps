# StopKorona!

**Latest version:** 1.0.1

**Bundle ID:** mk.gov.koronavirus.stop

## Bluetooth
```xml
<key>NSBluetoothAlwaysUsageDescription</key>
<string>StopKorona! exchanges Bluetooth signals with nearby phones that run the same app. These signals are in a form of anonymous ID to ensure your privacy. </string>
<key>NSBluetoothPeripheralUsageDescription</key>
<string>StopKorona! exchanges Bluetooth signals with nearby phones that run the same app. These signals are in a form of anonymous ID to ensure your privacy. </string>
```

## NSAppTransportSecurity
```xml
<dict>
	<key>NSAllowsArbitraryLoads</key>
	<true/>
	<key>NSAllowsArbitraryLoadsInWebContent</key>
	<true/>
	<key>NSExceptionDomains</key>
	<dict>
		<key>stop.koronavirus.gov.mk</key>
		<dict>
			<key>NSExceptionAllowsInsecureHTTPLoads</key>
			<true/>
			<key>NSExceptionRequiresForwardSecrecy</key>
			<false/>
			<key>NSIncludesSubdomains</key>
			<true/>
			<key>NSTemporaryExceptionMinimumTLSVersion</key>
			<string>TLSv1.0</string>
		</dict>
		<key>virustrace.nextsense.com</key>
		<dict>
			<key>NSExceptionAllowsInsecureHTTPLoads</key>
			<true/>
			<key>NSExceptionRequiresForwardSecrecy</key>
			<false/>
			<key>NSIncludesSubdomains</key>
			<true/>
			<key>NSTemporaryExceptionMinimumTLSVersion</key>
			<string>TLSv1.0</string>
		</dict>
	</dict>
</dict>
```

## UIBackgroundModes
```xml
<array>
	<string>bluetooth-central</string>
	<string>bluetooth-peripheral</string>
	<string>remote-notification</string>
</array>
```

## UIRequiredDeviceCapabilities
```xml
<array>
	<string>peer-peer</string>
	<string>bluetooth-le</string>
	<string>arm64</string>
</array>
```

## Frameworks
- Alamofire.framework
- GoogleUtilities.framework
- nanopb.framework
- NVActivityIndicatorView.framework
- ObjectMapper.framework
- SwiftPhoneNumberFormatter.framework
- VKPinCodeView.framework
