
# Appium Cucumber Mobile Automation

![Appium](https://img.shields.io/badge/Appium-6DB33F?style=for-the-badge&logo=appium&logoColor=white)
![Cucumber](https://img.shields.io/badge/Cucumber-23D96C?style=for-the-badge&logo=cucumber&logoColor=white)
![TestNG](https://img.shields.io/badge/TestNG-FF7300?style=for-the-badge&logo=testng&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)


## Overview
This project automates mobile application testing for **Android platforms** using Appium, Cucumber, and TestNG. The goal is to create a robust, easy-to-maintain, and scalable test suite for mobile applications, with a primary focus on Android, while allowing for easy extension to iOS if needed.

## Project Structure

```
appium-cucumber-mobile-automation/
├── .idea/
├── src/
│   ├── main/
│   └── test/
│       └── java/
│           ├── featureFiles/
│           │   ├── _01_Login.feature
│           │   ├── _02_Swipe.feature
│           │   ├── _03_Forms.feature
│           │   └── _04_DragFeatures.feature
│           ├── pages/
│           │   ├── DragPage.java
│           │   ├── FormsPage.java
│           │   ├── LoginPage.java
│           │   └── SwipePage.java
│           ├── runners/
│           │   └── TestRunner.java
│           ├── stepDefinitions/
│           │   ├── _01_LoginSteps.java
│           │   ├── _02_SwipeSteps.java
│           │   ├── _03_FormsSteps.java
│           │   ├── _04_DragSteps.java
│           │   └── Hooks.java
│           ├── tests/
│           │   └── Tests.java
│           └── utilities/
│               ├── DriverManager.java
│               └── PageActionsHelper.java
├── target/
├── .gitignore
├── LICENSE
├── pom.xml
└── README.md
```

## Features

- Integration with Appium for mobile test automation
- Cucumber for behavior-driven development (BDD)
- TestNG for testing framework
- Support for Android platforms
- Extensible and modular architecture

## Requirements

- Java 11 or higher
- Maven 3.6 or higher
- Appium server
- Android SDK
- Node.js (16.x or higher)

## Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/cihat-kose/appium-cucumber-mobile-automation.git
   cd appium-cucumber-mobile-automation
   ```

2. **Java Installation**
   - Install Java JDK 11 or later.
   - Set JAVA_HOME and PATH environment variables.

3. **Maven Installation**
   - Download and install Maven from [here](https://maven.apache.org/download.cgi).
   - Set MAVEN_HOME and PATH environment variables.

4. **Android SDK Installation**
   - Install Android Studio and configure the Android SDK.
   - Set ANDROID_HOME and PATH environment variables.

5. **Appium Server Installation**
   - Download and install Appium Desktop from [here](https://github.com/appium/appium-desktop/releases).
   - Start Appium.

6. **Loading Project Dependencies**
   - Navigate to the root directory of your project in the terminal or command line.
   - Run the following command to load the Maven dependencies:
     ```sh
     mvn clean install
     ```

## Running Tests

1. **Starting Appium Server**
   - Start the Appium server using Appium Desktop or via terminal.

2. **Starting Android Emulator or Real Device**
   - Start an Android emulator or connect a real device via USB.

3. To execute the tests, use the following command:
   ```sh
   mvn test
   ```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please open an issue or contact the repository owner.
