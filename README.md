# Mobile App Developer With React Native And React Native Expo

Materi ini ditujukan untuk membuat aplikasi mobile pada Android mobile phone dengan menggunakan React Native, dan diutamakan menggunakan React Native EXPO.  EXPO merupakan framework untuk React Native dengan berbagai build in library, dengan tujuan untuk mengurangi pemakaian third party library.  Materi yang dipelajari ini khusus untuk Android.  Dimana nantinya bisa di build juga untuk iOS dengan sedikit perubahan.

## Prerequisite
### Sudah mempelajari dan menyelesaikan materi berikut:
1. [Javascript Basic](https://github.com/praxis-academy/akademik/blob/v2.0/kurikulum/enterprise-front-end/isi/01.md)
2. [Javascript ES6](https://www.javascripttutorial.net/es6/)
3. [Object Oriented Programming](https://github.com/praxis-academy/akademik/blob/v2.0/kurikulum/enterprise-front-end/isi/02.md) in Javascript

# Let's Dive in to React Native and EXPO React Native

## Documentation
1. [React Native Documentation](https://reactnative.dev/)
2. [EXPO React Native Documentation](https://docs.expo.dev/)

# Lesson 1 - Install, Create New Project, And Running
1. Install [node js](https://nodejs.org/en/) LTS version
2. Install [expo-cli](https://docs.expo.dev/workflow/expo-cli/) on global environment using terminal
3. Download and install android emulator, recommended one is LD Player, then set it to mobile mode 1080x1920 2cores 2048M of RAM
4. Donwload [Expo Go](https://play.google.com/store/search?q=expo%20go&c=apps&hl=en) app on Playstore for both emulator and physical device
5. Create [Expo Project](https://docs.expo.dev/get-started/create-a-new-app/)
6. Run the newly created app both in android emulator and your physical device

#

# Lesson 2 - Components And Styling
1. Create a new page, then export the newly created page inside app.js
2. Import react native component API such as Text, View, Text Input, and other within this [Documentation](https://docs.expo.dev/versions/v46.0.0/react-native/view/)
3. Try to render and display all those cmponent in your screen
4. Styling.  Use inline styling and StyleShhet API from react-native, also learn about [layouting](https://reactnative.dev/docs/flexbox), [dimensions](https://reactnative.dev/docs/height-and-width) including height and weight, native css like margin, padding, border, etc
### Lesson 2 - Extra
1. UI Library.  Contains a bunch of UI library for react native especially EXPO, check [this](https://medium.com/nerd-for-tech/top-5-ui-libraries-for-react-native-2ce8a973bb1c) out.  You can try installing and rendering those UI component
### Lesson 2 - Mini Project
Create a login page, with new page called Login page, and import it inside your app.js. Create and design your own Login page with your own creativity.  Good Luck!!

#

# Lesson 3 - React Hooks and Component Function
1. Mastering basic React Hooks like [useState](https://reactjs.org/docs/hooks-state.html), and [useEffect](https://reactjs.org/docs/hooks-effect.html)
2. Component function like onPress for a button, and onChangeText for Text Input
### Lesson 3 - Extra
1. Learning [Advance Hooks](https://reactjs.org/docs/hooks-reference.html#additional-hooks).  There are a bunch of react advance hooks, but the most usable hooks these days are useCallback and useMemo.  But you can try another hook also
###  Lesson 3 - Mini Project
Crate a simple calculator app.  A very-very simple app to do a basic math calculation like addition, substraction, multiplication, and division, reset the calculation to zero.  And don't forget to styles your app too, coz it is a must do for a mboile developer.  Good Luck!! 

#

# Lesson 4 - Consuming API
1. Install axios library using npm
2. Do CRUD operation using API
3. Displaying success and error when consuming API
