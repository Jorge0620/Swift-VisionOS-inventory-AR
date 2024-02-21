# Mobile Swift VisionOS Inventory Tracker

AR Realtime Inventory Tracker/Scanner visionOS & iOS App built with seamless Augmented Reality Integration

## Requirements
- Xcode 15 (At least Beta 8)
- iOS 17
- Replace the bundleID for the App with your own.
- Firebase iOS & visionOS Project, download `GoogleService-info.plist` to your Xcode project target.
- As per Firebase SDK 10.14.0, you need to pass `open --env FIREBASE_SOURCE_FIRESTORE /path/to/project.xcodeproj` to be able to build on visionOS target

## Key features of this app
- Leveraging Swift UI and RealityKit to build the user interface and display 3D content, animations, and visual effects within the app
- Utilizing ARKit to provide the app with an understanding of the real-world space around the user, enabling the placement of virtual objects on horizontal and vertical surfaces
- Firestore inventory item synchronization
- Spatial Sound Integration
- Image scan AR functionality
- Upload files to firestore storage
- Developing the app to support the new hardware and full-space paradigm introduced by VisionOS, ensuring compatibility with the latest advancements in AR technology
- Quicklook preview
- SwiftUI 3D model display