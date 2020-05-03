# COVID-19 PK

**Latest version:** 1.5

**Bundle ID:** com.govpk.covid19

## Location
```xml
<key>NSLocationAlwaysAndWhenInUseUsageDescription</key>
<string>We need access to your location to show you relevent Radius Alert results.</string>
<key>NSLocationWhenInUseUsageDescription</key>
<string>We need access to your location to show you relevent Radius Alert results.</string>
```

## UIBackgroundModes
```xml
<array>
	<string>fetch</string>
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
- Alamofire.framework
- BEMCheckBox.framework
- FBLPromises.framework
- GoogleUtilities.framework
- nanopb.framework
- NVActivityIndicatorView.framework
- protobuf.framework
- SDWebImage.framework
- Siren.framework
- SlideMenuControllerSwift.framework
- SwiftyJSON.framework
