Getting Started
Following these instructions will allow you to run and build the project on your local machine for development and testing purposes.

Prerequisites
Follow the official guide "Setting up the development environment" to set up your local machine to develop iOS and Android applications with React Native.

Install an xCode version that supports iOS 13.5, required by the ExposureNotification framework used by the app.

Install yarn globally:

npm install -g yarn
For other installation methods, follow the official Installation guide.

Installing
Clone this repository.

Install the npm dependencies:

yarn install
Create your .env file or copy it from the .env.sample:

cp .env.sample .env
Move to ios/ folder and install the CocoaPods dependencies:

cd ios && pod install
Running the applications locally
Start the React Native bundler:

yarn start
To start the Android application, run:

yarn android
To start the iOS one, run:

yarn ios