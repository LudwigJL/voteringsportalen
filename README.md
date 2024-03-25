# VoteringsPortalen: Mobile application
# Project Overview

This mobile application aims to enhance political transparency in Sweden's Riksdag. Our idea stemmed from the observation that very few Swedish citizens are aware of their party's voting records in the Riksdag, often leading to uncertainty about whether their chosen party's actions align with their beliefs. We simply asked ourselves: Does the average Swedish citizen truly understand what is happening in the Swedish Riksdag? The answer was no; staying updated required too much effort.

As a solution, we developed a user-friendly mobile application where users can quickly access relevant Riksdag votes. Here, users can gain insights into the parties' stances on specific political questions and see if the parties are keeping their political promises. Furthermore, we have added more functions such as providing data about specific members (ledamöter) such as their attendance rates and their yes/no voting ratings compared to their party.

By providing a clear, user-friendly view of what's happening in our Riksdag, we hope that our app empowers users to become more politically informed citizens.

## Our Data
All data within our application is directly gathered from Riksdagen's open APIs.

## Installation

1. Clone the repository: `git clone https://github.com/LudwigJL/voteringsportalen`
2. Navigate to the project directory: `cd voteringsportalen`
3. Set up flutter in Visual Studio Code:
For detailed instructions on installing Flutter and setting up your development environment, please refer to the official [Flutter Installation Guide](https://flutter.dev/docs/get-started/install).

## Running the Application

For optimal testing and development, it is recommended to execute the application within a chosen Simulator or Emulator. This ensures a comprehensive evaluation of the application's functionality in a controlled environment.

To initiate the application:

1. **Open the Project in Visual Studio Code:**
   - Launch Visual Studio Code.
   - Open the project by navigating to the project directory.

2. **Prepare Simulator or Emulator:**
   - Launch your preferred Simulator or Emulator.
   - Ensure the device is connected; you can verify this in the bottom right corner of Visual Studio Code.

3. **Run the Application:**
   - In Visual Studio Code, either:
     - Click the "Run" button.
     - Or, run the following command in the terminal:

   ```bash
   flutter run

# Installing the Application on a Physical Device

After successfully running the application in a Simulator or Emulator, you may want to install it on a physical device for real-world testing. Follow these steps:

1. **Build the Application:**
   - Open a terminal in Visual Studio Code.
   - Run the following command to build the application:

   ```bash
   flutter build apk  # For Android
   # or
   flutter build ios  # For iOS
   ```

   This command generates the necessary build files for your target platform.

2. **Connect Your Device:**
   - Ensure your physical device is connected to your computer via USB.

3. **Check Device Connection in Visual Studio Code:**
   - Look for your connected device in the bottom right corner of Visual Studio Code. You should see the device name.

4. **Install the Application:**
   - Run the following command to install the application on your connected device:

   ```bash
   flutter install
   ```

   This will install the application on your connected device.

Now, you can launch the application directly from your device and conduct real-world testing.

For additional information and troubleshooting, refer to the [Flutter documentation](https://flutter.dev/docs/get-started/install) or your platform-specific guidelines.
`
