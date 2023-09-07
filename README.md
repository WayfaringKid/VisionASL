# VisionASL - Vision Pro ASL Accessibility Suite

## Introduction

The **VisionASL** aims to bridge communication gaps for the deaf and hard-of-hearing community by leveraging Apple's VisionOS and Vision Pro Mixed Reality headset. The suite will utilize advanced computer vision and natural language processing technologies to enable seamless translation between American Sign Language (ASL) and spoken English.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Contribute](#contribute)
- [License](#license)
- [Contact](#contact)

## Features

### ASL to Text

- **Computer Vision Model**: Recognizes and interprets American Sign Language gestures.
- **Real-time Display**: A SwiftUI view to display the interpreted text in real-time.

### Spoken Language to ASL & Text

- **Speech-to-Text**: Converts spoken language to text.
- **Text to ASL Translation**: Translates text to ASL gestures displayed through 3D models or animations.
- **Real-time Text Display**: Another SwiftUI view to display the text interpretation of spoken language.

### Additional Accessibility Features

- **Spatial Haptic Feedback**: For XR/VR environments, spatial haptic feedback to guide users through spaces.
- **Auditory Alerts**: Different tones or vibrations for different types of notifications.
  
## Technology Stack

- **Swift**: Business logic and data management.
- **SwiftUI**: User interface.
- **Core ML**: Machine learning for gesture recognition.
- **AVFoundation**: Audio processing for speech-to-text.
- **Xcode**: Development, debugging, and profiling.

## dev notes
- shared space in visionOS across different headset - everyone see same translation
- noticing user proper speed of asl while translating
