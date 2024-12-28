<<<<<<< HEAD
=======
# videoSDK-assignment

>>>>>>> a38ac02db72c56c7e566478df352cce043f86824
Video SDK empowers developers to build world-class collaborative products with live video/audio, cloud recording, RTMP/HLS streaming, and interaction APIs.

🎉 Get 10,000 free minutes every month! Start Now

<<<<<<< HEAD
📚 Table of Contents 🖥️ Demo App 📱 Compatibility ⚡ Quick Setup 🛠 Prerequisites 📦 Running the Sample App 🔥 Features 🧠 Key Concepts 🔐 Token Generation 📖 Documentation 🤝 Join Our Community 🖥️ Demo App 📱 Download and explore the sample apps:

Android iOS 📱 Compatibility Platform Supported Android ✅ iOS ✅ Web ✅ macOS ✅ Windows ✅ Safari ❌ ⚡ Quick Setup Sign Up: Create an account on VideoSDK to get your API Key and Secret. Understand Tokens: Learn how to generate and manage tokens from the Token Guide. 🛠 Prerequisites Flutter 2.0+ with Dart 3.3.0+ A valid VideoSDK Account 📦 Running the Sample App

Clone the Repository
git clone https://github.com/videosdk-live/videosdk-rtc-flutter-sdk-example.git cd videosdk-rtc-flutter-sdk-example

Copy and Configure Environment File
cp .env.example .env Update .env with your generated temporary token:
=======
📚 Table of Contents
🖥️ Demo App
📱 Compatibility
⚡ Quick Setup
🛠 Prerequisites
📦 Running the Sample App
🔥 Features
🧠 Key Concepts
🔐 Token Generation
📖 Documentation
🤝 Join Our Community
🖥️ Demo App
📱 Download and explore the sample apps:

Android
iOS
📱 Compatibility
Platform	Supported
Android	✅
iOS	✅
Web	✅
macOS	✅
Windows	✅
Safari	❌
⚡ Quick Setup
Sign Up: Create an account on VideoSDK to get your API Key and Secret.
Understand Tokens: Learn how to generate and manage tokens from the Token Guide.
🛠 Prerequisites
Flutter 2.0+ with Dart 3.3.0+
A valid VideoSDK Account
📦 Running the Sample App
1. Clone the Repository

git clone https://github.com/videosdk-live/videosdk-rtc-flutter-sdk-example.git
cd videosdk-rtc-flutter-sdk-example

2. Copy and Configure Environment File

cp .env.example .env
Update .env with your generated temporary token:
>>>>>>> a38ac02db72c56c7e566478df352cce043f86824

env

AUTH_TOKEN=YOUR_TEMPORARY_TOKEN

<<<<<<< HEAD
Install Dependencies flutter pub get

iOS/macOS Setup (Optional) Navigate to the respective folder and install CocoaPods:

cd ios pod install

Run the Application flutter run
🔥 Features Feature Description Documentation Precall Setup Configure devices before joining a call Docs Join/Leave Meeting Seamlessly join and leave meetings Join, Leave Mute/Unmute Mic Control microphone during calls Docs Toggle Camera Enable/disable video during calls Docs Screen Share Share your screen with participants Docs Virtual Background Add virtual/blurred backgrounds Docs Chat In-meeting chat with participants Docs Recording Record meetings for future use Docs

🧠 Key Concepts Meeting: Represents real-time video and audio communication. Participant: Local or remote user in a meeting. Stream: Media (audio/video) content shared during a meeting.

🔐 Token Generation Development Use temporary tokens for quick development. Generate one from the dashboard.

Production For secure token management in production, set up an authentication server. Example repositories:

API Server Examples 📖 Documentation Explore detailed guides and examples in the VideoSDK Documentation.

🤝 Join Our Community Discord: Connect with developers and the VideoSDK team. X (Twitter): Follow for updates and announcements. This README provides all the essential details to get started with VideoSDK in a Flutter project. Let me know if you want to refine any specific section further!
=======
3. Install Dependencies
flutter pub get

5. iOS/macOS Setup (Optional)
Navigate to the respective folder and install CocoaPods:

cd ios
pod install

5. Run the Application
flutter run


🔥 Features
Feature	Description	Documentation
Precall Setup	Configure devices before joining a call	Docs
Join/Leave Meeting	Seamlessly join and leave meetings	Join, Leave
Mute/Unmute Mic	Control microphone during calls	Docs
Toggle Camera	Enable/disable video during calls	Docs
Screen Share	Share your screen with participants	Docs
Virtual Background	Add virtual/blurred backgrounds	Docs
Chat	In-meeting chat with participants	Docs
Recording	Record meetings for future use	Docs

🧠 Key Concepts
Meeting: Represents real-time video and audio communication.
Participant: Local or remote user in a meeting.
Stream: Media (audio/video) content shared during a meeting.

🔐 Token Generation
Development
Use temporary tokens for quick development. Generate one from the dashboard.

Production
For secure token management in production, set up an authentication server. Example repositories:

API Server Examples
📖 Documentation
Explore detailed guides and examples in the VideoSDK Documentation.

🤝 Join Our Community
Discord: Connect with developers and the VideoSDK team.
X (Twitter): Follow for updates and announcements.
This README provides all the essential details to get started with VideoSDK in a Flutter project. Let me know if you want to refine any specific section further!
>>>>>>> a38ac02db72c56c7e566478df352cce043f86824
