
# react-native-android-play-services-location

## Getting started

`$ npm install react-native-android-play-services-location --save`

### Mostly automatic installation

`$ react-native link react-native-android-play-services-location`

### Manual installation

#### iOS

Not supported.

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.PlayServicesLocation;` to the imports at the top of the file
  - Add `new PlayServicesLocation()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-android-play-services-location'
  	project(':react-native-android-play-services-location').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-android-play-services-location/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-android-play-services-location')
  	```
