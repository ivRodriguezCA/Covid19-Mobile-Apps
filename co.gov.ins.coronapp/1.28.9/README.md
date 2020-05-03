# CoronApp-Colombia

**Latest version:** 1.28.9

**Bundle ID:** co.gov.ins.coronapp

## Location
```xml
<key>NSLocationAlwaysAndWhenInUseUsageDescription</key>
<string>La Aplicación solicita su ubicación para registrar el lugar en donde registra el estado actual de salud.</string>
<key>NSLocationWhenInUseUsageDescription</key>
<string>La Aplicación solicita su ubicación para registrar el lugar en donde registra el estado actual de salud.</string>
```

## NSAppTransportSecurity
```xml
<dict>
	<key>NSExceptionDomains</key>
	<dict>
		<key>apicovid.and.gov.co</key>
		<dict>
			<key>NSThirdPartyExceptionAllowsInsecureHTTPLoads</key>
			<true/>
		</dict>
		<key>apicovidqa.and.gov.co</key>
		<dict>
			<key>NSThirdPartyExceptionAllowsInsecureHTTPLoads</key>
			<true/>
		</dict>
		<key>aprende.colombiaaprende.edu.co</key>
		<dict>
			<key>NSThirdPartyExceptionAllowsInsecureHTTPLoads</key>
			<true/>
		</dict>
		<key>innpulsacolombia.com</key>
		<dict>
			<key>NSThirdPartyExceptionAllowsInsecureHTTPLoads</key>
			<true/>
		</dict>
		<key>www.mintrabajo.gov.co</key>
		<dict>
			<key>NSThirdPartyExceptionAllowsInsecureHTTPLoads</key>
			<true/>
		</dict>
	</dict>
</dict>
```
## Frameworks
- CountryPickerView.framework
- FBLPromises.framework
- GoogleUtilities.framework
- nanopb.framework
- protobuf.framework
- SimpleQRCode.framework
