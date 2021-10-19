# Pivo Pro SDK

Pivo Pro SDK is an iOS Framework which can be used to:
- Connect with Pivo
- Control Pivo
- Tracking with Pivo

For more information about Pivo [getpivo.com](getpivo.com)

For more information of the SDK and contact to get license to use the SDK: https://developer.pivo.app/

Test app located at: https://github.com/pivo-inc/pivo-pro-sdk-testapp-ios

## Changelogs

In version 0.0.8:
- Change class name from `PivoProSDK` to `PivoSDK` to prevent an error
- Support new Pivo types
- Build with Swift 5.5
- In order to get `Rotated` feedback when rotates Pivo, please make sure to use `turnLeftWithFeedback` and `turnRightWithFeedback` with speed from `getSupportedSpeedsByRemoteControllerInSecoundsPerRound`
