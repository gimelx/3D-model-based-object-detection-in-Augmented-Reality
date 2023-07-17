# ARKit-based Application for iOS (Application Name)

This application is an implementation of 3D model-based object detection using Apple's ARKit. It was developed in Xcode and uses object scans generated from the ARScanning App for object detection.

## Features

- 3D model-based object detection using scanned objects from ARScanning app.

## Requirements

- iOS
- Xcode
- ARScanning app (https://developer.apple.com/documentation/arkit/arkit_in_ios/content_anchors/scanning_and_detecting_3d_objects) for object scanning

## Installation

1. Clone this repository.
2. Open Xcode and navigate to the repository location.
3. Connect your iOS device and select it as the build destination.
4. Click 'Run' to install the application on your device.

## Usage

1. Use the ARScanning app to scan the objects you want to detect. 
2. Store the scan outputs in the resource folder of this application. 
3. Run the application. It will detect the objects based on the scans and display the name of the scan when the object is detected.

---



# Vuforia Engine and Unity Application (Application Name)

This application leverages the Vuforia Engine integrated with Unity to create immersive AR experiences. It uses the Model Target feature of Vuforia for 3D object detection.

## Features

- 3D model-based object detection using Vuforia's Model Target feature.

## Requirements

- Unity 
- Vuforia Engine version requirement (Set up instructions: [Vuforia Engine in Unity](https://library.vuforia.com/getting-started/getting-started-vuforia-engine-unity))
- Model Target Generator ([User Guide](https://library.vuforia.com/objects/model-target-generator-user-guide))

## Installation

1. Clone this repository.
2. Open Unity and navigate to the repository location.
3. Follow the setup instructions to integrate the Vuforia Engine with your Unity project.

## Usage

1. Use the Model Target Generator to create your model target and export it to Unity.
2. In Unity, add the provided controller script to the model target.
3. According to the script, add several buttons and textfields as shown in the provided image.
4. Set the build settings in Unity:
    - Target platform: Android
    - Minimum API level: 28
    - Scripting backend: IL2CPP
    - API compatibility level: .NET Standard
    - Architecture: ARM64
5. Connect your Android device, select it as the build destination, then click 'Build and Run' to install the application on your device.

---



## Contributing

If you wish to contribute, please feel free to fork the repository, make your changes, and submit a pull request.

## License

Provide information about your license.

## Contact

Your Name – Your Email – Your Twitter handle, etc.

Please feel free to leave any comments or issues on the GitHub page.

