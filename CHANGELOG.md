# Cordova Plugin Release Notes

## Cordova Plugin 5.3.1-3.3.1
Release Date: 24.11.2016

#### New
- Includes Wikitude SDK 5.3.1: detailed changelog for <a href="http://www.wikitude.com/external/doc/documentation/latest/android/changelog.html" target="_top">Android</a> and <a href="http://www.wikitude.com/external/doc/documentation/latest/ios/changelog.html" target="_top">iOS</a>

#### Fixed
- Fixes an issue for Android where the keyboard was not showing up again after entering and returning from an ARView


## Cordova Plugin 5.3.0-3.3.1
Release Date: 13.09.2016

#### New
- Includes Wikitude SDK 5.3.0: detailed changelog for <a href="http://www.wikitude.com/external/doc/documentation/latest/android/changelog.html" target="_top">Android</a> and <a href="http://www.wikitude.com/external/doc/documentation/latest/ios/changelog.html" target="_top">iOS</a>

#### Fixed
- Missing Android permission check in demo sample app


## Cordova Plugin 5.2.0-3.3.1
Release Date: 22.07.2016

#### Fixed
- Corrected version number in `plugin.xml` file
- Updated way how to handle files for Cordova Dev app


## Cordova Plugin 5.2.0-3.3.0
Release Date: 08.07.2016

#### New
- You can now use the `cordova.file` API when loading Architect Worlds
- Android only: New `backButtonCallback` that is called when the Wikitude Plugin is closed because of a press on the back button
- Includes Wikitude SDK 5.2.0: detailed changelog for <a href="http://www.wikitude.com/external/doc/documentation/latest/android/changelog.html" target="_top">Android</a> and <a href="http://www.wikitude.com/external/doc/documentation/latest/ios/changelog.html" target="_top">iOS</a>


## Cordova Plugin 5.1.4-3.2.1
Release Date: 15.03.2016

- Includes Wikitude SDK 5.1.4: detailed changelog for <a href="http://www.wikitude.com/developer/documentation/android" target="_top">Android</a> and <a href="http://www.wikitude.com/developer/documentation/ios" target="_top">iOS</a>


## Cordova Plugin 5.1.3-3.2.1
Release Date: 08.03.2016

- Includes Wikitude SDK 5.1.3: detailed changelog for <a href="http://www.wikitude.com/developer/documentation/android" target="_top">Android</a> and <a href="http://www.wikitude.com/developer/documentation/ios" target="_top">iOS</a>


## Cordova Plugin 5.1.1-3.2.0
Release Date: 15.01.2016

Fixed:
- Missing textures on certain 3D models

Improved
- Wikitude Sample App now implements Android Runtime Permissions (applies to Android 6.0 - API level 23)

Wikitude SDK 5.1.0

New

- Support for Android switched camera on Nexus 5X
- Support multiple regional co-located cloud recognition services
- 3D model import: account for pivot node transformations

Fixed

- 3D model import:
- Animation grouping
- Account for animation stack (numbering of animations if more than one animation tracks are on the FBX animation stack)
- Accept the first texture of a multi-textured 3d model
- Accept 3d models with more than one mesh skins per node


## Cordova Plugin 5.0.0-3.1.0
Release Date: 06.05.15

New:
- This release includes the Wikitude SDK 5.0.0.


## Cordova Plugin 4.1.0-3.1.0
Release Date: 06.05.15

New:

- Compatibility for Cordova 5.0.0 and especially Android 4.0.0
- Updates Setup Guide to reflect new StartupConfiguration

## Cordova Plugin 4.1.0-3.0.1
Release Date: 01.04.15
#### Fixes
- Fixes a potential problem when camera access is denied and no error handler is set in the JS host application.
- Fixes a problem with device supported check where 2dtracking - only experiences still would require compass to be supported

## Cordova Plugin 4.1.0-3.0.0
Release Date: 09.03.15
#### New
- Integrates Wikitude SDK 4.1.0 for Android and iOS (see detailed release notes for <a href="http://www.wikitude.com/developer/documentation/android" target="_top">Android</a> and <a href="http://www.wikitude.com/developer/documentation/ios" target="_top">iOS</a>)
- Updated API (see <a href="http://www.wikitude.com/external/doc/documentation/latest/phonegap/migration.html" target="_top">Migration Guide for details</a>)


## PhoneGap Plugin 4.0.0-2.1.0 
Release Date: 29.07.14

#### New
- Integrates Wikitude SDK 4.0.0 for Android and iOS (see detailed release notes for <a href="http://www.wikitude.com/developer/documentation/android" target="_top">Android</a> and <a href="http://www.wikitude.com/developer/documentation/ios" target="_top">iOS</a>)
- Compatible with PhoneGap 3.5

## PhoneGap Plugin 3.3.1-2.0.1 
Release Date 24.04.2014

#### New
- Wikitude SDK 3.3.1 for Android and iOS
- `IRandGeo` mode available instead of `Both` in plugin

## PhoneGap Plugin 3.3.0-2.0.0 
Release Date 01.04.2014

#### New
- Wikitude SDK 3.3.0 for Android and iOS
- Support for PhoneGap 3.4.0

#### Fixed
- Back-button behavior for Android 4.4
- Focus issue on Android

#### Improved
- Extended set-up guide 

