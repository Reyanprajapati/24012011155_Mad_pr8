# 24012011155_Mad_pr8

Practical 8 - Mobile Application Development
Submitted By: Reyan Prajapati
Enrollment Number: 24012011155
Department: Computer Engineering / Information Technology
Practical: 8
Aim
To create and run a basic iOS application named hello world using Swift and SwiftUI in Xcode.
Objectives
- Create a new iOS App project in Xcode.
- Use SwiftUI to build the user interface and Swift as the programming language.
- Understand the structure of a basic SwiftUI app.
- Run the app in an iOS simulator and preview the interface in Xcode.
- Create a Git repository for the project.
Project Setup
When creating the project in Xcode, use these settings:
- Template: App (under the iOS tab)
- Product Name: hello world
- Interface: SwiftUI
- Language: Swift
- Core Data: Not selected
- Unit Tests: Not selected
- Git Repository: Select Create Git repository on my Mac
App Structure
The practical introduces two main source files:
File	Purpose
hello_worldApp.swift	Defines the app entry point using @main and loads ContentView() inside a WindowGroup.
ContentView.swift	Defines the main screen and displays the text Hello, world! with padding.


Main Code Concepts
hello_worldApp.swift
The app entry point uses SwiftUI's App protocol and presents ContentView in a window group.
ContentView.swift
The main view conforms to View and displays a Text("Hello, world!") view with .padding().
How to Run
1. Open the hello world project in Xcode.
2. Choose an iOS simulator from the run destination menu at the top of the project window.
3. Press the Run (play) button.
4. Wait for Xcode to build the project and launch the app in the selected simulator.
5. To preview the interface without launching the simulator, open ContentView.swift and use the SwiftUI preview. Press Resume in the preview pane if needed.
Technologies Used
- Xcode
- Swift
- SwiftUI
- iOS Simulator
- Git
Expected Output
The app launches in the simulator and displays Hello, world! on the screen. The SwiftUI preview can also show the view and reflect code changes.
Author
Reyan Prajapati
Enrollment Number: 24012011155
