# ProteGO Safe

**Latest version:** 3.0.1

**Bundle ID:** pl.gov.mc.protegosafe

## Bluetooth
```xml
<key>NSBluetoothAlwaysUsageDescription</key>
<string>Korzystając z modułu Bluetooth dbasz o siebie i bliskich. Włącz go, żeby aplikacja mogła ostrzegać Cię o zagrożeniach.</string>
<key>NSBluetoothPeripheralUsageDescription</key>
<string>Korzystając z modułu Bluetooth dbasz o siebie i bliskich. Włącz go, żeby aplikacja mogła ostrzegać Cię o zagrożeniach.</string>
```

## UIBackgroundModes
```xml
<array>
	<string>bluetooth-central</string>
	<string>bluetooth-peripheral</string>
</array>
```

## Frameworks
- FBLPromises.framework
- GoogleUtilities.framework
- GTMSessionFetcher.framework
- nanopb.framework
- PromiseKit.framework
- protobuf.framework
- SnapKit.framework

## (Potential) Bluetooth Beacons Information
```xml
<dict>
	<key>Dev</key>
	<dict>
		<key>Bluetooth</key>
		<dict>
			<key>CENTRAL_SCAN_DURATION</key>
			<integer>10</integer>
			<key>CENTRAL_SCAN_INTERVAL</key>
			<integer>60</integer>
			<key>DATA_EXPIRATION_DAYS</key>
			<string>-21</string>
			<key>ORG_ID</key>
			<string>PL_PGS</string>
			<key>PROTOCOL_VERSION</key>
			<integer>2</integer>
			<key>SERVICE_UUID</key>
			<string>60B772DC-5417-4760-AC10-3E30074C4833</string>
			<key>V2_CHARACTERISTIC_ID</key>
			<string>8FBFDF09-5EB4-4F68-AC16-6CD2275D07CA</string>
		</dict>
		<key>PWA</key>
		<dict>
			<key>HOST</key>
			<string>safesafe-dev.thecoders.io</string>
			<key>SCHEME</key>
			<string>https</string>
		</dict>
	</dict>
	<key>Live</key>
	<dict>
		<key>Bluetooth</key>
		<dict>
			<key>CENTRAL_SCAN_DURATION</key>
			<integer>10</integer>
			<key>CENTRAL_SCAN_INTERVAL</key>
			<integer>60</integer>
			<key>DATA_EXPIRATION_DAYS</key>
			<string>-21</string>
			<key>ORG_ID</key>
			<string>PL_PGS</string>
			<key>PROTOCOL_VERSION</key>
			<integer>2</integer>
			<key>SERVICE_UUID</key>
			<string>6E9E7830-F4C7-4717-B0D8-525D30181121</string>
			<key>V2_CHARACTERISTIC_ID</key>
			<string>8FBFDF09-5EB4-4F68-AC16-6CD2275D07CA</string>
		</dict>
		<key>PWA</key>
		<dict>
			<key>HOST</key>
			<string>safesafe.app</string>
			<key>SCHEME</key>
			<string>https</string>
		</dict>
	</dict>
	<key>Staging</key>
	<dict>
		<key>Bluetooth</key>
		<dict>
			<key>CENTRAL_SCAN_DURATION</key>
			<integer>10</integer>
			<key>CENTRAL_SCAN_INTERVAL</key>
			<integer>60</integer>
			<key>DATA_EXPIRATION_DAYS</key>
			<string>-21</string>
			<key>ORG_ID</key>
			<string>PL_PGS</string>
			<key>PROTOCOL_VERSION</key>
			<integer>2</integer>
			<key>SERVICE_UUID</key>
			<string>60B772DC-5417-4760-AC10-3E30074C4833</string>
			<key>V2_CHARACTERISTIC_ID</key>
			<string>8FBFDF09-5EB4-4F68-AC16-6CD2275D07CA</string>
		</dict>
		<key>PWA</key>
		<dict>
			<key>HOST</key>
			<string>safesafe-stage.thecoders.io</string>
			<key>SCHEME</key>
			<string>https</string>
		</dict>
	</dict>
</dict>
```
