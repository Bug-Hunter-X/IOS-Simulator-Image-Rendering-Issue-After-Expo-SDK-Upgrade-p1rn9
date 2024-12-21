# iOS Simulator Image Rendering Issue

This repository demonstrates an uncommon bug encountered after upgrading the Expo SDK. Images fail to render in the iOS simulator, while other components display correctly.  The issue is specific to iOS and doesn't occur on Android.

## Bug Description

Following an Expo SDK upgrade, images within my React Native application stopped rendering in the iOS simulator. Other UI components, including text and custom components, function without issues.  This problem only manifests in the iOS simulator; images render correctly on a physical iOS device and on the Android simulator.

## Steps to Reproduce

1. Clone this repository.
2. Run `expo start`.
3. Observe the application in the iOS simulator.
4. Note that the image (if included) does not render.

## Expected Behavior

The image should render correctly in the iOS simulator, as it does on physical devices and the Android simulator.

## Actual Behavior

The image does not render in the iOS simulator.  Other components display as expected.

## Environment

* Expo SDK version: [Insert your Expo SDK version]
* React Native version: [Insert your React Native version]
* iOS Simulator version: [Insert your iOS Simulator version]

## Solution

The solution, included in this repo, might involve reviewing the image source path, ensuring the image is correctly included in the project, checking for any conflicting libraries, or attempting a clean build and cache clear.  The 'App.js' file shows the corrected code and the provided solution.