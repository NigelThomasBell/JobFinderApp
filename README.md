# Job Finder App
![React Native Job Finder App Project Image](/_readme_images/ReactNativeJobs.png "React Native Job Finder App Project Image Project Image")
## Table of Contents
1. [Introduction](#introduction)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Quick Start](#quick-start)
5. [References](#references)

## <a name="introduction">Introduction</a>
This project provided hands-on experience in React Native development, starting with understanding the basics and resulting in the creation of a feature-rich app. There is also a focus on UI/UX, external data integration, and best practices.

## <a name="tech-stack">Tech Stack</a>
- Node.js
- React Native
- React Native StyleSheet
- Expo
- Axios
- TypeScript
- APIs
    - JSearch (from RapidAPI)

## <a name="features">Features</a>
- **Visually Appealing UI/UX Design**: Develop an aesthetically pleasing user interface using React Native components.
- **Third Party API Integration**: Fetch data from an external API and seamlessly integrate it into the app.
- **Search & Pagination Functionality**: Implement search functionality and pagination for efficient data navigation.
- **Custom API Data Fetching Hooks**: Create custom hooks for streamlined and reusable API data fetching.
- **Dynamic Home Page**: Explore diverse jobs from popular and nearby locations across different categories.
- **Browse with Ease on Explore Page**: Page: Navigate through various jobs spanning different categories and types.
- **Detailed Job Insights**: View comprehensive job details, including application links, salary info, responsibilities, and qualifications.
- **Tailored Job Exploration**: Find jobs specific to a particular title 
- **Robust Loading and Error Management**: Ensure effective handling of loading processes and error scenarios. 
- **Optimized for All Devices**: A responsive design for a seamless user experience across various devices.
- many more, including code architecture and reusability.

## <a name="quick-start">Quick Start</a>
### Prerequisites
Ensure you have the following installed on your machine:
- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm (Node Package Manager)](https://www.npmjs.com/)
- [Expo Go](https://expo.dev/client)
- (Optional) [Android Studio](https://developer.android.com/studio)

### Cloning the Repository
```bash
git clone https://github.com/NigelThomasBell/JobFinderApp.git
cd JobFinderApp
```

### Installation
Install the project dependencies using npm:
```bash
npm install
```

### Set Up Environment Variables
Create a new file named `.env` in the root of your project and add the following content with your own keys:
```env
RAPID_API_KEY=
```
Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on the [RapidAPI website](https://rapidapi.com/letscrape-6bRBa3QguO5/api/jsearch). Make sure that you subscribe to the API before trying to use it.

### Running the Project
* Android:
    * Real Device:
        * General:
            ```bash
            npx expo start
            ```
        * Tunnel (if general does not work with your device/network):
            ```bash
            npx expo start --tunnel
            ```
    * Emulated Device using Android Emulator:
        * Install Android Studio with the default settings.
        * On __Welcome to Android Studio__, click __More Actions__, then click __Virtual Device Manager__.
        * Pick a device (development used a ```Pixel 4```) and click __Next__.
        * Pick a system image (development used ```R```) and click __Next__.
        * Once the SDK has finished installing, click __Finish__ and then click __Next__.
        * Ensure the __Startup orientation__ is set to ```Portrait```, and click __Finish__.
        * Click the play button on the device to launch the emulated device.
        * Start the Expo project 
            ```bash
            npx expo start
            ```
        * Press ```a``` in the console running the Expo app to launch the app inside the emulated device. If Expo Go is not installed, it will automatically start installing it on the emulated device.
        * Further Notes: 
            * Before pressing ```a``` in the console running the Expo app to open on Android, ensure the emulated device is running, otherwise you will get an error.
            * After creating the emulated device, if you get a continuous black screen without the typical bootup graphics or interface displaying, you may have to press the turn off button from the extended controls to the right of the device. During development, this caused the emulated device to display the app.


## <a name="references">References</a>
* The project was built while learning from [this course](https://www.youtube.com/watch?v=mJ3bGvy0WAY) by JavaScript Mastery.
* Models and assets used are located [here](https://drive.google.com/file/d/1VGr3R-3uta9xNj17eRHMxTELhtE2LaCm/view).
* Android Emulator instructions are based on [this tutorial](https://www.youtube.com/watch?v=WkXrDvImVXc) from Rudra Dey.
