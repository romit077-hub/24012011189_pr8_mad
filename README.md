# MAD Practical 8 – Creating a Basic iOS Application Using SwiftUI

## Student Details

- **Name:** Romit Trivedi
- **Enrollment Number:** 24012011189
- **Batch:** CE_I_2
- **Subject:** Mobile Application Development (MAD)
- **Practical Number:** 8

## Aim

To create a basic iOS application using Xcode and SwiftUI, understand the structure of a SwiftUI application, and run the application using the iOS Simulator.

## Software Requirements

- Xcode
- macOS
- Swift programming language
- SwiftUI framework
- iOS Simulator

## Practical Description

This practical demonstrates the process of creating and running a basic Hello World iOS application using SwiftUI.

### 1. Creating a New iOS Project

1. Open Xcode.
2. Select **File → New → Project**.
3. Choose the **App** template under the iOS section.
4. Set the application name to `hello_world`.
5. Select SwiftUI as the interface technology.
6. Select Swift as the programming language.
7. Keep Core Data and Unit Testing options disabled.
8. Enable the option to create a Git repository on the Mac.
9. Save the project.

### 2. Understanding the SwiftUI Application Structure

A basic SwiftUI application contains two important source files:

- **hello_worldApp.swift:** Defines the main entry point of the application and creates the main application scene.
- **ContentView.swift:** Defines the user interface displayed by the application.

The `ContentView` structure conforms to the SwiftUI `View` protocol and uses the `body` property to describe the user interface.

The application uses a `Text` view to display the Hello World message.

### 3. Running the Application in iOS Simulator

1. Open the project in Xcode.
2. Select an available iOS Simulator device.
3. Click the Run (Play) button in the Xcode toolbar.
4. Wait for the project to build.
5. The application launches in the selected simulator.

### 4. Understanding SwiftUI Preview

SwiftUI provides a preview feature that allows developers to view changes to the user interface without manually running the application every time.

The preview is available in `ContentView.swift`. Pressing Resume refreshes the preview and displays the latest interface changes.

## Expected Output

A basic iOS application successfully runs in the iOS Simulator and displays:

**Hello, world!**

The SwiftUI preview also displays the same interface.

## Learning Outcomes

- Learned how to create a new iOS project using Xcode.
- Understood the basics of Swift and SwiftUI.
- Learned the structure of a basic SwiftUI application.
- Understood the role of the App and View structures.
- Learned how to run an application using the iOS Simulator.
- Understood how to use SwiftUI Preview.

## Conclusion

Successfully created and executed a basic Hello World iOS application using Xcode and SwiftUI. Also understood the fundamental structure of an iOS application and learned how to use the iOS Simulator and SwiftUI Preview.
