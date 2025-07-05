# Course 3: Mobile App Development with React Native

## Course Description

Dive into the world of cross-platform mobile app development with React Native. This course is designed to take you from a beginner to a capable React Native developer, able to build beautiful and functional mobile applications for both iOS and Android using a single JavaScript codebase. We will cover the fundamentals of React, core React Native components, navigation, state management, working with APIs, and deploying your applications. Get ready to build real-world mobile apps!

## Prerequisites

*   Solid understanding of JavaScript (ES6+ features like arrow functions, classes, destructuring, promises, async/await are crucial).
*   Familiarity with HTML and CSS concepts (React Native uses similar styling paradigms).
*   Basic understanding of Node.js and npm/yarn.
*   Comfortable using the command line/terminal.
*   A computer capable of running Android Studio (for Android development) and/or Xcode (for iOS development, macOS required).

## Course Outline

### Module 1: Introduction to React Native & Core Concepts

This module introduces React Native, sets up the development environment, and covers the fundamental concepts of React that are essential for React Native development.

*   **Lesson 1.1: What is React Native?**
    *   Introduction to Mobile App Development (Native vs. Cross-Platform).
    *   Advantages of React Native (Code Reusability, Faster Development, Large Community, Hot Reloading).
    *   How React Native Works (JavaScript Bridge, Native Modules).
    *   React Native vs. Other Cross-Platform Frameworks (e.g., Flutter, Ionic, Xamarin).
    *   Showcase of Apps Built with React Native.
    *   <YouTube videoId="0-S5a0eXPoc" title="React Native Explained in 100 Seconds by Fireship" />
    *   <YouTube videoId="6ZnfsJ6mM5c" title="What is React Native? And Why You Should Learn It by Programming with Mosh" />

*   **Lesson 1.2: Setting Up Your Development Environment**
    *   Node.js and npm/yarn installation.
    *   Choosing a Development Approach:
        *   **Expo CLI:** Easier setup, managed workflow, good for beginners, less access to native modules directly.
        *   **React Native CLI (Bare Workflow):** More flexibility, direct access to native code, more complex setup.
    *   Installing Expo CLI: `npm install -g expo-cli`
    *   Installing React Native CLI: `npx react-native init MyBareApp` (requires Android Studio/Xcode setup).
    *   Setting up Android Studio and Android Emulator (AVD).
    *   Setting up Xcode and iOS Simulator (macOS only).
    *   Installing a Code Editor (VS Code recommended with extensions like ESLint, Prettier, React Native Tools).
    *   Running your first React Native app (Expo and Bare Workflow).
    *   <YouTube videoId="00_hgtXrgqE" title="React Native Environment Setup - Expo vs React Native CLI by Academind" />
    *   <YouTube videoId="JedpQRRqdSY" title="React Native Ultimate Setup Guide 2023 (Mac & Windows) by Code with Nader" /> (Covers both Expo & Bare)

*   **Lesson 1.3: React Fundamentals for React Native - JSX and Components**
    *   Brief Recap of React: A JavaScript library for building user interfaces.
    *   JSX (JavaScript XML): Syntax extension for writing HTML-like structures in JavaScript.
        *   Embedding JavaScript expressions in JSX with `{}`.
        *   JSX attributes (e.g., `style`, `source`).
        *   JSX represents React elements.
    *   Components: Building blocks of a React Native application.
        *   Functional Components (with Hooks - preferred).
        *   Class Components (older, but good to recognize).
    *   Creating your first custom component.
    *   **Example (Functional Component):**
        ```javascript
        import React from 'react';
        import { Text, View } from 'react-native';

        const Greeting = (props) => {
          return (
            <View>
              <Text>Hello, {props.name}!</Text>
            </View>
          );
        };

        export default Greeting;
        ```
    *   <YouTube videoId="SqcY0GlETPk" title="React JS Crash Course by Traversy Media" /> (Focus on JSX and Components sections)

