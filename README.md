# Vanced MicroG

[![Build Status](https://api.travis-ci.com/YTVanced/VancedMicroG.svg?branch=master)](https://travis-ci.com/github/YTVanced/VancedMicroG)
[![Github All Releases](https://img.shields.io/github/downloads/YTVanced/VancedMicroG/total.svg)]() [![Github All Releases](https://img.shields.io/github/release/YTVanced/VancedMicroG.svg)]() 

microG GmsCore is a FLOSS (Free/Libre Open Source Software) framework to allow applications designed for Google Play Services to run on systems, where Play Services is not available.

This fork tweaks MicroG to be usable by applications that require Google authentication such as Youtube Vanced.

## Notable changes

- No longer a system app
- Package name changed from `com.google.android.gms` to `com.mgoogle.android.gms` to support installation alongside the official MicroG
- Removed unnecessary features:
  - Maps & Location
  - Wear-Api
  - Safetynet
  - Games
  - Car
- Removed all permissions, as none are required for Google authentication
