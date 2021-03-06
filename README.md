# React Native Fundamentals
React Native concepts challenge applied for the GoStack Bootcamp

## :rocket: About the challenge

In this challenge, I will develop another application, a GoRestaurant, only this time the mobile version for the customer. Now I will practice what I've learned so far in React Native together with TypeScript, to create a small app for ordering food.

This will be an application that will connect to a fake API, and display and filter the API's food dishes and allow the creation of new orders.

## :hammer: Do you want to check it out?

Clone the repository:

```sh
  $ git clone https://github.com/paulo-carvalho93/desafio-delivery-react-native.git
```

If you are emulating on iOS, in your project folder, navigate to the ios folder and run the following commands to install all dependencies for iOS.
```sh
  $ cd ios
  $ pod install
  $ yarn ios # or npm ios
  $ yarn ios # or npm run ios
  
```

If you are emulating on Android with Android Studio run the following commands:

```sh
  $ cd desafio-delivery-react-native
  # Installing project dependencies
  $ yarn # or npm install
  
  # Running unit tests
  $ yarn test # or npm test

  # Start Android Emulator
  $ yarn start # or npm start
  $ yarn run react-native run-android # or npm run react-native run-android
  # OR
  $ yarn android
  ```
  
  Attention: You need **json-server** running to bring all the products.
  
  ```sh
   # Run the following command:
   $ yarn json-server server.json -p 3333
   ```
  
  