*   **Lesson 1.4: React Fundamentals - Props and State**
    *   **Props (Properties):** Passing data from parent to child components (read-only in the child).
        *   How to define and use props.
        *   `props.children`.
        *   Default props.
    *   **State:** Data that a component manages internally and can change over time.
        *   Using the `useState` Hook in functional components.
            ```javascript
            import React, { useState } from 'react';
            import { Text, Button, View } from 'react-native';

            const Counter = () => {
              const [count, setCount] = useState(0); // Initial state is 0

              return (
                <View>
                  <Text>Count: {count}</Text>
                  <Button title="Increment" onPress={() => setCount(count + 1)} />
                </View>
              );
            };
            export default Counter;
            ```
        *   Understanding how state changes trigger re-renders.
    *   Props vs. State.
    *   Lifting State Up.
    *   <YouTube videoId="sBws8MSXN7A" title="React State and Props Explained in 10 Minutes by Web Dev Simplified" />

*   **Lesson 1.5: Handling User Input and Events**
    *   Core Components for User Input: `TextInput`, `Button`, `Touchable` components.
    *   Event Handling in React Native (e.g., `onPress`, `onChangeText`).
    *   Passing event handlers as props.
    *   Working with `TextInput` to capture user input and update state.
    *   **Example:**
        ```javascript
        import React, { useState } from 'react';
        import { Text, TextInput, Button, View } from 'react-native';

        const NameInput = () => {
          const [name, setName] = useState('');
          const [submittedName, setSubmittedName] = useState('');

          return (
            <View>
              <TextInput
                placeholder="Enter your name"
                value={name}
                onChangeText={text => setName(text)} // Or onChangeText={setName}
                style={{ borderWidth: 1, padding: 10, marginBottom: 10 }}
              />
              <Button title="Submit" onPress={() => setSubmittedName(name)} />
              {submittedName ? <Text>Hello, {submittedName}!</Text> : null}
            </View>
          );
        };
        export default NameInput;
        ```
    *   <YouTube videoId="Ke90Tje7VS0" title="React Native Tutorial for Beginners - Handling User Input by The Net Ninja" /> (Part of a series)

*   **Lesson 1.6: Styling in React Native**
    *   Styling with JavaScript Objects (similar to CSS-in-JS).
    *   The `StyleSheet.create` API for performance optimization.
    *   Common Style Properties (Flexbox, dimensions, colors, fonts, margins, paddings).
    *   Inline styles vs. StyleSheet objects.
    *   Passing styles as props.
    *   Conditional styling.
    *   **Example:**
        ```javascript
        import React from 'react';
        import { Text, View, StyleSheet } from 'react-native';

        const StyledComponent = () => {
          return (
            <View style={styles.container}>
              <Text style={styles.title}>Styled Text</Text>
              <Text style={[styles.text, styles.highlight]}>Another Text</Text>
            </View>
          );
        };

        const styles = StyleSheet.create({
          container: {
            flex: 1,
            justifyContent: 'center',
            alignItems: 'center',
            backgroundColor: '#f0f0f0',
          },
          title: {
            fontSize: 24,
            fontWeight: 'bold',
            color: 'blue',
            marginBottom: 10,
          },
          text: {
            fontSize: 16,
          },
          highlight: {
            color: 'green',
          }
        });

        export default StyledComponent;
        ```
    *   <YouTube videoId="0-i0gVnI9L4" title="React Native Styling Tutorial by The Net Ninja" />

### Module 2: Core React Native Components & Layout

This module explores essential React Native components and how to arrange them using Flexbox.

*   **Lesson 2.1: View, Text, and Image Components**
    *   `<View>`: The most fundamental component for building UI. A container that supports layout with Flexbox, styling, some touch handling, and accessibility controls.
        *   Nesting Views to create complex layouts.
    *   `<Text>`: A component for displaying text. Supports nesting, styling, and touch handling.
        *   Text styling properties (`fontSize`, `fontWeight`, `color`, `textAlign`, etc.).
    *   `<Image>`: A component for displaying different types of images, including network images, static resources, and temporary local images.
        *   `source` prop (e.g., `require('./my-icon.png')` or `{uri: 'https://...'}`).
        *   `style` prop for dimensions, `resizeMode` (`cover`, `contain`, `stretch`, `repeat`, `center`).
    *   <YouTube videoId="R2zmjkE2B9Y" title="React Native Tutorial #6 - View, Text & StyleSheet by The Net Ninja" />
    *   <YouTube videoId="YjcLOhLcvQo" title="React Native Tutorial #7 - Images & Background Images by The Net Ninja" />

