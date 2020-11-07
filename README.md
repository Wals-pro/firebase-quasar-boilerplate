# **Quasar-Firebase Sample Apps**:
A working repository to highlight and show the integration of Google's Firebase services with in the Quasar framework. Each concept will be siloed with in its own application to focus on the scope of the implementation. If an example doesn't highlight a need or sepecific concern with in its scope please consider researching in our discord *#firebase* channel within the backend api grouping or post a question on our forum.

Each application is meant to be considered in conjunction with the dev.to blog post series Quasar-Firebase.

## **Applications**
### **Base Implementation**
  - Firebase Initialization
  - Base Service & Structure
### **Email Authentication**
  - Create and log in users via Email & Password
### **Data Integration**
  - User Profile
  - Vuexfire
  - QUploader to Google Cloud Storage

## **Installation**
npm install -g firebase-tools
yarn add cross-env
quasar ext add @quasar/qenv
firebase init
firebase deploy
