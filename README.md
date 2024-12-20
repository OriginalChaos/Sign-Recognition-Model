# Sign-Recognition-Model

## Overview

This project aims to develop a **sign recognition model** using neural networks and TensorFlow. The system is designed to detect, classify, and interpret hand signs in real time, with applications in accessibility tools, assistive technologies, and communication aids. By leveraging TensorFlow for model training and TensorFlow.js for web-based integration, this project enables seamless and inclusive interaction between users and devices.

## Features

- **Real-Time Sign Recognition**: Detects and interprets predefined hand signs with real-time processing.
- **Accessible Interaction**: Enables individuals with disabilities to control devices and software through sign language gestures.
- **Customizable Signs**: Users can create and train the system to recognize personalized signs for specific commands.
- **Cross-Platform Compatibility**: Works across mobile and web platforms using **Flutter** and **TensorFlow.js**.

## Tech Stack

- **Programming Languages**:
  - Python (for model development)
  - Dart (for mobile app development using Flutter)
  - JavaScript (for web interface with TensorFlow.js)

- **Frameworks and Libraries**:
  - **TensorFlow/Keras** (for neural network training)
  - **Angular** (for web development)

- **APIs and Tools**:
  - **Firebase Authentication and Realtime Database** (for user management and secure data storage)
  - **Google Cloud Platform** (for scalable backend hosting)
  - **TensorFlow.js** (for web-based gesture recognition)

- **Development Platforms**:
  - **Flutter** (for creating cross-platform mobile applications)

## Installation

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Node.js and npm (for TensorFlow.js)
- Flutter
- Firebase CLI (if using Firebase)
- Google Cloud SDK (if deploying to Google Cloud)

### Clone the Repository

```bash
git clone https://github.com/OriginalChaos/Sign-Recognition-Model.git
```

### Setting up the Backend

1. Install the required Python libraries:

```bash
pip install -r requirements.txt
```

2. Set up **Google Cloud Platform** for backend hosting.

3. Configure **Firebase** for authentication and Realtime Database.

### Setting up the Mobile App (Flutter)

1. Install Flutter SDK from [Flutter's official site](https://flutter.dev/docs/get-started/install).

2. Navigate to the Flutter folder:

```bash
cd mobile_app
```

3. Run the app:

```bash
flutter run
```

### Setting up the Web App (TensorFlow.js)

1. Install the required Node.js dependencies:

```bash
cd web_app
npm install
```

2. Start the web app:

```bash
npm start
```

## Usage

- **Mobile App**: Launch the app on your mobile device to start tracking and recognizing hand signs in real-time.
- **Web App**: Access the web platform to test gesture recognition using TensorFlow.js in the browser.

## Contributing

If you'd like to contribute to the project, feel free to fork the repository, submit issues, or send pull requests.