*   **Lesson 2.2: ScrollView and FlatList for Displaying Lists**
    *   `<ScrollView>`: A generic scrolling container that can host multiple components and views. Good for limited number of items.
        *   `horizontal` prop.
        *   Performance considerations for long lists.
    *   `<FlatList>`: A performant interface for rendering simple, flat lists.
        *   Only renders items currently visible on screen (virtualization).
        *   Required props: `data` (array of items) and `renderItem` (function to render each item).
        *   `keyExtractor` prop for unique keys.
        *   Optional props: `ListHeaderComponent`, `ListFooterComponent`, `ItemSeparatorComponent`, `onEndReached` (for infinite scrolling).
    *   **Example (FlatList):**
        ```javascript
        import React from 'react';
        import { FlatList, Text, View, StyleSheet } from 'react-native';

        const MyList = () => {
          const data = [
            { id: '1', title: 'Item 1' },
            { id: '2', title: 'Item 2' },
            { id: '3', title: 'Item 3' },
          ];

          const renderItem = ({ item }) => (
            <View style={styles.item}>
              <Text>{item.title}</Text>
            </View>
          );

          return (
            <FlatList
              data={data}
              renderItem={renderItem}
              keyExtractor={item => item.id}
            />
          );
        };
        // ... styles
        export default MyList;
        ```
    *   <YouTube videoId_V6u38Lz4k" title="React Native FlatList & SectionList Tutorial by The Net Ninja" />

*   **Lesson 2.3: SectionList for Grouped Data**
    *   `<SectionList>`: Similar to `FlatList` but for rendering sectioned lists.
    *   `sections` prop (array of objects, each with a `title` and `data` array).
    *   `renderItem` and `renderSectionHeader` props.
    *   `keyExtractor`.
    *   **Example:** Displaying contacts grouped by letter.
    *   <YouTube videoId_V6u38Lz4k" title="React Native FlatList & SectionList Tutorial by The Net Ninja" /> (Continued)

*   **Lesson 2.4: Flexbox for Layout in React Native**
    *   Recap: Flexbox is the primary layout system in React Native.
    *   Default `flexDirection` is `column` in React Native (unlike `row` in web CSS).
    *   Core Flexbox properties:
        *   `flexDirection`: `row`, `column`, `row-reverse`, `column-reverse`.
        *   `justifyContent`: Alignment along the main axis (`flex-start`, `flex-end`, `center`, `space-between`, `space-around`, `space-evenly`).
        *   `alignItems`: Alignment along the cross axis (`flex-start`, `flex-end`, `center`, `stretch`, `baseline`).
        *   `flex`: Proportion of available space an item should take (`flex: 1` makes it take all available space).
        *   `flexGrow`, `flexShrink`, `flexBasis`.
        *   `alignSelf`: Override `alignItems` for individual items.
    *   Building common layouts (e.g., headers, footers, sidebars, centered content).
    *   <YouTube videoId="7fH4YRPADWc" title="React Native Flexbox Tutorial by Academind" />

*   **Lesson 2.5: Dimensions and Platform-Specific Code**
    *   `Dimensions` API: Getting screen width and height (`Dimensions.get('window').width`).
        *   Useful for responsive styling.
        *   Note: Dimensions can change (e.g., device rotation).
    *   `Platform` API: Writing platform-specific code.
        *   `Platform.OS`: Returns `'ios'` or `'android'`.
        *   `Platform.select()`: Object with `ios` and `android` keys to provide platform-specific values.
        *   Platform-specific file extensions (e.g., `MyComponent.ios.js`, `MyComponent.android.js`).
    *   **Example (Platform.select):**
        ```javascript
        import { StyleSheet, Platform } from 'react-native';
        const styles = StyleSheet.create({
          container: {
            paddingTop: Platform.OS === 'ios' ? 20 : 0, // Different padding for iOS status bar
            backgroundColor: Platform.select({
              ios: 'silver',
              android: 'skyblue',
            }),
          },
        });
        ```
    *   <YouTube videoId="H9DU4QcRakA" title="React Native Responsive UI & Platform Specific Code by The Net Ninja" />

