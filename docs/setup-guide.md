# BomberMan Environment Setup and Run Guide

## 1. Environment Requirements
- **Java JDK**: 17 (Eclipse Temurin 17.0.21+)
- **Build Tool**: Gradle Wrapper (included in the project)
- **Operating System**: Windows (Verified)

## 2. Build and Run Instructions
1. Clone the repository:
   `git clone https://github.com/Mo001001/BomberMan.git`
2. Navigate to the inner project directory:
   `cd BomberMan/BomberMan`
3. Compile the project and run tests:
   `.\gradlew.bat build`
   *(Verification Result: BUILD SUCCESSFUL)*
4. Launch the game:
   `.\gradlew.bat run`
   *(Alternatively, double-click the generated `.jar` file in the `build/libs/` directory)*

## 3. Troubleshooting
- **Warning: "unmappable character for encoding GBK"**: This is caused by original Italian comments in the source code on Windows systems. It is just a warning and does not affect the compilation process.
- **Error: Java not found**: Please ensure your `JAVA_HOME` system environment variable is pointing to JDK 17.