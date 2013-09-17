#TCGoogleMaps

This sample project shows how we can use **Google Maps SDK for iOS**, **Google Places API**  and **Google Directions API** to build a simple navigation app.

<br>
*Search autocomplete with results sorted based on distance from your current location and relevance.*

<img src="README-Images/Screenshot1.png" alt="Google Places Autocomplete" title="Google Places Autocomplete">

<br>
*Selecting a search result will give you the directions from your location to the selected destination.*  

<img src="README-Images/Screenshot2.png" alt="Google Maps Directions" title="Google Maps Directions">

<br>
*Tapping on the list icon will bring up turn-by-turn directions.*

<img src="README-Images/Screenshot3.png" alt="Turn-by-Turn Directions" title="Turn-by-Turn Directions">

<br>
*Selecting a step from the list will zoom in on that specific step on the map.*

<img src="README-Images/Screenshot4.png" alt="Step-by-Step Directions on Map" title="Step-by-Step Directions on Map">

<br>
###How to Build and Run
<dl>
  <dt>Build Requirements</dt>
  <dd>Xcode 4.6 or later, iOS 6.0 SDK or later, CocoaPods</dd>
  <dt>Runtime Requirements</dt>
  <dd>iOS 6.0 or later</dd>
</dl>

####Step 1: Download and Install CocoaPods

Follow the simple installation guide from <http://cocoapods.org/>.

####Step 2: Install Library Dependencies

Run the following commands in Terminal.app:  
```
$ cd <PROJECT_DIRECTORY>
$ pod install  
$ open TCGoogleMaps.xcworkspace
```

####Step 3: Generate your API Keys

1. Go to [Google API Console](https://code.google.com/apis/console/) and generate your API key.
2. In Xcode, open `TCGoogleMaps\App\TCGoogleAPIKeys.m` and replace with your own API key:
  
  ```Objective-C
  NSString * const kTCGoogleMapsAPIKey = @"YOUR-API-KEY";
  NSString * const kTCGooglePlacesAPIKey = @"YOUR-API-KEY";
  ```

###Open Source Libraries Used
* AFNetworking - <https://github.com/AFNetworking/AFNetworking>
* MBProgressHUD - <https://github.com/jdg/MBProgressHUD>

###See Also
* Google Maps SDK for iOS - <https://developers.google.com/maps/documentation/ios/>
* Google Places API - <https://developers.google.com/places/>
* Google Directions API - <https://developers.google.com/maps/documentation/directions/>

###License
This project's source code is provided for educational purposes only. Image resources are based on the icons used in Google Maps. See the LICENSE file for more info.