*   **Lesson 2.6: Touchable Components for User Interaction**
    *   Beyond `<Button>`: More customizable touch handling.
    *   `<TouchableOpacity>`: Opacity changes on press.
    *   `<TouchableHighlight>`: Background color changes on press (underlayColor).
    *   `<TouchableWithoutFeedback>`: No visual feedback, useful for custom feedback.
    *   `<Pressable>` (newer, recommended): More versatile, supports hover, focus, pressed states.
        *   `style` prop can be a function to apply styles based on state.
    *   Event props: `onPress`, `onLongPress`, `onPressIn`, `onPressOut`.
    *   <YouTube videoId="Gc2ygs7n9hY" title="React Native Touchable Components & Pressable API by The Net Ninja" />

### Module 3: Navigation in React Native

This module covers how to implement navigation between different screens in your React Native application using React Navigation.

*   **Lesson 3.1: Introduction to React Navigation**
    *   Why is navigation needed?
    *   Overview of React Navigation library (most popular solution).
    *   Core concepts: Navigators (Stack, Tab, Drawer), Screens, Navigation Props.
    *   Installation:
        ```bash
        npm install @react-navigation/native
        # For Expo managed projects
        expo install react-native-screens react-native-safe-area-context
        # For Bare React Native projects
        npm install react-native-screens react-native-safe-area-context
        ```
    *   <YouTube videoId="9yYn1WDA32Y" title="React Navigation 5 - Crash Course by Traversy Media" /> (Note: Version might be slightly old, check official docs for latest v6+)
    *   Official Docs: [React Navigation Docs](https://reactnavigation.org/docs/getting-started)

*   **Lesson 3.2: Stack Navigator**
    *   For navigating between screens where each new screen is placed on top of a stack.
    *   Installation: `npm install @react-navigation/stack`
    *   Creating a Stack Navigator: `createStackNavigator()`.
    *   Defining Screens within the navigator.
    *   `NavigationContainer`: Must wrap your root navigator.
    *   Navigating between screens: `navigation.navigate('RouteName')`.
    *   Passing parameters to routes: `navigation.navigate('Details', { itemId: 86 })`.
    *   Accessing parameters in the screen: `route.params`.
    *   Configuring the header bar (title, colors, custom components).
    *   `navigation.goBack()`, `navigation.push()`.
    *   **Example:**
        ```javascript
        // App.js
        import * as React from 'react';
        import { NavigationContainer } from '@react-navigation/native';
        import { createStackNavigator } from '@react-navigation/stack';
        // ... import HomeScreen, DetailsScreen

        const Stack = createStackNavigator();

        function App() {
          return (
            <NavigationContainer>
              <Stack.Navigator initialRouteName="Home">
                <Stack.Screen name="Home" component={HomeScreen} options={{ title: 'Overview' }} />
                <Stack.Screen name="Details" component={DetailsScreen} />
              </Stack.Navigator>
            </NavigationContainer>
          );
        }
        export default App;
        ```
    *   <YouTube videoId="NYSN-OV_FRs" title="React Navigation - Stack Navigator Tutorial by Academind" />

*   **Lesson 3.3: Tab Navigator**
    *   For implementing tab-based navigation (bottom tabs or top tabs).
    *   Installation: `npm install @react-navigation/bottom-tabs` or `npm install @react-navigation/material-top-tabs`.
    *   Creating a Bottom Tab Navigator: `createBottomTabNavigator()`.
    *   Defining tab screens.
    *   Customizing tab icons and labels.
    *   `tabBarOptions` (older versions) or `screenOptions` with `tabBarIcon`, `tabBarLabel` (newer versions).
    *   Nesting navigators (e.g., a stack navigator inside each tab).
    *   <YouTube videoId="fRDf5nK_pgA" title="React Navigation - Tab Navigator Tutorial by Academind" />

*   **Lesson 3.4: Drawer Navigator**
    *   For implementing a navigation drawer that slides in from the side.
    *   Installation: `npm install @react-navigation/drawer`.
    *   Creating a Drawer Navigator: `createDrawerNavigator()`.
    *   Defining drawer screens.
    *   Opening and closing the drawer programmatically: `navigation.openDrawer()`, `navigation.closeDrawer()`, `navigation.toggleDrawer()`.
    *   Customizing drawer content and appearance.
    *   <YouTube videoId="hSTTa2QHT6Y" title="React Navigation - Drawer Navigator Tutorial by Academind" />

*   **Lesson 3.5: Navigating Between Navigators & Advanced Patterns**
    *   Strategies for navigating from a screen in one navigator (e.g., Tab) to a screen in another (e.g., a modal Stack).
    *   Using `navigation.navigate()` with nested navigator names.
    *   Authentication flows: Handling login/logout and navigating between auth screens and main app screens.
        *   Conditionally rendering navigators based on auth state.
    *   Deep Linking: Opening specific screens in your app from a URL.
    *   Type checking with TypeScript for navigation props (recommended for larger apps).
    *   <YouTube videoId="hAsKeAbfr2k" title="React Navigation - Authentication Flow (Login/Logout) by Academind" />

*   **Lesson 3.6: Navigation Lifecycle and Best Practices**
    *   Understanding screen lifecycle events with React Navigation (e.g., `focus`, `blur` listeners using hooks like `useFocusEffect`).
    *   Performance considerations with navigation.
    *   Organizing navigation code in larger applications.
    *   Best practices for user experience in mobile navigation.
    *   <YouTube videoId="QhSFd1EThkM" title="React Navigation Hooks - useNavigation, useRoute, useFocusEffect by Codedamn" />

### Module 4: State Management in React Native

This module explores different techniques for managing state in React Native applications, especially as they grow in complexity.

*   **Lesson 4.1: Review of Component State with `useState` and `useReducer`**
    *   `useState`: For simple local component state.
    *   Limitations of `useState` for complex state logic or shared state.
    *   `useReducer`: An alternative to `useState` for managing more complex state logic.
        *   Reducer function: `(state, action) => newState`.
        *   `dispatch` function to send actions.
        *   Good for state that involves multiple sub-values or when the next state depends on the previous one.
    *   **Example (useReducer):**
        ```javascript
        const initialState = { count: 0 };
        function reducer(state, action) {
          switch (action.type) {
            case 'increment': return { count: state.count + 1 };
            case 'decrement': return { count: state.count - 1 };
            default: throw new Error();
          }
        }
        // In component:
        // const [state, dispatch] = useReducer(reducer, initialState);
        // <Button title="+" onPress={() => dispatch({ type: 'increment' })} />
        ```
    *   <YouTube videoId="kK_Wqx3RnHk" title="React Hooks Tutorial - 15 - useReducer Hook by Codevolution" />

*   **Lesson 4.2: React Context API for Global State**
    *   What is Context? A way to pass data through the component tree without having to pass props down manually at every level.
    *   When to use Context (for global state like theme, user authentication, language).
    *   `React.createContext()`: Creates a Context object.
    *   `Context.Provider`: Component that provides the context value to its children.
    *   `Context.Consumer` (older) or `useContext` Hook (preferred): To consume the context value in child components.
    *   **Example:**
        ```javascript
        // theme-context.js
        import React, { createContext, useState, useContext } from 'react';
        export const ThemeContext = createContext();
        export const ThemeProvider = ({ children }) => {
          const [theme, setTheme] = useState('light');
          const toggleTheme = () => setTheme(prev => (prev === 'light' ? 'dark' : 'light'));
          return <ThemeContext.Provider value={{ theme, toggleTheme }}>{children}</ThemeContext.Provider>;
        };
        export const useTheme = () => useContext(ThemeContext);

        // App.js: Wrap with <ThemeProvider>
        // MyComponent.js: const { theme, toggleTheme } = useTheme();
        ```
    *   Limitations: Can cause performance issues if not used carefully (all consumers re-render when context value changes).
    *   <YouTube videoId="5bL2VdOpCMs" title="React Context API Tutorial by Traversy Media" />

*   **Lesson 4.3: Introduction to Redux for State Management**
    *   What is Redux? A predictable state container for JavaScript apps.
    *   Core Redux Concepts:
        *   Store: Single source of truth for application state.
        *   Actions: Plain JavaScript objects describing what happened.
        *   Reducers: Pure functions that specify how the state changes in response to actions.
        *   Dispatch: How actions are sent to the store.
        *   Middleware: For handling asynchronous actions (e.g., Redux Thunk, Redux Saga).
    *   Why use Redux? (Centralized state, easier debugging, maintainability for large apps).
    *   Setting up Redux: `redux`, `react-redux`.
    *   <YouTube videoId="9boMnm5X9ak" title="Redux Crash Course With React by Traversy Media" />

*   **Lesson 4.4: Redux with React Native - Actions, Reducers, and Store**
    *   Creating Actions and Action Creators.
    *   Writing Reducers to handle actions and update state immutably.
    *   Combining multiple reducers with `combineReducers`.
    *   Creating the Redux Store with `createStore()`.
    *   Providing the store to the React application using `<Provider>` from `react-redux`.
    *   Connecting React components to Redux:
        *   `useSelector` Hook: To extract data from the Redux store state.
        *   `useDispatch` Hook: To get the `dispatch` function and dispatch actions.
    *   **Example Structure:**
        *   `actions/types.js` (action type constants)
        *   `actions/postActions.js` (action creators)
        *   `reducers/postReducer.js` (reducer logic)
        *   `reducers/index.js` (combine reducers)
        *   `store.js` (create store)
    *   <YouTube videoId="9boMnm5X9ak" title="Redux Crash Course With React by Traversy Media" /> (Focus on React integration parts)

*   **Lesson 4.5: Asynchronous Actions with Redux Thunk**
    *   Need for handling async operations (e.g., API calls) in Redux.
    *   Redux Thunk middleware: Allows action creators to return a function instead of an action object.
        *   This function receives `dispatch` and `getState` as arguments.
    *   Installation: `npm install redux-thunk`.
    *   Applying middleware when creating the store: `applyMiddleware(thunk)`.
    *   Writing thunk action creators for API calls.
    *   **Example (Thunk Action Creator):**
        ```javascript
        // actions/dataActions.js
        export const fetchData = () => async dispatch => {
          try {
            dispatch({ type: 'FETCH_DATA_REQUEST' });
            const response = await fetch('https://api.example.com/data');
            const data = await response.json();
            dispatch({ type: 'FETCH_DATA_SUCCESS', payload: data });
          } catch (error) {
            dispatch({ type: 'FETCH_DATA_FAILURE', payload: error.message });
          }
        };
        ```
    *   <YouTube videoId="1QI-UE3-0c4" title="Redux Thunk Tutorial by Traversy Media" />

*   **Lesson 4.6: Redux Toolkit (Modern Redux)**
    *   Why Redux Toolkit? Simplifies Redux development, reduces boilerplate, includes best practices by default.
    *   `configureStore()`: Simplified store setup, automatically includes Thunk and DevTools.
    *   `createSlice()`: Generates reducers, action creators, and action types from a "slice" of state.
    *   `createAsyncThunk()`: For handling asynchronous actions (like API calls) more easily.
    *   Migrating from traditional Redux to Redux Toolkit.
    *   Highly recommended for new Redux projects.
    *   <YouTube videoId="0XgB7SgC-V4" title="Redux Toolkit Crash Course 2023 by Laith Harb" />
    *   <YouTube videoId="NqzdVN2tyvQ" title="Redux Toolkit Tutorial by Codevolution" />

### Module 5: Working with APIs, Local Storage, and Native Features

This module covers fetching data from remote servers, storing data locally, and interacting with some native device features.

*   **Lesson 5.1: Fetching Data from APIs with `fetch` and `Axios`**
    *   Making network requests in React Native.
    *   Using the built-in `fetch` API.
        *   Handling GET, POST, PUT, DELETE requests.
        *   Working with JSON data.
        *   Error handling.
    *   Using `Axios` library (popular alternative to `fetch`).
        *   Installation: `npm install axios`.
        *   Benefits: Easier error handling, request/response interception, automatic JSON transformation.
    *   Displaying fetched data in components.
    *   Loading indicators and error messages.
    *   Integrating with Redux/Context for state management of API data.
    *   **Example (fetch):**
        ```javascript
        // Inside an async function or useEffect
        try {
          const response = await fetch('https://jsonplaceholder.typicode.com/todos/1');
          if (!response.ok) throw new Error('Network response was not ok.');
          const data = await response.json();
          console.log(data);
          // setData(data);
        } catch (error) {
          console.error('Fetch error:', error);
          // setError(error.message);
        }
        ```
    *   <YouTube videoId="Ekpmi9rXh8M" title="React Native API Calls Tutorial - Fetch & Axios by The Net Ninja" />

*   **Lesson 5.2: Asynchronous JavaScript Review (Promises, `async/await`)**
    *   Deep dive into Promises: `then()`, `catch()`, `finally()`, `Promise.all()`, `Promise.race()`.
    *   `async/await` syntax for cleaner asynchronous code.
    *   Error handling with `try...catch` in `async` functions.
    *   Common patterns for handling asynchronous operations in React components (e.g., in `useEffect` Hook).
    *   <YouTube videoId="DHvZLI7Db8E" title="Async Await JavaScript ES7 by Traversy Media" />

*   **Lesson 5.3: Persistent Local Storage with `AsyncStorage` (or community alternatives)**
    *   `AsyncStorage`: Simple, unencrypted, asynchronous, persistent key-value storage system (deprecated from core, use community package `@react-native-async-storage/async-storage`).
    *   Installation: `npm install @react-native-async-storage/async-storage`
    *   Storing data: `AsyncStorage.setItem('key', JSON.stringify(value))`.
    *   Retrieving data: `const value = await AsyncStorage.getItem('key'); return value ? JSON.parse(value) : null;`.
    *   Removing data: `AsyncStorage.removeItem('key')`.
    *   Use cases: Storing user preferences, authentication tokens, offline data.
    *   Alternatives for more complex needs (e.g., SQLite, Realm).
    *   <YouTube videoId="tN3Adna4u38" title="React Native AsyncStorage Tutorial by Codedamn" />

*   **Lesson 5.4: Using the Camera and Photo Library (Expo Packages)**
    *   Accessing device camera and photo library using Expo packages.
    *   `expo-camera`: For taking photos and videos.
        *   Requesting permissions.
        *   Displaying camera preview.
        *   Taking pictures and recording videos.
    *   `expo-image-picker`: For selecting images/videos from the device's library.
        *   Requesting permissions.
        *   Launching image/video library.
        *   Handling selected media.
    *   Displaying captured/selected images in the app.
    *   (For Bare RN, you'd use libraries like `react-native-camera` and `react-native-image-picker` which require native linking).
    *   <YouTube videoId="IZGggIpc72U" title="React Native Camera & Image Picker Tutorial (Expo) by NotJust.dev" />

*   **Lesson 5.5: Geolocation and Maps (Expo Packages)**
    *   `expo-location`: Accessing device's GPS location.
        *   Requesting location permissions.
        *   Getting current location (one-time or continuous updates).
        *   Handling location accuracy.
    *   `react-native-maps` (Works with Expo and Bare RN, may require configuration).
        *   Displaying maps (Google Maps on Android, Apple Maps on iOS).
        *   Adding markers, polygons, polylines.
        *   User interaction with maps (zooming, panning).
        *   Displaying user's current location on the map.
    *   <YouTube videoId="qK459405HSk" title="React Native Maps Tutorial (Expo & Bare) by NotJust.dev" />
    *   <YouTube videoId="q7hH4jVgxpI" title="Expo Location Tutorial - Get User's Location by Codedamn" />

*   **Lesson 5.6: Working with Device Permissions**
    *   Understanding the importance of requesting permissions at runtime (Android M+ and iOS).
    *   Using `expo-permissions` (older, now integrated into specific modules like `expo-camera`, `expo-location`) or `react-native-permissions` (for Bare RN).
    *   Checking current permission status.
    *   Requesting permissions from the user.
    *   Handling permission grants and denials gracefully.
    *   Best practices for asking for permissions (provide context, ask only when needed).
    *   <YouTube videoId="d1kM6moiD3I" title="Handle Permissions in React Native (Expo & Bare Workflow) by Code with Nader" />

### Module 6: Debugging, Testing, and Deployment

This module covers essential skills for finalizing your React Native application: debugging, writing tests, and preparing for deployment to app stores.

*   **Lesson 6.1: Debugging React Native Applications**
    *   Using the Developer Menu (Shake gesture or keyboard shortcuts).
        *   Reload, Hot Reloading, Fast Refresh.
        *   Enable/Disable Performance Monitor.
        *   Debug JS Remotely (using Chrome DevTools).
    *   Chrome DevTools for JavaScript debugging:
        *   Console for logs, warnings, errors.
        *   Sources tab for setting breakpoints and stepping through code.
        *   Network tab for inspecting API requests.
    *   React Native Debugger (standalone application combining Chrome DevTools, React DevTools, Redux DevTools).
    *   React DevTools for inspecting component hierarchy, props, and state.
    *   Flipper (by Facebook): Extensible mobile app debugger.
    *   Logging effectively (`console.log`, `console.warn`, `console.error`).
    *   <YouTube videoId="4gPCMm2Qc3w" title="Debugging React Native Apps - Tips & Tools by Academind" />

*   **Lesson 6.2: Error Handling and Crash Reporting**
    *   Common types of errors in React Native apps.
    *   Using `try...catch` for synchronous errors.
    *   Handling Promise rejections (`.catch()`).
    *   Error Boundaries in React: Components that catch JavaScript errors anywhere in their child component tree.
    *   Implementing basic Error Boundaries.
    *   Introduction to crash reporting services (e.g., Sentry, Firebase Crashlytics) for production apps.
    *   <YouTube videoId="Cswn5A0ZJ6c" title="React Error Boundaries In 11 Minutes by Web Dev Simplified" />

*   **Lesson 6.3: Unit Testing with Jest**
    *   Introduction to testing and its importance.
    *   Jest: JavaScript testing framework, often included by default in React Native projects.
    *   Writing basic unit tests for functions and components.
    *   Matchers (`toBe`, `toEqual`, `toHaveBeenCalled`, etc.).
    *   Testing React components (snapshots, testing props, state changes, event handlers).
    *   Using React Native Testing Library (`@testing-library/react-native`) for more user-centric component testing.
        *   Querying elements by text, accessibility labels, etc.
        *   Simulating user interactions.
    *   Mocking dependencies (e.g., API calls, native modules).
    *   Running tests and interpreting results.
    *   <YouTube videoId="FgnxcWiS5LQE" title="React Native Testing Tutorial with Jest & React Testing Library by The Net Ninja" />

*   **Lesson 6.4: End-to-End (E2E) Testing Overview (Detox/Appium)**
    *   What is E2E testing? Testing the application flow from the user's perspective.
    *   Introduction to E2E testing frameworks for React Native:
        *   Detox: Gray box E2E testing framework by Wix.
        *   Appium: Open-source tool for automating native, mobile web, and hybrid applications.
    *   Basic concepts: Writing test scripts, selecting elements, performing actions, making assertions.
    *   This is an overview; full E2E testing is a large topic.
    *   <YouTube videoId="s30shW0Lg5c" title="React Native E2E Testing with Detox - Getting Started by NotJust.dev" />

*   **Lesson 6.5: Building and Bundling for Release**
    *   Understanding app bundling (JavaScript bundle and native assets).
    *   **Expo CLI:**
        *   Building standalone apps: `expo build:android` and `expo build:ios`.
        *   EAS Build (Expo Application Services): Modern way to build and submit apps developed with Expo (and even bare React Native).
    *   **React Native CLI (Bare Workflow):**
        *   Generating a release build for Android (APK/AAB).
            *   Generating a signing key.
            *   Configuring Gradle for release.
        *   Generating a release build for iOS (IPA).
            *   Xcode configuration (certificates, provisioning profiles).
            *   Archiving and exporting the app.
    *   Over-the-Air (OTA) updates (e.g., using Expo Updates or CodePush).
    *   <YouTube videoId="O_007f2jWlA" title="Build & Deploy React Native Apps (Android & iOS) with EAS Build (Expo) by NotJust.dev" />
    *   <YouTube videoId="nfYLoK0V7AU" title="React Native - Generate Signed APK For Play Store (Android) by Code Step By Step" /> (Bare RN)

*   **Lesson 6.6: Publishing to App Stores (Overview)**
    *   Google Play Store (Android):
        *   Creating a Google Play Developer account.
        *   Preparing store listing (title, description, screenshots, promo video).
        *   Uploading your Android App Bundle (AAB).
        *   Setting up pricing, distribution, content rating.
        *   Managing releases (alpha, beta, production).
    *   Apple App Store (iOS):
        *   Enrolling in the Apple Developer Program.
        *   Creating an App Store Connect record.
        *   Preparing store listing.
        *   Uploading your build using Xcode or Transporter.
        *   TestFlight for beta testing.
        *   App Store review process.
    *   Key considerations: App Store guidelines, marketing, post-launch monitoring.
    *   <YouTube videoId="HZeT0t4GBhQ" title="Publish React Native App to Google Play Store & Apple App Store (2023) by Code with Nader" />

---

This course provides a comprehensive path to becoming a React Native developer. Remember that the mobile development landscape evolves, so continuous learning and consulting official documentation are key. Good luck building amazing mobile apps!
