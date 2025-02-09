# 🏡 Full-Stack Real Estate App

A full-stack Real Estate app built from scratch using **React Native, React.js, Expo, Google Authentication, and Appwrite**. This app features **dynamic routing, authentication, and a modern UI** powered by **Tailwind CSS** and **NativeWind** This is my first mobile app.

## 🚀 Features
- 🔑 **Google Authentication** (Secure login with Firebase/Auth)
- 📍 **Dynamic Routing** using **expo-router**
- 📦 **Appwrite Database** for managing listings & user data
- 🎨 **Tailwind CSS** & **NativeWind** for modern UI styling
- 📱 **Cross-platform support** (iOS, Android, Web via Expo)

## 🛠️ Technologies Used
- **React Native** (for mobile UI)
- **React.js** (for web-based components)
- **Expo** (for development & deployment)
- **Google Authentication** (OAuth integration)
- **Tailwind CSS + NativeWind** (styling)
- **Appwrite** (backend, database, and authentication)
- **Expo Router** (dynamic navigation)

## 📂 Project Structure
```sh
📦 real-estate-app
├── 📂 app          # Expo Router pages
├── 📂 components   # Reusable UI components
├── 📂 config       # Configuration files (Auth, API, etc.)
├── 📂 constants    # Configuration data
├── 📂 lib          # Integration with appwrite
├── 📂 assets       # Images, icons, etc.
├── package.json    # Dependencies
└── README.md       # Project documentation
```

## 🔧 Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Abhishek-Bharti1/expo-restate-app.git
   cd real-estate-app
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up Appwrite & Google Authentication (Add API keys in `.env` file):
   ```env
 EXPO_PUBLIC_APPWRITE_PROJECT_ID=
 EXPO_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
 EXPO_PUBLIC_APPWRITE_DATABASE_ID=
 EXPO_PUBLIC_APPWRITE_GALLERIES_COLLECTION_ID=
 EXPO_PUBLIC_APPWRITE_REVIEWS_COLLECTION_ID=
 EXPO_PUBLIC_APPWRITE_AGENTS_COLLECTION_ID=
 EXPO_PUBLIC_APPWRITE_PROPERTIES_COLLECTION_ID
   ```
4. Run the app:
   ```sh
   expo start
   ```

## 🚀 Deployment
To deploy the app using Expo Application Services (EAS):
```sh
eas build -p android  # For Android
eas build -p ios      # For iOS
```

## 📜 License
This project is licensed under the [MIT License](LICENSE).

## 💡 Contributing
Feel free to contribute by opening issues or submitting PRs. Let's build something amazing together! 🚀

