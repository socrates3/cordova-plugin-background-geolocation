AbstractLocationService.java --> //startForeground(startId, notification);   //stopForeground(true);
OLD: DistanceFilterLocationService.java --> //stopForeground(true);
OLD: FusedLocationService.java --> //stopForeground(true);

example/SampleApp/scripts/install_plugins.js --> "cordova-plugin-socrates3-background-geolocation"

# cordova-plugin-socrates3-background-geolocation
==============================

Fork notice
==============================

This is fork of [mauron85 cordova-backgroud-geolocation](https://github.com/mauron85/cordova-plugin-background-geolocation). Changes are made to avoid Foreground Android service, and to try to reduce battery-usage.
