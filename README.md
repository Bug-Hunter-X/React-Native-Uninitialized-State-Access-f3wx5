# React Native: Accessing State Before Initialization

This repository demonstrates a common error in React Native: attempting to access state variables before they've been initialized by the `useState` hook.  The `bug.js` file showcases the incorrect implementation, leading to a runtime error.  The solution (`bugSolution.js`) provides a corrected version using optional chaining or conditional rendering to handle the uninitialized state.

## Setup

1. Clone the repository:
   ```bash
git clone <repository_url>
```
2. Navigate to the directory:
   ```bash
cd <repository_directory>
```
3. Install dependencies:
   ```bash
yarn install
```
4. Run the application:
   ```bash
react-native run-android  // or react-native run-ios
```