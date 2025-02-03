<div align="center">
  <br />
    <img src="https://raw.githubusercontent.com/ansulagrawal/aora-app/master/assets/pages/cover.png" alt="Project Banner">
  <br />

  <div>
    <img src="https://img.shields.io/badge/-React_Native-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react.js" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
    <img src="https://img.shields.io/badge/NativeWind-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="nativewind" />
  </div>

  <h3 align="center">Video Sharing App</h3>
</div>


## <a name="tech-stack">⚙️ Tech Stack</a>

- React Native
- Expo
- Nativewind
- Animatable
- Appwrite

## <a name="features">🔋 Features</a>

👉 **Onboarding Screen**: Engaging graphics and clear instructions welcome users to the app.

👉 **Robust Authentication & Authorization System**: Secure email login safeguards user accounts.

👉 **Dynamic Home Screen with Animated Flat List**: Smoothly animated flat list showcases the latest videos for seamless browsing.

👉 **Pull-to-Refresh Functionality**: Users can refresh content with a simple pull gesture for up-to-date information.

👉 **Full-Text Search Capability**: Efficiently search through videos with real-time suggestions and instant results.

👉 **Tab Navigation**: Navigate between sections like Home, Search, and Profile with ease using tab navigation.

👉 **Post Creation Screen for Uploading Media**: Upload video and image posts directly from the app with integrated media selection.

👉 **Profile Screen with Detailed Insights**: View account details and activity, including uploaded videos and follower count, for a personalized experience.

👉 **Responsiveness**: Smooth performance and adaptability across various devices and screen sizes for a consistent user experience.

👉 **Animations**: Dynamic animations using the Animatable library to enhance user interaction and engagement throughout the app's UI.

and many more, including code architecture and reusability

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/ansulagrawal/aora-app.git
cd aora-app
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Adding ENV Variable**

- create a `.env` file

```
EXPO_PUBLIC_APPWRITE_ENDPOINT=""
EXPO_PUBLIC_APPWRITE_PLATFLORM=""
EXPO_PUBLIC_APPWRITE_PROJECT_ID=""
EXPO_PUBLIC_APPWRITE_DATABASE_ID=""
EXPO_PUBLIC_APPWRITE_USER_COLLECTION_ID=""
EXPO_PUBLIC_APPWRITE_VIDEO_COLLECTION_ID=""
EXPO_PUBLIC_APPWRITE_STORAGE_ID=""
```

**Running the Project**

```bash
npm start
```

**Expo Go**

Download the [Expo Go](https://expo.dev/go) app onto your device, then use it to scan the QR code from Terminal and run.

**Preview of all pages**

- Onboarding Page:
  <br />
  <img src="https://raw.githubusercontent.com/ansulagrawal/aora-app/master/assets/pages/onboarding.png" alt="Onboarding Page">
  <br />
  <br />


**Build**

Create a account on [expo](https://expo.dev) then flow below steps:

```bash
npm install -g eas-cli && eas login
```

```bash
expo init
```

```bash
eas build:configure
```

For `Android`:

```bash
eas build -p android --profile preview
```
