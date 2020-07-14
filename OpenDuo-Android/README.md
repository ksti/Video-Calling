# Open Video Call for Android

*English | [中文](README.zh.md)*

This readme describes the steps and considerations for demonstrating the Agora OpenDuo Android sample app.

## Introduction

Built upon the Agora Video SDK and the Agora RTM SDK, the Agora OpenDuo for iOS is an open-source demo that integrates 1 to 1 video call into your Android applications.

This sample app allows you to:

- Login the RTM server
- Make a call
- Accept or hang up a call
- Mute/unmute a user
- Switch the camera

## Prerequisites

- Android Studio 3.3 or above
- Real devices (Nexus 5X or other devices)
- Some simulators are function missing or have performance issue, so real device is the best choice

## Quick Start

This section shows you how to prepare, build, and run the sample application.

### Obtain an App ID

To build and run the sample application, get an App ID:
1. Create a developer account at [agora.io](https://dashboard.agora.io/signin/). Once you finish the signup process, you will be redirected to the Dashboard.
2. Navigate in the Dashboard tree on the left to **Projects** > **Project List**.
3. Save the **App ID** from the Dashboard for later use.
4. Generate a temp **Access Token** (valid for 24 hours) from dashboard page with given channel name, save for later use.

5. Update "app/src/main/res/values/strings_config.xml" with your App ID and Token.
```
<string name="private_app_id"><#YOUR APP ID#></string>
<!-- Please leave it if not enable App Certificate -->
<!-- You can generate a temporary token at https://dashboard.agora.io/projects -->
<string name="agora_access_token"><#YOUR TOKEN#></string>
```

### Integrate the Agora Video SDK

The SDK will be automatically installed via gradle when the project is opened with Android Studio.

    

### Run the Application

Connect your Android device, build and run.
      
Or use `Gradle` to build and run.


## Contact Us

- For potential issues, take a look at our [FAQ](https://docs.agora.io/en/faq) first
- Dive into [Agora SDK Samples](https://github.com/AgoraIO) to see more tutorials
- Take a look at [Agora Use Case](https://github.com/AgoraIO-usecase) for more complicated real use case
- Repositories managed by developer communities can be found at [Agora Community](https://github.com/AgoraIO-Community)
- You can find full API documentation at [Document Center](https://docs.agora.io/en/)
- If you encounter problems during integration, you can ask question in [Stack Overflow](https://stackoverflow.com/questions/tagged/agora.io)
- You can file bugs about this sample at [issue](https://github.com/AgoraIO-Usecase/Video-Calling/issues)

## License

The MIT License (MIT)