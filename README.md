# practice-react-native
Test app for practice

To set up React Native in Visual Studio Code (VS Code), follow these steps:

1. Install Node.js

2. Install React Native CLI
   > npm install -g react-native-cli

3. Install Android Studio (for Android development)
    Set up Android environment variables:
      >  export ANDROID_HOME=$HOME/Library/Android/sdk
      >  export PATH=$PATH:$ANDROID_HOME/emulator
      >  export PATH=$PATH:$ANDROID_HOME/platform-tools
      >  export PATH=$PATH:$ANDROID_HOME/tools

4. Install Xcode (for iOS development, macOS only)
    After installing, run the following command to install Xcode command line tools:
       > xcode-select --install

5. Install Expo CLI (optional)
    > npm install -g expo-cli
    > create a new project using Expo:
        >> expo init MyNewProject
        >> cd MyNewProject
        >> expo start

6. Install VS Code and Extensions
    > React Native Tools (for debugging and IntelliSense support)
    > ESLint (for linting)
    > Prettier (for code formatting)

7. Create a New React Native Project
    > npx react-native init MyProject
    > cd MyProject

8. Run the Project
    > For Android: 
        >> npx react-native run-android
    > For iOS (macOS only): 
        >> npx react-native run-ios
