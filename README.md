# Karte von morgen - die App
Die App zur Karte von morgen

Available at 

 <a href="https://itunes.apple.com/us/app/karte-von-morgen/id1444338148?l=de&ls=1&mt=8"><img src="/resources/app-store-brands.svg" height=50px></img></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://play.google.com/store/apps/details?id=de.alexreiner.kvm"><img src="/resources/google-play-brands.svg" height=50px></img></a>

written with [IONIC-Framework](https://ionicframework.com/).

License: 

![](/resources/CC-BY-SA_icon.svg.png)


## Installation ##

First you have to install [AndroidStudio](https://developer.android.com/studio/) and [npm](https://nodejs.org/en/). Afterwards set up Ionic and cordova to your global packages.

```
$ npm install -g ionic cordova
```

All packages and plugins should be installed.
Just connect your Android-Phone and build with

```
$ sh createandroid.sh
```
or
```
$ ionic cordova run android
```

## Used Plugins ##

* [Diagnostic](https://ionicframework.com/docs/native/diagnostic/)
* [Network](https://ionicframework.com/docs/native/network/)
* [Background Geolocation](https://ionicframework.com/docs/native/background-geolocation/)
* [Native Geocoder](https://ionicframework.com/docs/native/native-geocoder/)
* [File Transfer](https://ionicframework.com/docs/native/file-transfer/)
* [Location Accuracy](https://ionicframework.com/docs/native/location-accuracy/)
* [Launch Navigator](https://ionicframework.com/docs/native/launch-navigator/)
* [Storage](https://ionicframework.com/docs/storage/)

* sort-by:
```
$ npm install sort-by --save
```

* papaparse:
```
$ npm install papaparse --save
$ npm install @types/papaparse --save
```

* leaflet:
```
$ npm install leaflet --save
```

* jQuery:
```
$ npm install jquery --save
$ npm install @types/jquery
```

## Used Map ##

We are using OpenStreetMap.
