# Detox: End-toEnd Mobile UI Automation

This repo is a designed for UI automation of react-native project using Grey box testing.

As you may have known, the major problems in the mobile UI testing are slowness and flakiness. The tools like Appium are completely black-box and uses client-server architecture which causes flakiness in the UI tests. Detox is designed to solve the problem of slowness and flakiness for mobile UI testing. Some of Detox’s great features are as follows

* Detox monitors the asynchronous operations in the app to reduce the flakiness of finding the async elements in the app UI.
* Detox is a grey-box testing tool so it can access the code and data from your mobile apps. It’s an in-process tool and doesn’t use client-server architecture for test execution so it’s way faster than Appium or other third-party mobile test automation frameworks.
* Detox is easy to be connected to any CI systems and popular cloud testing services.
* Detox is awesome for fast feedback on your E2E testing which doesn’t need the connection to real devices.
* React Native developers would love Detox as it’s faster, debuggable and can be used with any test runner like Jest or Mocha.


## Pros and Cons of Detox for UI Testing ##
### Detox Pro ###
* Detox is highly debuggable than any other third-party UI test automation.
* Detox can be integrated easily in any React Native app. The initial cost and efforts are much less than any other tools.
* Detox is way faster than Appium or any other third-party tool as it syncs with the app.
* Detox is easy to learn and has great API documentation to write and extend our test suite.
* Community is growing fast.

### Detox Cons ###
* Android support is not great but it’s improving
* Web Views and Hybrid apps are not supported.
* Few useful methods are missing like getting the text out of element or finding the coordinates.
* Test reporting and screenshot ability aren’t great. But with the integration of TestNG it can be handled
