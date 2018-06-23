# Chime App

## About the App

We developed a new app to generate, consume, manage and share the WCAP URIs as described above. The app is simple, usable and beautiful, and meant to be a persistent, passive helper for the user running it on their smartphone. Users can share and synchronize their Chime links with each other, to let eachother know where they can find off-grid services in the physical world. The app tells a user which Chimes are available nearby, and how far away the rest are. It also actively notifies a user when they come nearby a Chime, and allows them to automatically connect to it, and perform any automated actions like data syncing or uploading.

## Release

This app is currently only in prototype phase. You can find prototype dev builds posted on the Release page: https://github.com/guardianproject/chimeapp/releases

## Chime Protocol 

The most critical step in an off-grid system is finding nodes, peers and services to connect with. To do this, we first conceived of a new URI format that we call the “Wind Chime Announce Protocol” (WCAP). WCAP links provide information about physical location, time windows, connectivity information (ssid, bssid), available services, and more. Here is an example for a 

wcap:BrooklineLibrary?name=brookelinelibrary&lat=135.2&lon=35.4&begin=0000-00-00T03:00:00Z&end=0000-00-00T05:59:59Z&ssid=librarybox.lan&bssid=24:a4:3c:9e:d2:84&serviceType=fdroid&servicePackage=org.fdroid.fdroid&serviceUri=http%3A%2F%2F192.168.1.1%2Ffdroid%2Frepo%3Ffingerprint%3DB7C2EEFD8DAC7806AF67DFCD92EB18126BC08312A7F2D6F3862E46013C7A6135

These links can be shared through a variety of broadcast mechanisms, including QR codes, Bluetooth, SMS text message, WifiDirect Discovery, SSIDs, and Beacons / AltBeacons. 
