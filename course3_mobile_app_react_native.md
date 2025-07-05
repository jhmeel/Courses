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

### Module 1: Introduction to React Native & Core Concepts (Expanded)

This module introduces React Native, sets up the development environment, and covers the fundamental concepts of React that are essential for React Native development, now with significantly more detail.

*   **Lesson 1.1: The Mobile App Landscape - Native, Web, Hybrid, Cross-Platform**
    *   **Native Apps:** Developed specifically for one platform (iOS - Swift/Objective-C; Android - Kotlin/Java).
        *   Pros: Best performance, full access to device features, native look and feel.
        *   Cons: Separate codebases for each platform, higher development cost and time.
    *   **Web Apps (Progressive Web Apps - PWAs):** Websites designed to feel like apps, accessed via a browser.
        *   Pros: Single codebase, accessible on any device with a browser, no app store submission.
        *   Cons: Limited access to native device features, performance can vary, require internet connection (though PWAs can cache).
    *   **Hybrid Apps:** Web technologies (HTML, CSS, JS) wrapped in a native container (e.g., using Cordova, Ionic with Capacitor).
        *   Pros: Single codebase, access to some native features via plugins.
        *   Cons: Performance can be a bottleneck, UI might not feel fully native.
    *   **Cross-Platform Native Apps (The React Native Category):** Write code in one language (e.g., JavaScript for React Native, Dart for Flutter) that compiles/bridges to native UI components.
        *   Pros: Near-native performance, single codebase for much of the app, access to native features.
        *   Cons: Bridge performance can sometimes be an issue, might need native modules for complex features.
    *   <YouTube videoId="qlKj8Rg4cjo" title="Native vs Hybrid vs Cross-Platform vs PWA Apps by Academind" />
    *   <YouTube videoId_ MOBILE_APP_DEVELOPMENT_TYPES_OVERVIEW_by_DesignCourse title="Mobile App Development Types Overview by DesignCourse" /> (Placeholder for a comprehensive overview)

*   **Lesson 1.2: What is React Native? The "Learn Once, Write Anywhere" Philosophy**
    *   Definition: An open-source UI software framework created by Meta Platforms, Inc. It is used to develop applications for Android, Android TV, iOS, macOS, tvOS, Web, Windows, and UWP by enabling developers to use the React framework along with native platform capabilities.
    *   Core Idea: Uses JavaScript and React to build user interfaces with actual native UI components, not web views (like some hybrid apps).
    *   The JavaScript Bridge: How JS code communicates with native modules and UI elements. Understanding its role and potential performance implications.
    *   "Learn Once, Write Anywhere" vs. "Write Once, Run Anywhere": React Native aims to allow developers to use their React knowledge across platforms, but platform-specific code might still be needed for optimal experience or certain features.
    *   Key Advantages Revisited: Code reusability, faster development cycles, large community, hot reloading/fast refresh, access to native APIs.
    *   <YouTube videoId="0-S5a0eXPoc" title="React Native Explained in 100 Seconds by Fireship" /> (Recap)
    *   <YouTube videoId="6ZnfsJ6mM5c" title="What is React Native? And Why You Should Learn It by Programming with Mosh" /> (Recap)

*   **Lesson 1.3: React Native vs. Competitors (Flutter, NativeScript, Ionic, Xamarin)**
    *   **Flutter (by Google):** Uses Dart language, compiles to native code, provides its own rendering engine (Skia) and UI widgets.
        *   Pros: Excellent performance, beautiful UI, fast development.
        *   Cons: Dart language has a smaller community than JS, larger app sizes initially.
    *   **NativeScript:** Uses JavaScript/TypeScript, Angular/Vue. Allows direct access to native platform APIs.
    *   **Ionic (with Capacitor/Cordova):** Primarily web technologies in a web view, uses plugins for native features (more hybrid).
    *   **Xamarin (by Microsoft):** Uses C# and .NET, compiles to native apps. Good for enterprise and existing .NET shops.
    *   Brief comparison based on: Programming language, UI rendering, performance, community, ease of learning, native feature access.
    *   Why React Native might be a good choice for JS developers.
    *   <YouTube videoId="g4h4QkXkZ7A" title="React Native vs Flutter - Which is Best? (2023) by Fireship" />
    *   <YouTube videoId_ CROSS_PLATFORM_FRAMEWORK_COMPARISON_2023_by_NetNinja title="Cross-Platform Framework Comparison 2023 by The Net Ninja" /> (Placeholder: The Net Ninja often does good comparisons)

*   **Lesson 1.4: Setting Up Your Development Environment - Node.js, Watchman, JDK**
    *   **Node.js and npm/yarn:** JavaScript runtime and package managers. React Native uses Node.js to build your JS code and npm/yarn to manage project dependencies.
        *   Installing Node.js (LTS version recommended). Checking versions: `node -v`, `npm -v`.
        *   Understanding npm vs. yarn (common commands: `npm install`, `yarn add`).
    *   **Watchman (macOS/Linux):** A file watching service by Facebook, recommended for performance with React Native's bundler (Metro).
        *   Installation via Homebrew (macOS: `brew install watchman`) or from source (Linux).
    *   **Java Development Kit (JDK):** Required for Android development. React Native typically requires a specific version (e.g., JDK 11 or 17, check official React Native docs for current requirements).
        *   Installing OpenJDK or Oracle JDK.
        *   Setting `JAVA_HOME` environment variable and adding JDK's `bin` to PATH.
    *   <YouTube videoId_ INSTALL_NODEJS_NPM_YARN_FOR_REACT_NATIVE_by_Codevolution title="Install NodeJS, NPM, Yarn for React Native by Codevolution" /> (Placeholder: Codevolution often has setup guides)
    *   <YouTube videoId_ SETTING_UP_JDK_FOR_ANDROID_DEVELOPMENT_REACT_NATIVE_by_Programming领域 title="Setting up JDK for Android Development (React Native) by Programming领域" /> (Placeholder: Find a clear JDK setup video)

*   **Lesson 1.5: Choosing a Development Workflow - Expo CLI vs. React Native CLI (Bare Workflow)**
    *   **Expo CLI (Managed Workflow):**
        *   Pros: Easiest setup, managed native code (no need to touch Xcode/Android Studio for basic apps), Expo Go app for quick testing on devices, Over-The-Air (OTA) updates, many built-in APIs (camera, location, etc. via `expo install ...`).
        *   Cons: Limited access to custom native modules (need to "eject" or use EAS Build with custom native code), larger initial app size, some native features might not be available directly without specific Expo packages.
        *   Good for: Beginners, rapid prototyping, apps not needing complex custom native integrations, quicker start.
    *   **React Native CLI (Bare Workflow):**
        *   Pros: Full flexibility, direct access to native code (iOS/Android projects), can integrate any third-party native module, potentially smaller app sizes, more control over the build process.
        *   Cons: More complex setup (requires Android Studio/Xcode knowledge), longer build times, need to manage native dependencies and build processes manually.
        *   Good for: Apps with specific custom native requirements, experienced developers, teams with native expertise, long-term complex projects.
    *   EAS (Expo Application Services): Modern services from Expo that bridge the gap, allowing managed workflow apps to include custom native code and have more control over builds (EAS Build, EAS Submit, EAS Update).
    *   Recommendation for beginners to start with Expo CLI for this course.
    *   <YouTube videoId="00_hgtXrgqE" title="React Native Environment Setup - Expo vs React Native CLI by Academind" /> (Recap)
    *   <YouTube videoId_ EXPO_EAS_BUILD_INTRODUCTION_by_Expo_Team title="Expo EAS Build Introduction by Expo Team" /> (Placeholder for EAS overview from official Expo channel)

*   **Lesson 1.6: Setting Up for Android Development (Android Studio, Emulator, SDKs)**
    *   Installing Android Studio (official IDE for Android from Google).
    *   Understanding the Android SDK Manager within Android Studio:
        *   Installing necessary SDK Platforms (choose a recent Android API level).
        *   Installing SDK Tools (e.g., Android SDK Build-Tools, NDK (for some native modules), CMake, Android Emulator, Android SDK Platform-Tools).
    *   Configuring Environment Variables: `ANDROID_HOME` (or `ANDROID_SDK_ROOT`) and adding platform-tools to PATH.
    *   Creating an Android Virtual Device (AVD) / Emulator:
        *   Using AVD Manager in Android Studio.
        *   Choosing a device definition (Pixel, etc.).
        *   Selecting a system image (Android version - match SDK platform if possible).
        *   Configuring AVD settings (RAM, storage, graphics acceleration - use Hardware GLES 2.0 for better performance).
    *   Running the emulator and ensuring it's recognized by ADB (Android Debug Bridge - `adb devices`).
    *   Connecting a physical Android device for testing (Enable Developer Options and USB Debugging on the device).
    *   <YouTube videoId="JedpQRRqdSY" title="React Native Ultimate Setup Guide 2023 (Mac & Windows) by Code with Nader" /> (Focus on Android part)
    *   <YouTube videoId_ ANDROID_EMULATOR_SETUP_AND_OPTIMIZATION_by_The_Net_Ninja title="Android Emulator Setup and Optimization by The Net Ninja" /> (Placeholder: The Net Ninja for practical setup)

*   **Lesson 1.7: Setting Up for iOS Development (Xcode, Simulator, CocoaPods - macOS Only)**
    *   **macOS is required for iOS development.**
    *   Installing Xcode from the Mac App Store (official IDE for iOS). Includes iOS SDK, simulator, and necessary tools.
    *   Xcode Command Line Tools: Install via Xcode preferences or `xcode-select --install` in terminal.
    *   CocoaPods: Dependency manager for Swift and Objective-C Cocoa projects (React Native often uses it for linking native modules in Bare Workflow).
        *   Installation: `sudo gem install cocoapods`. Then `pod setup`.
    *   Creating an iOS Simulator:
        *   Via Xcode (Window > Devices and Simulators > Simulators).
        *   Choosing a device (iPhone, iPad model).
        *   Selecting an iOS version.
    *   Running the iOS Simulator.
    *   Connecting a physical iOS device for testing (requires an Apple Developer account, even a free one, for deploying to device).
    *   <YouTube videoId="JedpQRRqdSY" title="React Native Ultimate Setup Guide 2023 (Mac & Windows) by Code with Nader" /> (Focus on iOS part)
    *   <YouTube videoId_ IOS_SIMULATOR_VS_PHYSICAL_DEVICE_TESTING_REACT_NATIVE_by_Codevolution title="iOS Simulator vs Physical Device Testing React Native by Codevolution" /> (Placeholder: Codevolution for specific RN topics)

*   **Lesson 1.8: Creating Your First React Native App (Expo CLI and React Native CLI)**
    *   **Using Expo CLI:**
        *   `npm install -g expo-cli` (if not already installed, or `npx expo-cli@latest ...` for latest).
        *   `expo init MyExpoApp` (choose a template, e.g., "blank (TypeScript)" or "blank").
        *   `cd MyExpoApp`
        *   `npm start` or `expo start` (starts Metro Bundler, shows QR code and options).
        *   Running on Expo Go app on a physical device (scan QR code with camera or Expo Go app).
        *   Running on an Android emulator (press `a` in the terminal where Metro is running).
        *   Running on an iOS simulator (press `i` in the terminal).
    *   **Using React Native CLI (Bare Workflow):**
        *   `npx react-native@latest init MyBareApp`
        *   `cd MyBareApp`
        *   `npx react-native run-android` (for Android emulator/device).
        *   `npx react-native run-ios` (for iOS simulator/device - on macOS). (May need `pod install` in `ios` directory first).
    *   Understanding the initial project structure (brief overview of `App.js`/`App.tsx`, `node_modules`, `ios`, `android` folders).
    *   Hot Reloading / Fast Refresh: Seeing changes instantly in the app without a full rebuild.
    *   <YouTube videoId_ CREATE_REACT_NATIVE_APP_WITH_EXPO_STEP_BY_STEP_2023_by_Academind title="Create React Native App with Expo Step-by-Step 2023 by Academind" /> (Placeholder: Academind for clear tutorials)
    *   <YouTube videoId_ REACT_NATIVE_CLI_FIRST_APP_SETUP_AND_RUN_by_The_Net_Ninja title="React Native CLI First App Setup and Run by The Net Ninja" /> (Placeholder)

*   **Lesson 1.9: React Fundamentals - JSX (JavaScript XML) Deep Dive**
    *   Recap: JSX is a syntax extension for JavaScript that looks like HTML/XML.
    *   Transpilation: JSX is converted into `React.createElement()` calls by Babel.
        *   Example: `<MyComponent name="Test" />` becomes `React.createElement(MyComponent, {name: "Test"})`.
    *   Key JSX Rules Revisited & Expanded:
        *   **Single Root Element:** JSX expressions must have one parent element. Use `<View>` or Fragments (`<>...</>` or `<React.Fragment>...</>`).
        *   **CamelCase Attributes:** HTML attributes like `class` become `className`; `for` becomes `htmlFor` (in React DOM, not directly in React Native for `label` which doesn't exist as a core component). React Native props are generally camelCase.
        *   **JavaScript Expressions in `{}`:**
            *   Can embed any valid JS expression: variable, function call, arithmetic operation.
            *   Cannot use `if/else` statements directly in JSX, use ternary operators or logical `&&`.
            *   **Example:** `<Text>{user.name.toUpperCase()}</Text>`, `<Text>Score: {score * 10}</Text>`, `{isLoggedIn && <UserProfile />}`
        *   **Styling in JSX:** The `style` prop accepts a JavaScript object or an array of style objects.
            *   **Example:** `<View style={{ padding: 10, backgroundColor: 'lightblue' }}>`
        *   **Comments in JSX:** `{/* This is a JSX comment */}` (within curly braces).
        *   Self-closing tags for elements with no children: `<Image source={...} />`.
        *   Mapping arrays to JSX elements using `.map()`:
            ```javascript
            // const names = ["Alice", "Bob", "Charlie"];
            // <View>{names.map(name => <Text key={name}>{name}</Text>)}</View>
            // `key` prop is important for lists
            ```
    *   <YouTube videoId="SqcY0GlETPk" title="React JS Crash Course by Traversy Media" /> (Revisit JSX section with RN context)
    *   <YouTube videoId_ ADVANCED_JSX_PATTERNS_IN_REACT_NATIVE_by_Codevolution title="Advanced JSX Patterns in React Native by Codevolution" /> (Placeholder)

*   **Lesson 1.10: React Fundamentals - Components (Functional and Class-Based) In-Depth**
    *   Components are the core building blocks, reusable and independent pieces of UI.
    *   **Functional Components with Hooks (Modern Standard):**
        *   Simpler syntax, easier to read and test.
        *   Use React Hooks (`useState`, `useEffect`, `useContext`, etc.) to manage state and side effects.
        *   No `this` keyword complexities.
        *   **Example (with props destructuring):**
            ```javascript
            import React from 'react';
            import { Text, View, StyleSheet } from 'react-native';

            const UserCard = ({ name, email, isActive }) => { // Props destructuring
              return (
                <View style={styles.card}>
                  <Text style={styles.name}>{name}</Text>
                  <Text>{email}</Text>
                  {isActive && <Text style={styles.activeStatus}>Active</Text>}
                </View>
              );
            };
            // ... styles ...
            export default UserCard;
            ```
    *   **Class Components (Legacy, but still seen):**
        *   ES6 classes extending `React.Component` or `React.PureComponent`.
        *   `render()` method is required and returns JSX.
        *   Access props via `this.props`.
        *   Manage state with `this.state` (initialized in constructor) and update with `this.setState()`.
        *   Lifecycle methods (e.g., `componentDidMount`, `componentDidUpdate`, `componentWillUnmount`).
    *   Component Composition: Building complex UIs by combining smaller, specialized components.
    *   Exporting and Importing components between files.
    *   <YouTube videoId_ REACT_FUNCTIONAL_VS_CLASS_COMPONENTS_WHEN_TO_USE_by_Programming_with_Mosh title="React Functional vs Class Components: When To Use? by Programming with Mosh" /> (Placeholder)
    *   <YouTube videoId="Ke90Tje7VS0" title="React Native Tutorial for Beginners - Components, Props & State by The Net Ninja" /> (Revisit Components part)

*   **Lesson 1.11: React Fundamentals - Props Deep Dive (Validation, Default Props)**
    *   Recap: Props are read-only data passed from parent to child.
    *   Destructuring props in function parameters or at the beginning of the function body.
    *   `props.children`: Special prop to render content passed between component tags.
        *   **Example:** `<Card><Text>This is card content</Text></Card>` (Inside Card: `{props.children}`)
    *   **Default Props:** Providing default values for props if they are not supplied by the parent.
        *   Functional Components: `MyComponent.defaultProps = { propName: 'defaultValue' };` or using default parameter syntax: `function MyComponent({ name = "Guest" }) {...}`
        *   Class Components: `static defaultProps = { propName: 'defaultValue' };`
    *   **PropTypes (for JavaScript projects, less common with TypeScript):**
        *   Runtime type checking for props to catch bugs during development.
        *   `import PropTypes from 'prop-types';`
        *   `MyComponent.propTypes = { name: PropTypes.string.isRequired, age: PropTypes.number };`
        *   (TypeScript provides static type checking, which is generally preferred for new projects).
    *   Spreading props: `<Button {...buttonProps} />` (use with caution).
    *   <YouTube videoId_ REACT_PROPS_ADVANCED_CHILDREN_DEFAULTPROPS_PROPTYPES_by_Academind title="React Props Advanced: Children, defaultProps, PropTypes by Academind" /> (Placeholder)
    *   <YouTube videoId_ REACT_NATIVE_PROPS_IN_DEPTH_by_Codevolution title="React Native Props In-Depth by Codevolution" /> (Placeholder)

*   **Lesson 1.12: React Fundamentals - State Deep Dive (`useState` Hook)**
    *   Recap: State allows components to manage and update their own data, triggering re-renders.
    *   `useState` Hook:
        *   `const [value, setValue] = useState(initialValue);`
        *   `initialValue`: Can be a primitive, object, array, or a function that returns the initial value (lazy initialization, runs only once).
        *   `setValue`: The updater function.
            *   Can take a new value directly: `setValue(newValue);`
            *   Can take a function (updater function) if the new state depends on the previous state: `setValue(prevState => prevState + 1);` (This is the preferred way for state updates based on previous state to avoid issues with stale closures).
    *   State updates are asynchronous (batched by React for performance). Don't rely on state being updated immediately after calling `setValue`.
    *   Multiple `useState` calls for different pieces of state in a component.
    *   Managing object and array state:
        *   Treat state as immutable. When updating objects or arrays, create a new object/array with the changes rather than modifying the existing one directly.
        *   **Example (Object):** `setUser(prevUser => ({ ...prevUser, age: prevUser.age + 1 }));`
        *   **Example (Array):** `setItems(prevItems => [...prevItems, newItem]);`
    *   <YouTube videoId_ REACT_USESTATE_HOOK_COMPLETE_GUIDE_by_The_Net_Ninja title="React useState Hook Complete Guide by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId_ WORKING_WITH_OBJECTS_AND_ARRAYS_IN_REACT_STATE_by_Web_Dev_Simplified title="Working with Objects and Arrays in React State by Web Dev Simplified" /> (Placeholder)

*   **Lesson 1.13: React Native Core Components - `View`, `Text`, `Image` (Introduction)**
    *   React Native provides a set of essential, ready-to-use Core Components that map to native UI elements.
    *   **`<View>`:** The most fundamental component for building UI. A container that supports layout with Flexbox, styling, some touch handling, and accessibility controls.
        *   Analogous to `<div>` in web.
        *   Used to group other components.
    *   **`<Text>`:** A component for displaying text. Supports nesting, styling, and touch handling.
        *   All text in React Native must be inside a `<Text>` component. You cannot have bare text inside a `<View>`.
        *   Can be nested for different text styles within a block.
    *   **`<Image>`:** A component for displaying different types of images.
        *   `source` prop:
            *   Local static images: `source={require('./my-icon.png')}` (Metro bundler handles packaging).
            *   Network images: `source={{ uri: 'https://example.com/image.jpg' }}` (must specify width/height).
            *   Base64 encoded images.
        *   `style` prop for dimensions, `resizeMode` (`cover`, `contain`, `stretch`, `repeat`, `center`).
    *   Importing core components: `import { View, Text, Image } from 'react-native';`
    *   <YouTube videoId="R2zmjkE2B9Y" title="React Native Tutorial #6 - View, Text & StyleSheet by The Net Ninja" /> (Recap)
    *   <YouTube videoId="YjcLOhLcvQo" title="React Native Tutorial #7 - Images & Background Images by The Net Ninja" /> (Recap)

*   **Lesson 1.14: Handling User Input - `Button`, `TextInput`, `Switch`, `Slider` (Introduction)**
    *   **`<Button>`:** A basic, platform-styled button.
        *   Props: `title` (required), `onPress` (callback), `color` (Android), `disabled`. Limited styling.
    *   **`<TextInput>`:** (Covered in 1.12, recap key props like `value`, `onChangeText`, `placeholder`, `keyboardType`, `secureTextEntry`).
    *   **`<Switch>`:** A boolean input (on/off toggle).
        *   Props: `value` (boolean), `onValueChange` (callback), `trackColor`, `thumbColor`.
    *   **`<Slider>`:** (Community package often used, e.g., `@react-native-community/slider`). Allows selecting a value from a range.
        *   Props: `value`, `onValueChange`, `minimumValue`, `maximumValue`, `step`.
    *   Other input types (e.g., Pickers, DatePickers often come from community packages or platform-specific APIs).
    *   <YouTube videoId_ REACT_NATIVE_BUTTON_AND_TOUCHABLES_by_Academind title="React Native Button and Touchables by Academind" /> (Placeholder, focus on Button)
    *   <YouTube videoId_ REACT_NATIVE_SWITCH_COMPONENT_by_Codevolution title="React Native Switch Component by Codevolution" /> (Placeholder)

*   **Lesson 1.15: Platform-Specific Code (`Platform` module, `.ios.js`, `.android.js`)**
    *   Sometimes you need to write different code or apply different styles for iOS and Android.
    *   **`Platform` Module:** `import { Platform } from 'react-native';`
        *   `Platform.OS`: Returns `'ios'` or `'android'`.
        *   `Platform.Version`: Returns the OS version (string on Android, number on iOS).
        *   `Platform.select(specifics)`: An object where keys are platform names (`ios`, `android`, `native`, `default`) and values are the platform-specific values.
            *   **Example (Styles):** `paddingTop: Platform.OS === 'ios' ? 20 : 0`
            *   **Example (Values):** `const iconName = Platform.select({ ios: 'ios-cart', android: 'md-cart', default: 'cart' });`
    *   **Platform-Specific File Extensions:**
        *   Create files like `MyComponent.ios.js` and `MyComponent.android.js` (or `.ios.tsx` / `.android.tsx`).
        *   React Native's Metro bundler will automatically pick the correct file based on the platform when you import `MyComponent` (e.g., `import MyComponent from './MyComponent';`).
        *   Useful for larger chunks of platform-specific logic or entire component implementations.
    *   <YouTube videoId="H9DU4QcRakA" title="React Native Responsive UI & Platform Specific Code by The Net Ninja" /> (Focus on Platform module)
    *   <YouTube videoId_ REACT_NATIVE_PLATFORM_SPECIFIC_FILES_by_Codevolution title="React Native Platform Specific Files by Codevolution" /> (Placeholder)

---
### Module 2: Core React Native Components & Layout (Expanded)

This module explores essential React Native components and how to arrange them using Flexbox, with greater depth on each component and layout concept.

*   **Lesson 2.1: The `<View>` Component In-Depth**
    *   Recap: `<View>` as the fundamental building block for UI structure and layout.
    *   Nesting Views to create complex layouts and component hierarchies.
        *   **Example:** Building a card layout with nested Views for header, body, and footer sections.
        *   ` <View style={styles.card}><View style={styles.cardHeader}><Text>Title</Text></View><View style={styles.cardBody}><Text>Content...</Text></View></View> `
    *   Common props for `<View>`:
        *   `style`: Applying Flexbox, dimensions, colors, borders, margins, padding.
        *   Accessibility props: `accessible`, `accessibilityLabel` (read by screen readers), `accessibilityHint`, `accessibilityRole` (`button`, `header`, etc.).
        *   Touch handling props (`onStartShouldSetResponder`, etc. - lower level, `Pressable` is often preferred).
        *   `pointerEvents`: Controls if a view can be the target of touch events.
    *   `View` vs `SafeAreaView`: Understanding `SafeAreaView` for automatically handling notches, rounded corners, and status bars on iOS devices (and some Android).
    *   Performance considerations: Avoid deeply nested Views if not necessary; use `collapsable` prop for optimization where appropriate.
    *   <YouTube videoId_ REACT_NATIVE_VIEW_COMPONENT_DEEP_DIVE_by_Academind title="React Native View Component Deep Dive by Academind" /> (Placeholder: Academind for thorough explanations)
    *   <YouTube videoId_ REACT_NATIVE_SAFEAREAVIEW_EXPLAINED_by_Codevolution title="React Native SafeAreaView Explained by Codevolution" /> (Placeholder)

*   **Lesson 2.2: The `<Text>` Component In-Depth**
    *   Recap: `<Text>` for displaying all text content. Text must be within a `<Text>` component.
    *   Nesting `<Text>` components to apply different styles to parts of a text string.
        *   **Example:** `<Text>This is <Text style={{fontWeight: 'bold', color: 'red'}}>important</Text> and this is <Text style={{fontStyle: 'italic'}}>emphasized</Text>.</Text>`
        *   Styles are inherited by nested `<Text>` components unless overridden.
    *   Common props for `<Text>`:
        *   `style`: Font size, color, weight, family, alignment, line height, text decoration, etc.
        *   `numberOfLines`: Truncates text to a specific number of lines, often with an ellipsis.
        *   `ellipsizeMode`: (`head`, `middle`, `tail` (default), `clip`) How to display truncated text.
        *   `onPress`: Making text clickable (though `Pressable` around Text is often better for feedback and accessibility).
        *   `selectable`: Boolean, allows users to select text for copying.
        *   `adjustsFontSizeToFit` (iOS only): Reduces font size to fit within container.
        *   Accessibility props (`accessibilityLabel`, etc.).
    *   Text-specific styles: `textAlign` (`auto`, `left`, `right`, `center`, `justify`), `lineHeight`, `letterSpacing`, `textShadowColor`, `textShadowOffset` ({width, height}), `textShadowRadius`, `textTransform` (`none`, `uppercase`, `lowercase`, `capitalize`), `fontVariant` (e.g., `small-caps`).
    *   <YouTube videoId_ REACT_NATIVE_TEXT_COMPONENT_ADVANCED_FEATURES_by_The_Net_Ninja title="React Native Text Component Advanced Features by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId_ STYLING_TEXT_IN_REACT_NATIVE_by_UI_Dev_Simplified title="Styling Text in React Native by UI Dev Simplified" /> (Placeholder)

*   **Lesson 2.3: The `<Image>` Component and Image Handling**
    *   Recap: Displaying static, network, and base64 images.
    *   `source` prop details:
        *   `require('./path/to/image.png')`: For local static images. Bundler includes these in the app, manages scaling for different screen densities.
        *   `{ uri: 'https://...' }`: For network images. Must specify `width` and `height` in style for them to appear.
        *   `{ uri: 'data:image/png;base64,...' }`: For base64 encoded images.
        *   Can also pass an array of sources for image fallbacks: `source={[{uri: primaryUrl}, {uri: fallbackUrl}, require('./localFallback.png')]}`
    *   `resizeMode` prop:
        *   `cover`: Scales image to fill dimensions, maintaining aspect ratio, cropping if necessary.
        *   `contain`: Scales image to fit within dimensions, maintaining aspect ratio (may leave empty space).
        *   `stretch`: Scales image to fill dimensions, may distort aspect ratio.
        *   `repeat`: Repeats the image (rarely used for primary images, more for patterns).
        *   `center`: Centers the image within the frame if smaller, without scaling.
    *   `style` prop: `width`, `height`, `borderRadius`, `borderWidth`, `borderColor`, `opacity`, `tintColor` (for tinting template/monochromatic images).
    *   Loading indicators for network images using `<ActivityIndicator />` component and image `onLoadStart`/`onLoadEnd` props.
    *   Error handling for network images (`onError` prop).
    *   Using `<ImageBackground>` to display an image as a background for other components (children are rendered on top).
    *   SVG Images: Using libraries like `react-native-svg` for scalable vector graphics.
    *   <YouTube videoId="YjcLOhLcvQo" title="React Native Tutorial #7 - Images & Background Images by The Net Ninja" /> (Recap & expand)
    *   <YouTube videoId_ REACT_NATIVE_IMAGE_OPTIMIZATION_AND_LOADING_STATES_by_Codevolution title="React Native Image Optimization and Loading States by Codevolution" /> (Placeholder)
    *   <YouTube videoId_ USING_SVGS_IN_REACT_NATIVE_by_NotJustDev title="Using SVGs in React Native by NotJust.dev" /> (Placeholder)

*   **Lesson 2.4: `<ScrollView>` for Scrollable Content**
    *   When to use `<ScrollView>`: For a generic scrolling container that can host multiple components and views when content might exceed the screen height or width.
    *   Renders all its children at once, even those not currently visible. This can lead to performance issues for very long lists of items.
    *   Common props:
        *   `horizontal={true/false}`: For horizontal scrolling (default is vertical).
        *   `showsHorizontalScrollIndicator={boolean}`, `showsVerticalScrollIndicator={boolean}`: Show/hide scrollbars.
        *   `pagingEnabled` (iOS mainly): When true, the scroll view stops on multiples of the scroll view's size when scrolling.
        *   `keyboardDismissMode`: (`none`, `on-drag`, `interactive` (iOS)) How the keyboard dismisses when a scroll begins.
        *   `contentContainerStyle`: Styles the inner container that wraps all the ScrollView's children. Use this for padding within the scrollable area or for flexbox layout of children if needed.
        *   `stickyHeaderIndices={[index1, index2]}`: Makes children at specified indices stick to the top of the screen when scrolling.
    *   **Example:** A settings page with many options, or a horizontal gallery of a few items.
        ```javascript
        <ScrollView contentContainerStyle={{ padding: 20 }}>
          <Text style={styles.sectionTitle}>Profile Settings</Text>
          {/* ... many setting components ... */}
          <Text style={styles.sectionTitle}>Notification Settings</Text>
          {/* ... more setting components ... */}
        </ScrollView>
        ```
    *   Limitations for long lists (prefer `FlatList` or `SectionList` for better performance due to virtualization).
    *   <YouTube videoId_ REACT_NATIVE_SCROLLVIEW_TUTORIAL_AND_USE_CASES_by_Academind title="React Native ScrollView Tutorial and Use Cases by Academind" /> (Placeholder)

*   **Lesson 2.5: `<FlatList>` for Performant Lists - Basic Usage**
    *   Why `FlatList`? Virtualized list rendering – only renders items currently visible on screen (plus a small buffer area), significantly improving performance and memory usage for long lists.
    *   Required props:
        *   `data`: An array of data items to render (e.g., `[{id: '1', name: 'Item A'}, {id: '2', name: 'Item B'}]`).
        *   `renderItem`: A function that takes an object `{ item, index, separators }` and returns a React element for each item.
            *   `item`: The data object for the current row.
            *   `index`: The index of the current row.
    *   `keyExtractor`: A function that takes an item and its index and returns a unique string key for that item. Essential for React's reconciliation process to efficiently update the list.
        *   **Example:** `keyExtractor={(item, index) => item.id ? item.id.toString() : index.toString()}`
    *   **Basic Example:**
        ```javascript
        const DATA = [{id: 'bd7acbea', title: 'First Item'}, {id: '3ac68afc', title: 'Second Item'}, {id: '58694a0f', title: 'Third Item'}];
        const Item = ({ title }) => (<View style={styles.item}><Text style={styles.title}>{title}</Text></View>);

        const App = () => (
          <FlatList
            data={DATA}
            renderItem={({item}) => <Item title={item.title} />}
            keyExtractor={item => item.id}
          />
        );
        // ... styles for item, title ...
        ```
    *   <YouTube videoId_V6u38Lz4k" title="React Native FlatList & SectionList Tutorial by The Net Ninja" /> (Focus on FlatList basics)
    *   <YouTube videoId_ REACT_NATIVE_FLATLIST_FOR_BEGINNERS_by_Programming_with_Mosh title="React Native FlatList for Beginners by Programming with Mosh" /> (Placeholder)

*   **Lesson 2.6: `<FlatList>` - Advanced Props and Features**
    *   `ListHeaderComponent`, `ListFooterComponent`: Components to render at the beginning or end of the list respectively. Can be React components or functions returning components.
    *   `ItemSeparatorComponent`: A React component (or function returning one) to render between items (e.g., a divider line).
    *   `ListEmptyComponent`: Component to render if the `data` array is empty (e.g., a "No items found" message).
    *   `horizontal={true/false}`: For creating horizontal lists.
    *   `numColumns`: Renders items in multiple columns, creating a grid-like layout. `keyExtractor` might need adjustment. Items flow left-to-right, top-to-bottom.
    *   Pull-to-refresh:
        *   `onRefresh`: Callback function to execute when user pulls down to refresh.
        *   `refreshing`: Boolean prop to control the visibility of the refresh indicator.
    *   Infinite scrolling / loading more data:
        *   `onEndReached`: Callback function executed when the scroll position is within `onEndReachedThreshold` of the end of the content.
        *   `onEndReachedThreshold`: A number (0-1) indicating how far from the end (in terms of visible lengths) the bottom edge of the list must be to trigger `onEndReached`.
        *   Typically used to fetch more data and append it to the `data` prop.
    *   Performance props: `initialNumToRender`, `maxToRenderPerBatch`, `windowSize`, `updateCellsBatchingPeriod`.
    *   <YouTube videoId_ REACT_NATIVE_FLATLIST_ADVANCED_FEATURES_HEADER_FOOTER_SEPARATOR_by_Codevolution title="React Native FlatList Advanced Features (Header, Footer, Separator) by Codevolution" /> (Placeholder)
    *   <YouTube videoId_ REACT_NATIVE_FLATLIST_PULL_TO_REFRESH_INFINITE_SCROLL_by_NotJustDev title="React Native FlatList Pull to Refresh & Infinite Scroll by NotJust.dev" /> (Placeholder)

*   **Lesson 2.7: `<SectionList>` for Grouped/Sectioned Lists**
    *   Similar to `FlatList` but designed for rendering lists with logical sections (e.g., contacts grouped by letter, settings grouped by category, menu items grouped by course).
    *   Required props:
        *   `sections`: An array of section objects. Each section object must have a `data` array (items for that section) and typically other properties like `title` (or any data needed for `renderSectionHeader`).
            *   **Example `sections` structure:** `[{ title: 'Main Dishes', data: ['Pizza', 'Burger'] }, { title: 'Desserts', data: ['Cake', 'Ice Cream'] }]`
        *   `renderItem`: Function to render each item within a section (receives `{ item, index, section }`).
        *   `renderSectionHeader`: Function to render the header for each section (receives `{ section: { title, ...otherSectionData } }`).
    *   `keyExtractor` (for items, typically using item's unique ID or index within its section).
    *   **Example:**
        ```javascript
        const DATA = [
          { title: 'Fruits', data: ['Apple', 'Banana', 'Orange'] },
          { title: 'Vegetables', data: ['Carrot', 'Broccoli', 'Spinach'] },
        ];
        // ...
        <SectionList
          sections={DATA}
          keyExtractor={(item, index) => item + index}
          renderItem={({item}) => <View style={styles.item}><Text>{item}</Text></View>}
          renderSectionHeader={({section: {title}}) => <Text style={styles.header}>{title}</Text>}
        />
        ```
    *   Other props similar to `FlatList`: `stickySectionHeadersEnabled` (makes section headers stick to top during scroll), `ListHeaderComponent`, `ListFooterComponent`, etc.
    *   <YouTube videoId_V6u38Lz4k" title="React Native FlatList & SectionList Tutorial by The Net Ninja" /> (Focus on SectionList part)
    *   <YouTube videoId_ REACT_NATIVE_SECTIONLIST_IN_DEPTH_by_Academind title="React Native SectionList In-Depth by Academind" /> (Placeholder)

*   **Lesson 2.8: Introduction to Flexbox Layout in React Native - Main Concepts**
    *   Flexbox is the primary layout system in React Native. It's designed to provide a consistent layout on different screen sizes by distributing space among items.
    *   Core concepts are similar to web Flexbox, but with some key differences:
        *   `flexDirection` defaults to `column` in React Native (items stack vertically).
        *   `alignContent` defaults to `flex-start` (web default is `stretch`).
        *   `flex` property on children is a number, not a complex string like on web.
    *   **Flex Container:** Any `<View>` (or other component that supports layout) can become a flex container. While `display: 'flex'` is the default for `View`, being explicit or understanding this is good.
    *   **Flex Items:** Direct children of the flex container.
    *   **Main Axis:** Primary axis for item layout (determined by `flexDirection`).
    *   **Cross Axis:** Perpendicular to the main axis.
    *   <YouTube videoId="7fH4YRPADWc" title="React Native Flexbox Tutorial by Academind" /> (Recap and intro)
    *   <YouTube videoId_ FLEXBOX_IN_REACT_NATIVE_VS_WEB_KEY_DIFFERENCES_by_Codevolution title="Flexbox in React Native vs Web - Key Differences by Codevolution" /> (Placeholder)

*   **Lesson 2.9: Flexbox Container Properties in React Native - `flexDirection`, `justifyContent`, `alignItems`, `flexWrap`**
    *   **`flexDirection`:** (Default is `column` in React Native).
        *   `column`: Items stacked vertically. Main axis is top-to-bottom.
        *   `row`: Items arranged horizontally. Main axis is left-to-right.
        *   `column-reverse`: Items stacked vertically, bottom-to-top.
        *   `row-reverse`: Items arranged horizontally, right-to-left.
    *   **`justifyContent`:** Aligns children along the main axis.
        *   Values: `flex-start` (default for column, start for row), `flex-end`, `center`, `space-between`, `space-around`, `space-evenly`.
    *   **`alignItems`:** Aligns children along the cross axis (within a single line).
        *   Values: `stretch` (default), `flex-start`, `flex-end`, `center`, `baseline`.
    *   **`flexWrap`:** Controls if items wrap to new lines if they overflow the container.
        *   `nowrap` (default): Items may overflow.
        *   `wrap`: Items wrap to the next line.
        *   `wrap-reverse`.
    *   Practical examples of combining these for common UI patterns (e.g., centering content, distributing items horizontally/vertically).
    *   <YouTube videoId_ REACT_NATIVE_FLEXBOX_CONTAINER_PROPERTIES_IN_DETAIL_by_The_Net_Ninja title="React Native Flexbox Container Properties In Detail by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId_ MASTERING_JUSTIFYCONTENT_AND_ALIGNITEMS_IN_REACT_NATIVE_by_UI_Dev_Simplified title="Mastering justifyContent and alignItems in React Native by UI Dev Simplified" /> (Placeholder)

*   **Lesson 2.10: Flexbox Item Properties in React Native - `flex`, `alignSelf`, `flexGrow`, `flexShrink`, `flexBasis`**
    *   **`flex` (on a flex item):** A number that defines how an item should grow or shrink to fill available space along the main axis.
        *   `flex: <positive_number>`: The item will take up a proportion of the available space relative to other flex items with a `flex` value. Example: If item A has `flex: 2` and item B has `flex: 1`, A will take 2/3 of the space and B will take 1/3.
        *   If `flex: 0`, the item sizes based on its `width`/`height` (or content).
        *   If `flex: -1`, the item sizes based on `width`/`height`, but shrinks if needed, down to `minWidth`/`minHeight`.
        *   This is a shorthand for `flexGrow`, `flexShrink`, and `flexBasis`. In React Native, `flex: N` typically means `flexGrow: N, flexShrink: 1, flexBasis: '0%'` (Note: `flexBasis` default behavior with `flex` shorthand can be tricky, often better to be explicit if needed).
    *   **`alignSelf`:** Overrides the `alignItems` value for an individual flex item.
        *   Values: `auto` (default), `stretch`, `flex-start`, `flex-end`, `center`, `baseline`.
    *   **`flexGrow` (number):** How much an item can grow relative to other items. Default 0.
    *   **`flexShrink` (number):** How much an item can shrink relative to other items if there isn't enough space. Default 1 (for items in a `View` with `flexDirection: 'row'`).
    *   **`flexBasis` (number, percentage, or 'auto'):** Default size of an item along the main axis before `flexGrow` or `flexShrink` distribute space. `'auto'` means use `width`/`height` property.
    *   <YouTube videoId_ REACT_NATIVE_FLEXBOX_ITEM_PROPERTIES_FLEX_GROW_SHRINK_BASIS_by_Codevolution title="React Native Flexbox Item Properties (flexGrow, flexShrink, flexBasis) by Codevolution" /> (Placeholder)
    *   <YouTube videoId_ UNDERSTANDING_THE_FLEX_PROPERTY_IN_REACT_NATIVE_by_Academind title="Understanding the 'flex' Property in React Native by Academind" /> (Placeholder)

*   **Lesson 2.11: Absolute vs. Relative Positioning in React Native**
    *   React Native supports `position: 'absolute'` and `position: 'relative'` (which is the default for all components).
    *   **`position: 'relative'`:** Element is positioned according to normal Flexbox flow. `top`, `bottom`, `left`, `right` offset it from its normal calculated position without affecting the layout of other elements. Its original space is still reserved.
    *   **`position: 'absolute'`:** Element is removed from normal Flexbox flow. It does not affect the position of its siblings (they fill its original space).
        *   Positioned relative to its nearest ancestor that has `position: 'relative'` or `position: 'absolute'`.
        *   If no such ancestor, positioned relative to the root container (the screen or main view).
        *   Offset properties (`top`, `bottom`, `left`, `right`, `start`, `end`) define its position from the edges of its containing block.
    *   Use cases: Overlays (modals, tooltips), badges on icons, floating action buttons, custom UI elements that need precise placement.
    *   `zIndex` (number): Can be used with positioned elements to control stacking order (higher `zIndex` appears on top). Works on both iOS and Android.
    *   <YouTube videoId_ REACT_NATIVE_POSITIONING_ABSOLUTE_VS_RELATIVE_IN_DEPTH_by_Academind title="React Native Positioning (Absolute vs Relative) In-Depth by Academind" /> (Placeholder)
    *   <YouTube videoId_ ZINDEX_IN_REACT_NATIVE_by_UI_Dev_Simplified title="zIndex in React Native by UI Dev Simplified" /> (Placeholder)

*   **Lesson 2.12: Working with Dimensions - `width`, `height`, `min/max`, `Dimensions` API, `useWindowDimensions` Hook**
    *   Setting fixed `width` and `height` (in density-independent pixels - dp).
    *   Using percentages for `width` and `height` (e.g., `'50%'` - relative to parent's dimension).
    *   `minWidth`, `maxWidth`, `minHeight`, `maxHeight` to constrain dimensions.
    *   The `Dimensions` API: `import { Dimensions } from 'react-native';`
        *   `Dimensions.get('window')`: Returns `{ width, height, scale, fontScale }` of the app window (excluding status bar on Android, can change with rotation).
        *   `Dimensions.get('screen')`: Returns dimensions of the entire device screen (includes status bar, less likely to change).
        *   This API gives static values at the time of call. For dynamic updates on dimension changes (like rotation), an event listener is needed.
    *   `useWindowDimensions` Hook (Recommended for functional components): `import { useWindowDimensions } from 'react-native';`
        *   `const { height, width, scale, fontScale } = useWindowDimensions();`
        *   Automatically updates component when screen dimensions change (e.g., device rotation).
    *   Creating responsive layouts based on screen/window size using these values.
    *   <YouTube videoId_ REACT_NATIVE_DIMENSIONS_API_VS_USEWINDOWDIMENSIONS_HOOK_by_The_Net_Ninja title="React Native Dimensions API vs useWindowDimensions Hook by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId_ RESPONSIVE_DESIGN_IN_REACT_NATIVE_USING_DIMENSIONS_by_Codevolution title="Responsive Design in React Native using Dimensions by Codevolution" /> (Placeholder)

*   **Lesson 2.13: Touchable Components for User Interaction - `TouchableOpacity`, `TouchableHighlight`, `TouchableWithoutFeedback`, `Pressable`**
    *   These components provide ways to capture touch events and give visual feedback, making any View interactive.
    *   **`<TouchableOpacity>`:** Wraps its children. On press, the opacity of the wrapped view is animated (decreased then restored). Good for general purpose buttons or interactive areas.
    *   **`<TouchableHighlight>`:** Wraps its children. On press, the background of the wrapped view darkens or changes color (controlled by `underlayColor` prop). Must have exactly one child View. Good for list items or buttons where a highlight is desired.
    *   **`<TouchableWithoutFeedback>`:** Provides no visual feedback on press. Useful for custom feedback implemented manually or when no visual feedback is desired (e.g., dismissing a modal by tapping outside, or an invisible touch target).
    *   **`<Pressable>` (Recommended modern approach):** More versatile and provides more states and feedback options.
        *   `onPressIn`, `onPressOut`, `onLongPress`, `onPress`.
        *   `style` prop can be a function `(state) => styleObject` where `state.pressed` (boolean) can be used to change styles dynamically when pressed (e.g., `style={({ pressed }) => ({ opacity: pressed ? 0.5 : 1 })}`).
        *   Can provide feedback for `hover` and `focus` states on platforms that support them (e.g., TV, Web).
        *   More fine-grained control over `hitSlop` (area outside element that can trigger a press).
    *   Common props: `onPress` (primary action), `onLongPress`, `disabled`, `hitSlop`.
    *   <YouTube videoId="Gc2ygs7n9hY" title="React Native Touchable Components & Pressable API by The Net Ninja" /> (Recap and expand)
    *   <YouTube videoId_ REACT_NATIVE_PRESSABLE_VS_TOUCHABLES_by_Academind title="React Native Pressable vs Touchables by Academind" /> (Placeholder)

*   **Lesson 2.14: Building a Simple UI Layout - Example Project (e.g., Product Card or Social Media Post)**
    *   Combining `View`, `Text`, `Image`, and Flexbox to create a common UI pattern like a product card or a social media post.
    *   Step-by-step construction:
        *   Main container View (`flex: 1` if it's a screen).
        *   Image section (e.g., product image, user avatar) with appropriate `resizeMode`.
        *   Text content section (e.g., product name/price, post text, user name) using nested `<Text>` for different styles.
        *   Action button section (e.g., "Add to Cart", Like/Comment/Share buttons) using `Pressable` or `TouchableOpacity`, laid out with Flexbox (e.g., `flexDirection: 'row', justifyContent: 'space-around'`).
    *   Focus on applying Flexbox properties (`flexDirection`, `justifyContent`, `alignItems`, `flex`) to achieve the desired layout for different sections.
    *   Using `StyleSheet.create` for organizing styles: margins, paddings, borders, colors, font styles.
    *   Nesting Views and applying margins/paddings for spacing and structure.
    *   <YouTube videoId_ REACT_NATIVE_BUILD_A_PRODUCT_CARD_UI_by_CodeWithChris title="React Native - Build a Product Card UI by CodeWithChris" /> (Placeholder for a practical layout example)
    *   <YouTube videoId_ REACT_NATIVE_LAYOUT_CHALLENGE_SOCIAL_MEDIA_POST_by_UI_Dev_Simplified title="React Native Layout Challenge: Social Media Post by UI Dev Simplified" /> (Placeholder)

*   **Lesson 2.15: Introduction to `Modal` Component for Overlays**
    *   The `<Modal>` component: Presents content on top of an enclosing view. It's a way to display temporary UI that requires user interaction or attention.
    *   Common use cases: Alerts, pop-up dialogs, full-screen takeovers for forms or specific tasks (e.g., image picker, confirmation dialogs).
    *   Props:
        *   `visible` (boolean): Controls whether the modal is visible or not (this is typically managed by a state variable).
        *   `animationType`: How the modal appears/disappears (`slide` from bottom, `fade`, `none`).
        *   `transparent` (boolean): If true, the modal will have a transparent background, allowing underlying content to be seen (often used with a semi-transparent overlay View inside the modal for styling).
        *   `onRequestClose` (Android specific): Callback for when the hardware back button is pressed. You should typically set `visible` to `false` in this callback.
        *   `onShow`, `onDismiss` (callbacks for when modal finishes appearing/disappearing).
        *   `presentationStyle` (iOS specific): `fullScreen`, `pageSheet`, `formSheet`.
    *   Basic structure:
        ```javascript
        // const [modalVisible, setModalVisible] = useState(false);
        // <Modal
        //   animationType="slide"
        //   transparent={true}
        //   visible={modalVisible}
        //   onRequestClose={() => {
        //     Alert.alert("Modal has been closed.");
        //     setModalVisible(!modalVisible);
        //   }}
        // >
        //   <View style={styles.centeredView}> // Style to center modal content
        //     <View style={styles.modalView}> // Style for the modal box itself
        //       <Text style={styles.modalText}>Hello World!</Text>
        //       <Pressable style={[styles.button, styles.buttonClose]} onPress={() => setModalVisible(!modalVisible)}>
        //         <Text style={styles.textStyle}>Hide Modal</Text>
        //       </Pressable>
        //     </View>
        //   </View>
        // </Modal>
        // <Pressable style={[styles.button, styles.buttonOpen]} onPress={() => setModalVisible(true)}>
        //   <Text style={styles.textStyle}>Show Modal</Text>
        // </Pressable>
        ```
    *   Styling the modal content View (e.g., centering it, adding background, shadow, rounded corners).
    *   <YouTube videoId_ REACT_NATIVE_MODAL_COMPONENT_TUTORIAL_by_The_Net_Ninja title="React Native Modal Component Tutorial by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId_ CREATING_CUSTOM_MODALS_IN_REACT_NATIVE_by_Codevolution title="Creating Custom Modals in React Native by Codevolution" /> (Placeholder)

---
### Module 3: Navigation in React Native (Expanded)

This module covers how to implement navigation between different screens in your React Native application using React Navigation, with expanded detail.

*   **Lesson 3.1: Introduction to React Navigation - Why and What**
    *   Why is navigation essential in mobile apps? Users expect to move between different views/screens seamlessly.
    *   Challenges of implementing navigation from scratch (managing history stack, transitions, platform consistency).
    *   Overview of React Navigation library: The community-standard, most popular solution for navigation in React Native.
        *   Provides a collection of navigators (Stack, Tab, Drawer).
        *   JavaScript-based, highly customizable.
        *   Supports iOS and Android platform conventions.
    *   Core concepts:
        *   **Navigators:** Components that define the navigation structure (e.g., how screens transition).
        *   **Screens:** Individual components representing a view in your app.
        *   **Navigation Props:** Props passed down to screens by navigators, allowing them to dispatch navigation actions (e.g., `navigation.navigate()`).
        *   **Route Props:** Props passed down to screens containing information about the current route (e.g., `route.params`).
    *   Alternatives (brief mention, e.g., React Native Navigation by Wix - more native-driven).
    *   <YouTube videoId="9yYn1WDA32Y" title="React Navigation 5 - Crash Course by Traversy Media" /> (Note: Version might be slightly old, focus on concepts. Latest is v6+)
    *   Official Docs: [React Navigation Docs](https://reactnavigation.org/docs/getting-started) (Emphasize this as the primary source of truth).

*   **Lesson 3.2: Installing React Navigation and Core Dependencies**
    *   Installing the core library: `npm install @react-navigation/native` or `yarn add @react-navigation/native`.
    *   Installing peer dependencies (vary based on Expo or Bare RN project):
        *   **Expo managed projects:** `expo install react-native-screens react-native-safe-area-context`
        *   **Bare React Native projects:** `npm install react-native-screens react-native-safe-area-context` or `yarn add ...`
            *   Additional steps for Bare RN: Linking (mostly automatic now, but may need `pod install` for iOS).
    *   `react-native-screens`: Uses native navigation primitives for better performance.
    *   `react-native-safe-area-context`: Handles safe areas (notches, status bars).
    *   Wrapping your root app component with `NavigationContainer`.
        ```javascript
        // App.js
        import * as React from 'react';
        import { NavigationContainer } from '@react-navigation/native';

        export default function App() {
          return (
            <NavigationContainer>{/* Rest of your app code */}</NavigationContainer>
          );
        }
        ```
    *   <YouTube videoId_ REACT_NAVIGATION_V6_SETUP_AND_INSTALLATION_by_Codevolution title="React Navigation v6 Setup and Installation by Codevolution" /> (Placeholder for a v6 setup video)
    *   <YouTube videoId_ GETTING_STARTED_WITH_REACT_NAVIGATION_by_React_Native_School title="Getting Started with React Navigation by React Native School" /> (Placeholder)

*   **Lesson 3.3: Stack Navigator - Basic Setup and Navigation**
    *   What is a Stack Navigator? Manages a stack of screens, where new screens are pushed on top and can be popped off (like a browser history).
    *   Common use case: Navigating from a list to a detail screen.
    *   Installation: `npm install @react-navigation/stack` or `yarn add @react-navigation/stack`. (And `react-native-gesture-handler` if not already present).
    *   Creating a Stack Navigator: `import { createStackNavigator } from '@react-navigation/stack'; const Stack = createStackNavigator();`
    *   Defining Screens within the navigator:
        ```javascript
        // Inside NavigationContainer
        <Stack.Navigator initialRouteName="Home">
          <Stack.Screen name="Home" component={HomeScreen} options={{ title: 'Overview' }} />
          <Stack.Screen name="Details" component={DetailsScreen} />
        </Stack.Navigator>
        ```
        *   `name`: Unique name for the route.
        *   `component`: The React component to render for this screen.
        *   `options`: Configuration for the screen (e.g., header title).
    *   Navigating between screens:
        *   The `navigation` prop is passed to each screen component.
        *   `navigation.navigate('RouteName')`: Pushes a new screen if not already in stack, or jumps to it if it exists.
        *   `navigation.push('RouteName')`: Always pushes a new screen onto the stack, even if it's already present (useful for multiple instances of the same screen type).
    *   Going back: `navigation.goBack()` or `navigation.pop()` (removes current screen from stack), `navigation.popToTop()` (goes to first screen in stack).
    *   <YouTube videoId="NYSN-OV_FRs" title="React Navigation - Stack Navigator Tutorial by Academind" /> (Adapt for v6 if needed)

*   **Lesson 3.4: Stack Navigator - Passing Parameters to Routes**
    *   Why pass parameters? To send data from one screen to another (e.g., an item ID to a detail screen).
    *   Passing parameters with `navigation.navigate()` or `navigation.push()`:
        *   `navigation.navigate('Details', { itemId: 86, otherParam: 'anything' });` (Second argument is an object of params).
    *   Accessing parameters in the screen component:
        *   The `route` prop is passed to each screen component.
        *   `route.params`: An object containing the passed parameters.
        *   **Example (DetailsScreen):**
            ```javascript
            function DetailsScreen({ route, navigation }) {
              const { itemId, otherParam } = route.params; // Destructure params
              return (
                <View><Text>Details Screen for Item ID: {itemId}</Text></View>
              );
            }
            ```
    *   Setting initial params for a screen in the navigator definition: `<Stack.Screen name="Details" component={DetailsScreen} initialParams={{ itemId: 42 }} />`
    *   Updating params: `navigation.setParams({ newParam: 'value' });` (use with caution, can make state harder to track).
    *   Type checking params with TypeScript.
    *   <YouTube videoId_ REACT_NAVIGATION_PASSING_PARAMETERS_TO_SCREENS_by_The_Net_Ninja title="React Navigation - Passing Parameters to Screens by The Net Ninja" /> (Placeholder)

*   **Lesson 3.5: Stack Navigator - Configuring the Header Bar**
    *   The Stack Navigator provides a default header bar (navbar).
    *   Screen-specific header options (passed via `options` prop on `Stack.Screen`):
        *   `title`: Sets the header title text.
        *   `headerStyle`: Object for styling the header background (e.g., `backgroundColor`).
        *   `headerTintColor`: Color for the back button and title text.
        *   `headerTitleStyle`: Object for styling the title text (font, size, etc.).
        *   `headerShown: false`: To hide the header for a specific screen.
        *   `headerLeft`: Function returning a React element for a custom left component (e.g., custom back button, drawer toggle).
        *   `headerRight`: Function returning a React element for custom right components (e.g., action buttons).
        *   `headerTitle`: Function returning a React element for a custom title component (e.g., an image or complex layout).
            *   **Example (Custom Right Button):**
                ```javascript
                options={{
                  headerRight: () => (
                    <Button onPress={() => alert('Info Pressed!')} title="Info" />
                  )
                }}
                ```
    *   Setting default options for all screens in the navigator: `Stack.Navigator`'s `screenOptions` prop.
    *   Using `navigation.setOptions()` from within a screen component to dynamically update header options based on state or props.
    *   Platform-specific header styles (e.g., title alignment).
    *   <YouTube videoId_ REACT_NAVIGATION_CUSTOMIZING_HEADER_BAR_ADVANCED_by_Codevolution title="React Navigation - Customizing the Header Bar (Advanced) by Codevolution" /> (Placeholder)

*   **Lesson 3.6: Tab Navigator - Bottom Tabs (`@react-navigation/bottom-tabs`)**
    *   What is a Tab Navigator? Displays a set of tabs (usually at the bottom of the screen on mobile) to switch between different primary sections or views of an app.
    *   Installation: `npm install @react-navigation/bottom-tabs` or `yarn add ...`.
    *   Creating a Bottom Tab Navigator: `import { createBottomTabNavigator } from '@react-navigation/bottom-tabs'; const Tab = createBottomTabNavigator();`
    *   Defining tab screens within `Tab.Navigator`:
        ```javascript
        // Inside NavigationContainer
        <Tab.Navigator
          screenOptions={({ route }) => ({
            tabBarIcon: ({ focused, color, size }) => { /* return Icon component */ },
            tabBarActiveTintColor: 'tomato',
            tabBarInactiveTintColor: 'gray',
            headerShown: false, // Often hide individual tab screen headers if a global header exists
          })}
        >
          <Tab.Screen name="Feed" component={FeedScreen} options={{ tabBarLabel: 'Home' }} />
          <Tab.Screen name="Messages" component={MessagesScreen} options={{ tabBarBadge: 3 }} />
        </Tab.Navigator>
        ```
    *   Customizing tab icons and labels:
        *   `tabBarIcon`: Function that receives `{ focused: boolean, color: string, size: number }` and returns a React element (e.g., an Icon component from `react-native-vector-icons` or a custom component).
        *   `tabBarLabel`: String or function returning a React element.
        *   `tabBarActiveTintColor`, `tabBarInactiveTintColor`, `tabBarStyle`, `tabBarLabelStyle`, `tabBarItemStyle`.
    *   Displaying Badges on tab icons (`tabBarBadge` option).
    *   <YouTube videoId="fRDf5nK_pgA" title="React Navigation - Tab Navigator Tutorial by Academind" /> (Adapt for v6 if needed)
    *   <YouTube videoId_ REACT_NATIVE_BOTTOM_TAB_NAVIGATION_WITH_ICONS_AND_BADGES_by_The_Net_Ninja title="React Native Bottom Tab Navigation with Icons and Badges by The Net Ninja" /> (Placeholder)

*   **Lesson 3.7: Tab Navigator - Material Top Tabs (`@react-navigation/material-top-tabs`)**
    *   Displays tabs at the top of the screen, typically under a header, often swipeable between screens.
    *   Common for secondary navigation within a section (e.g., "Chats", "Status", "Calls" in WhatsApp).
    *   Installation: `npm install @react-navigation/material-top-tabs react-native-tab-view react-native-pager-view` (Note: `react-native-pager-view` is a peer dependency).
    *   Creating a Material Top Tab Navigator: `import { createMaterialTopTabNavigator } from '@react-navigation/material-top-tabs'; const TopTab = createMaterialTopTabNavigator();`
    *   Defining screens and customizing options similar to Bottom Tabs but with specific Material Top Tab options:
        *   `tabBarLabel`, `tabBarIcon`.
        *   `tabBarIndicatorStyle` (for the underline indicator).
        *   `tabBarStyle` (for the tab bar container).
        *   `swipeEnabled` (boolean, default true).
        *   `tabBarScrollEnabled` (if many tabs).
    *   <YouTube videoId_ REACT_NATIVE_MATERIAL_TOP_TAB_NAVIGATOR_TUTORIAL_by_The_Net_Ninja title="React Native Material Top Tab Navigator Tutorial by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId_ CUSTOMIZING_MATERIAL_TOP_TABS_IN_REACT_NATIVE_by_Codevolution title="Customizing Material Top Tabs in React Native by Codevolution" /> (Placeholder)

*   **Lesson 3.8: Drawer Navigator (`@react-navigation/drawer`)**
    *   What is a Drawer Navigator? Provides a navigation drawer that slides in from the side (usually left, but configurable) of the screen.
    *   Common for main app navigation, settings, profile links, less frequently accessed screens.
    *   Installation: `npm install @react-navigation/drawer react-native-gesture-handler react-native-reanimated` (Gesture Handler and Reanimated are crucial peer dependencies).
        *   **Important Setup:** Ensure `react-native-gesture-handler` is imported at the very top of your entry file (e.g., `App.js` or `index.js`): `import 'react-native-gesture-handler';`
        *   Additional setup for Reanimated v2+ might be needed (Babel plugin in `babel.config.js`).
    *   Creating a Drawer Navigator: `import { createDrawerNavigator } from '@react-navigation/drawer'; const Drawer = createDrawerNavigator();`
    *   Defining drawer screens.
    *   Opening/closing the drawer:
        *   Swipe gesture from the edge.
        *   Programmatically: `navigation.openDrawer()`, `navigation.closeDrawer()`, `navigation.toggleDrawer()`. Often done via a hamburger icon button in the header of screens within the drawer.
    *   Customizing drawer content: `drawerContent` prop takes a function that returns custom JSX for the drawer's entire content area.
    *   Drawer options: `drawerType` (`front`, `back`, `slide`, `permanent`), `drawerStyle`, `drawerLabelStyle`, `drawerActiveTintColor`, `drawerInactiveTintColor`, `drawerIcon`.
    *   <YouTube videoId="hSTTa2QHT6Y" title="React Navigation - Drawer Navigator Tutorial by Academind" /> (Adapt for v6 if needed)
    *   <YouTube videoId_ REACT_NATIVE_CUSTOM_DRAWER_NAVIGATOR_by_NotJustDev title="React Native Custom Drawer Navigator by NotJust.dev" /> (Placeholder)

*   **Lesson 3.9: Nesting Navigators (e.g., Stack inside Tab, Tab inside Drawer)**
    *   Complex apps often require nesting different types of navigators to achieve desired UI/UX flows.
    *   **Example: Stack Navigator inside each Tab screen:**
        *   Each tab (e.g., Home, Profile) can have its own independent stack of screens.
        *   The `component` prop of a `Tab.Screen` would be the Stack Navigator component itself.
        *   You'd typically hide the header of the screen containing the nested Stack Navigator: `options={{ headerShown: false }}` on the `Tab.Screen`.
    *   **Example: Tab Navigator inside a Drawer screen:**
        *   A drawer item might open a screen that itself contains a Tab Navigator.
    *   **Example: Stack Navigator as the root, with a Drawer Navigator nested inside for some screens, and Tab Navigators nested further.**
    *   Understanding how navigation actions (`navigate`, `goBack`) behave within nested structures. `navigation.navigate('ScreenName')` will try to find `ScreenName` in the current navigator. If not found, it might bubble up if the current navigator is nested.
    *   Navigating to a screen in a *different* or *nested* navigator: `navigation.navigate('ParentNavigatorName', { screen: 'ChildScreenName', params: { ... } });`
    *   <YouTube videoId_ REACT_NAVIGATION_NESTING_NAVIGATORS_STACK_TAB_DRAWER_by_Codevolution title="React Navigation: Nesting Navigators (Stack, Tab, Drawer) by Codevolution" /> (Placeholder)
    *   <YouTube videoId_ COMPLEX_NAVIGATION_STRUCTURES_IN_REACT_NATIVE_by_Spencer_Carli title="Complex Navigation Structures in React Native by Spencer Carli" /> (Placeholder)

*   **Lesson 3.10: The `navigation` Prop In-Depth (Methods and Helpers)**
    *   Every screen component rendered by a React Navigation navigator receives the `navigation` prop.
    *   Key `navigation` methods:
        *   `navigate('RouteName', params)`: Go to a screen. Smart - if screen is already on stack, it might go back. Pass params to the target screen.
        *   `push('RouteName', params)`: (Stack only) Always adds a new screen to the top of the stack, even if it's already there.
        *   `goBack()`: Navigates back to the previous screen in the stack or closes an open drawer/modal.
        *   `pop(count)`: (Stack only) Goes back `count` screens in the stack. `pop(1)` is like `goBack()`.
        *   `popToTop()`: (Stack only) Goes to the very first screen in the stack, dismissing all others.
        *   `replace('RouteName', params)`: (Stack only) Replaces the current screen with a new one. The current screen is removed from the stack (user can't go back to it). Useful for post-login flows.
        *   `reset(state)`: Wipes the entire navigation state and replaces it with the result of the `state` object. Used for complex state changes like auth flows.
        *   `setParams(params)`: Updates the params of the current screen. Merges with existing params.
        *   `setOptions(options)`: Update the screen's options (e.g., header title, header buttons) dynamically from within the component.
        *   `isFocused()`: Returns `true` if the screen is currently focused. (Often better to use `useIsFocused` hook for reactivity).
        *   Drawer specific: `openDrawer()`, `closeDrawer()`, `toggleDrawer()`.
        *   Tab specific: `jumpTo('TabName', params)`.
    *   Using the `useNavigation` hook in child components (that are not direct screens) to get access to the `navigation` object. `import { useNavigation } from '@react-navigation/native'; const navigation = useNavigation();`
    *   <YouTube videoId_ REACT_NAVIGATION_NAVIGATION_PROP_ALL_METHODS_EXPLAINED_by_The_Net_Ninja title="React Navigation - Navigation Prop All Methods Explained by The Net Ninja" /> (Placeholder)

*   **Lesson 3.11: The `route` Prop In-Depth (Accessing Params and Screen Info)**
    *   Every screen component also receives the `route` prop, containing information specific to that instance of the screen.
    *   Key `route` properties:
        *   `route.key`: A unique string key for this route instance. Useful for React `key` props if rendering a list of routes.
        *   `route.name`: The name of the route as defined in the navigator configuration (e.g., "Details").
        *   `route.params`: An object containing parameters passed to this route via `navigation.navigate('Details', { userId: 123 })` or `initialParams`.
            *   Access with optional chaining and default values: `const userId = route.params?.userId ?? 'defaultUser';`
    *   Using the `useRoute` hook in child components (that are not direct screens) to get access to the `route` object for the current screen. `import { useRoute } from '@react-navigation/native'; const route = useRoute();`
    *   TypeScript: Defining types for `route.params` for better type safety.
    *   <YouTube videoId_ REACT_NAVIGATION_ROUTE_PROP_AND_USEROUTE_HOOK_by_Academind title="React Navigation - Route Prop and useRoute Hook by Academind" /> (Placeholder)

*   **Lesson 3.12: Navigation Lifecycle Events & `useFocusEffect` / `useIsFocused` Hooks**
    *   Listening to screen focus/blur events to perform actions (e.g., fetch data when screen appears, analytics, start/stop background tasks).
    *   Using the `navigation.addListener('eventName', callback)` method:
        *   Common events:
            *   `focus`: Fired when the screen comes into focus.
            *   `blur`: Fired when the screen loses focus.
            *   `state`: Fired when the navigation state changes (e.g., new screen pushed, popped).
            *   `beforeRemove`: Fired when the user is trying to leave the screen (e.g., via back button or `goBack()`). Can be used to prevent navigation by calling `event.preventDefault()`, e.g., to show a "Discard changes?" dialog.
        *   Remember to unsubscribe listeners in a cleanup effect to prevent memory leaks.
    *   **`useIsFocused` Hook:** `import { useIsFocused } from '@react-navigation/native';`
        *   `const isFocused = useIsFocused();`
        *   Returns a boolean indicating if the screen is currently focused. Re-renders the component when focus changes. Simpler for conditional rendering or simple effects based on focus.
    *   **`useFocusEffect` Hook:** `import { useFocusEffect } from '@react-navigation/native';`
        *   Runs an effect (like `useEffect`) specifically when the screen comes into focus, and runs a cleanup function when it blurs or unmounts.
        *   Useful for fetching data when a screen becomes active or adding/removing event listeners tied to screen focus.
        *   Must wrap the effect function in `React.useCallback` to prevent re-running the effect on every render if its dependencies haven't changed.
        *   `useFocusEffect(React.useCallback(() => { const subscription = API.subscribe(); return () => subscription.unsubscribe(); }, []));`
    *   <YouTube videoId="QhSFd1EThkM" title="React Navigation Hooks - useNavigation, useRoute, useFocusEffect by Codedamn" /> (Focus on focus hooks)
    *   <YouTube videoId_ REACT_NAVIGATION_BEFOREREMOVE_EVENT_AND_PREVENTING_NAVIGATION_by_Codevolution title="React Navigation beforeRemove Event and Preventing Navigation by Codevolution" /> (Placeholder)

*   **Lesson 3.13: Authentication Flows (Conditional Rendering of Navigators)**
    *   Common app pattern: Different sets of screens for authenticated users (main app features) vs. unauthenticated users (Login, SignUp, Forgot Password).
    *   Managing an authentication token or user state (e.g., in React Context, Redux, Zustand, or simple `useState` in `App.js` for basic apps).
    *   Conditionally rendering the appropriate navigator in your root `App.js` component based on the auth state.
        ```javascript
        // function App() {
        //   const { userToken, isLoading } = useAuth(); // Assuming useAuth is a custom hook providing auth state
        //   if (isLoading) { return <SplashScreen />; } // Or some loading indicator
        //   return (
        //     <NavigationContainer>
        //       {userToken == null ? <AuthStackNavigator /> : <MainAppTabNavigator />}
        //     </NavigationContainer>
        //   );
        // }
        ```
    *   Using React Context API (or a state management library) to manage and provide auth state (`userToken`, `isLoading`) and auth functions (`signIn`, `signOut`, `signUp`) throughout the app without prop drilling.
    *   Navigating between the "Auth Stack" and the "App Stack" upon login/logout. This often involves resetting the navigation state using `navigation.reset()` to clear the previous stack history (e.g., user can't go back to login screen after logging in).
    *   Handling initial loading state (e.g., checking for a stored token from AsyncStorage when the app starts).
    *   <YouTube videoId="hAsKeAbfr2k" title="React Navigation - Authentication Flow (Login/Logout) by Academind" />
    *   <YouTube videoId_ REACT_NATIVE_AUTH_FLOW_WITH_CONTEXT_API_AND_ASYNCSTORAGE_by_NotJustDev title="React Native Auth Flow with Context API and AsyncStorage by NotJust.dev" /> (Placeholder)

*   **Lesson 3.14: Deep Linking and URL Integration**
    *   What is Deep Linking? Allowing users to open your app to a specific screen or content via a URL. This URL can come from a website link, an email, a push notification, or another app.
    *   Configuring deep linking with React Navigation:
        *   Defining a `linking` configuration object and passing it to the `NavigationContainer` prop.
        *   `prefixes`: An array of URL schemes or domains your app should respond to (e.g., `myapp://`, `https://yourapp.com`).
        *   `config`: An object that maps URL path patterns to your navigator/screen names and defines how to parse parameters from the path.
            *   Path patterns can include placeholders for params (e.g., `screens: { Profile: 'user/:userId' }`).
    *   Handling parameters from the URL (they become part of `route.params`).
    *   Testing deep links on different platforms:
        *   iOS: Universal Links (for `https://` schemes, requires server setup with AASA file) and Custom URL Schemes (e.g., `myapp://`). Requires native configuration in Xcode (Associated Domains, URL Types in Info.plist).
        *   Android: App Links (for `https://` schemes, requires server setup with assetlinks.json) and Deep Links (Custom URL Schemes). Requires native configuration (Intent Filters in `AndroidManifest.xml`).
    *   Expo specific configuration for deep linking (in `app.json` or `app.config.js` for `scheme` and associated domain setup for EAS Build).
    *   `Linking` API from React Native for manually handling incoming URLs or opening external URLs.
    *   <YouTube videoId_ REACT_NAVIGATION_DEEP_LINKING_TUTORIAL_COMPLETE_GUIDE_by_NotJustDev title="React Navigation Deep Linking Tutorial - Complete Guide by NotJust.dev" /> (Placeholder)
    *   <YouTube videoId_ EXPO_DEEP_LINKING_REACT_NATIVE_UNIVERSAL_LINKS_by_Expo_Team title="Expo Deep Linking React Native - Universal Links by Expo Team" /> (Placeholder)

*   **Lesson 3.15: Best Practices for Structuring Navigation Code & Type Checking with TypeScript**
    *   **Separation of Concerns:** Define navigators in their own files/folders (e.g., `src/navigation/MainTabNavigator.js`, `src/navigation/AuthStackNavigator.js`, `src/navigation/AppNavigator.js` as the root combining Auth and Main).
    *   **Route Names as Constants:** Define route names as constants or enums to avoid typos and for easier refactoring.
        *   `// src/navigation/ScreenNames.js`
        *   `export const ScreenNames = { AUTH_LOGIN: 'AuthLogin', APP_HOME: 'AppHome', APP_DETAILS: 'AppDetails' };`
    *   **TypeScript for Type Safety (Highly Recommended):**
        *   Define types for your navigator's screen list and their expected params.
            *   `export type RootStackParamList = { [ScreenNames.APP_HOME]: undefined; [ScreenNames.APP_DETAILS]: { itemId: string, itemName: string }; };`
        *   Use these types with React Navigation's provided generic types for hooks and props:
            *   `StackScreenProps<RootStackParamList, ScreenNames.APP_DETAILS>` for screen component props.
            *   `useNavigation<NavigationProp<RootStackParamList>>()`
            *   `useRoute<RouteProp<RootStackParamList, ScreenNames.APP_DETAILS>>()`
        *   This provides autocompletion and compile-time checks for route names and params.
    *   **Screen Organization:** Keep screen components in a dedicated `src/screens` folder, possibly sub-foldered by feature or navigator.
    *   **User Experience (UX) Considerations:**
        *   Ensure clear and consistent back navigation behavior.
        *   Design intuitive tab and drawer organization.
        *   Use modals appropriately for focused tasks or alerts, not for primary navigation flow.
    *   **Performance:** For very complex apps with many screens, consider strategies like lazy loading screens if supported by your navigation setup (less common with basic React Navigation but some patterns exist).
    *   <YouTube videoId_ REACT_NAVIGATION_TYPESCRIPT_BEST_PRACTICES_by_Codevolution title="React Navigation TypeScript Best Practices by Codevolution" /> (Placeholder)
    *   <YouTube videoId_ ORGANIZING_REACT_NATIVE_PROJECTS_NAVIGATION_SCREENS_AND_COMPONENTS_by_Spencer_Carli title="Organizing React Native Projects (Navigation, Screens, and Components) by Spencer Carli" /> (Placeholder)

This completes the expansion for Module 3 of Course 3.
---
### Module 4: State Management in React Native (Expanded)

This module explores different techniques for managing state in React Native applications, especially as they grow in complexity, with more detailed lessons.

*   **Lesson 4.1: The Challenge of State Management in Larger Applications**
    *   Recap: Component state (`useState`) is good for local UI state.
    *   Problems that arise as applications grow:
        *   **Prop Drilling:** Passing props down through many levels of components, even if intermediate components don't use them. Makes code verbose and hard to refactor.
        *   **Shared State:** Multiple components needing access to the same piece of data or needing to update it.
        *   **Complex State Logic:** State updates that involve multiple steps or depend on various conditions become hard to manage within a single component.
        *   **Global State:** Data that needs to be accessible from anywhere in the app (e.g., user authentication status, theme preferences, notifications).
    *   Why simple component state isn't always enough.
    *   Introduction to different categories of state management solutions (Component State, Context API, External Libraries like Redux, Zustand, Jotai, Recoil).
    *   <YouTube videoId_ THE_PROBLEM_WITH_PROP_DRILLING_IN_REACT_by_Web_Dev_Simplified title="The Problem with Prop Drilling in React (and how to solve it) by Web Dev Simplified" /> (Placeholder)
    *   <YouTube videoId_ WHY_DO_WE_NEED_STATE_MANAGEMENT_LIBRARIES_by_Academind title="Why Do We Need State Management Libraries? by Academind" /> (Placeholder)

*   **Lesson 4.2: Lifting State Up - A Core React Pattern**
    *   When multiple child components need to reflect the same changing data, it's often best to lift the shared state up to their closest common ancestor component.
    *   The ancestor then passes the state down to the children via props.
    *   If children need to modify the state, the ancestor passes down callback functions (event handlers) as props.
    *   **Example:** A temperature converter with Celsius and Fahrenheit inputs. The temperature state lives in the parent, and both inputs update/read from it.
    *   Pros: Keeps data flow unidirectional and understandable for simpler cases of shared state.
    *   Cons: Can lead to prop drilling if the common ancestor is very high up the tree.
    *   <YouTube videoId_ REACT_LIFTING_STATE_UP_EXPLAINED_by_The_Net_Ninja title="React Lifting State Up Explained by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId_ REACT_OFFICIAL_DOCS_LIFTING_STATE_UP_TUTORIAL_by_ReactJS_Org title="React Official Docs - Lifting State Up Tutorial (Conceptual) by ReactJS Org" /> (Placeholder)

*   **Lesson 4.3: `useReducer` Hook for Complex Local State Logic**
    *   An alternative to `useState` when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one.
    *   Inspired by Redux reducers.
    *   Syntax: `const [state, dispatch] = useReducer(reducer, initialArg, init);`
        *   `reducer`: A function `(currentState, action) => newState`. It takes the current state and an action object, and returns the new state.
        *   `initialArg`: The initial state value.
        *   `init` (optional): A function to compute the initial state lazily.
        *   `dispatch`: A function you call to send ("dispatch") an action object to the reducer.
    *   **Action Object:** Typically an object with a `type` property (string describing the action) and an optional `payload` (data for the update).
    *   **Example (Counter with increment, decrement, reset):**
        ```javascript
        const initialState = { count: 0 };
        function reducer(state, action) {
          switch (action.type) {
            case 'increment': return { count: state.count + 1 };
            case 'decrement': return { count: state.count - 1 };
            case 'reset': return { count: action.payload || 0 }; // Optional payload for reset value
            default: throw new Error('Unexpected action type');
          }
        }
        // In component:
        // const [state, dispatch] = useReducer(reducer, initialState);
        // <Button title="+" onPress={() => dispatch({ type: 'increment' })} />
        // <Button title="Reset to 5" onPress={() => dispatch({ type: 'reset', payload: 5 })} />
        ```
    *   Benefits: Centralizes state update logic, makes complex state transitions more predictable and testable.
    *   <YouTube videoId="kK_Wqx3RnHk" title="React Hooks Tutorial - 15 - useReducer Hook by Codevolution" /> (Recap)
    *   <YouTube videoId_ USEREDUCER_VS_USESTATE_IN_REACT_by_Web_Dev_Simplified title="useReducer vs useState in React by Web Dev Simplified" /> (Placeholder)

*   **Lesson 4.4: Introduction to React Context API**
    *   What is Context? A way to pass data through the component tree without having to pass props down manually at every level (avoids prop drilling).
    *   Designed to share data that can be considered "global" for a tree of React components, such as the current authenticated user, theme, or preferred language.
    *   Core API:
        *   `React.createContext(defaultValue)`: Creates a Context object. The `defaultValue` is used only when a component does not have a matching Provider above it in the tree.
        *   `Context.Provider`: A component that allows consuming components to subscribe to context changes. Accepts a `value` prop to be passed to consuming components.
            *   `<MyContext.Provider value={/* some value */}>`
        *   `Context.Consumer`: A component that subscribes to context changes. Requires a function as a child that receives the context value and returns a React node. (Less common with hooks).
        *   `useContext(MyContext)` Hook (Preferred): Accepts a context object (the value returned from `React.createContext`) and returns the current context value for that context. Re-renders when the Provider's `value` prop changes.
    *   <YouTube videoId="5bL2VdOpCMs" title="React Context API Tutorial by Traversy Media" /> (Recap)

*   **Lesson 4.5: Using Context API - Creating a Provider and Consumer/`useContext`**
    *   Step-by-step example of creating a simple theme context.
    *   **1. Create the Context:**
        ```javascript
        // ThemeContext.js
        import React, { createContext, useState, useContext } from 'react';
        export const ThemeContext = createContext(); // Can provide a default value here
        ```
    *   **2. Create the Provider Component:**
        ```javascript
        // ThemeContext.js (continued)
        export const ThemeProvider = ({ children }) => {
          const [theme, setTheme] = useState('light'); // 'light' or 'dark'
          const toggleTheme = () => setTheme(prevTheme => (prevTheme === 'light' ? 'dark' : 'light'));

          return (
            <ThemeContext.Provider value={{ theme, toggleTheme }}>
              {children}
            </ThemeContext.Provider>
          );
        };
        ```
    *   **3. Wrap the Application (or part of it) with the Provider:**
        ```javascript
        // App.js
        import { ThemeProvider } from './ThemeContext';
        // ...
        // return <ThemeProvider><AppNavigator /></ThemeProvider>;
        ```
    *   **4. Consume the Context using `useContext` Hook:**
        ```javascript
        // MyScreen.js
        import { useContext } from 'react';
        import { ThemeContext } from './ThemeContext';
        // ...
        // const { theme, toggleTheme } = useContext(ThemeContext);
        // return <View style={{backgroundColor: theme === 'light' ? '#fff' : '#333'}}>...</View>;
        ```
    *   <YouTube videoId_ REACT_CONTEXT_API_STEP_BY_STEP_TUTORIAL_by_The_Net_Ninja title="React Context API Step-by-Step Tutorial by The Net Ninja" /> (Placeholder)

*   **Lesson 4.6: Context API - Performance Considerations and Best Practices**
    *   Context re-renders all consuming components whenever the `value` prop of the Provider changes.
    *   If the `value` is an object or array created inline in the Provider's render method (e.g., `value={{ theme, toggleTheme }}`), it will be a new object on every render of the Provider, causing unnecessary re-renders of consumers even if the actual data hasn't changed.
    *   **Optimization:**
        *   Memoize the `value` prop using `React.useMemo` if it's an object/array, or split context into multiple smaller contexts if different parts of the value change at different rates.
        *   **Example with `useMemo`:**
            ```javascript
            // ThemeProvider
            // const value = React.useMemo(() => ({ theme, toggleTheme }), [theme, toggleTheme]);
            // return <ThemeContext.Provider value={value}>{children}</ThemeContext.Provider>;
            ```
    *   Context is not ideal for very high-frequency updates (like animation states).
    *   Keep context specific; avoid creating one massive global context for everything.
    *   Use Context for low-frequency updates of global-like data.
    *   <YouTube videoId_ REACT_CONTEXT_PERFORMANCE_OPTIMIZATION_by_Jack_Herrington title="React Context Performance Optimization by Jack Herrington" /> (Placeholder)
    *   <YouTube videoId_ AVOIDING_UNNECESSARY_RERENDERS_WITH_REACT_CONTEXT_by_Ben_Awad title="Avoiding Unnecessary Re-renders with React Context by Ben Awad" /> (Placeholder)

*   **Lesson 4.7: Introduction to Redux - Core Concepts (Store, Actions, Reducers)**
    *   What is Redux? A predictable state container for JavaScript applications (not just React/React Native).
    *   Why use Redux? For managing complex application state that needs to be shared across many components, or when state logic becomes too involved for Context API or `useReducer` alone. Provides robust debugging tools (Redux DevTools).
    *   Core Redux Principles (The Three Principles):
        1.  **Single Source of Truth:** The state of your whole application is stored in an object tree within a single **store**.
        2.  **State is Read-Only:** The only way to change the state is to emit an **action**, an object describing what happened.
        3.  **Changes are made with Pure Functions:** To specify how the state tree is transformed by actions, you write pure **reducers**.
    *   **Store:** The object that holds the application state. Has methods like `getState()`, `dispatch(action)`, `subscribe(listener)`.
    *   **Actions:** Plain JavaScript objects that describe an event or intention to change state. Must have a `type` property (string). Can have an optional `payload` (data).
        *   **Example:** `{ type: 'ADD_TODO', payload: { text: 'Learn Redux' } }`
    *   **Action Creators:** Functions that create and return action objects.
    *   **Reducers:** Pure functions `(previousState, action) => newState`. They take the current state and an action, and return the next state. Must not mutate the original state; create a new state object instead.
    *   <YouTube videoId="9boMnm5X9ak" title="Redux Crash Course With React by Traversy Media" /> (Focus on Redux core concepts part)

*   **Lesson 4.8: Setting up Redux with React Native (`redux`, `react-redux`)**
    *   Installation: `npm install redux react-redux` or `yarn add ...`.
    *   **1. Define Action Types (Constants):**
        *   `// actions/types.js`
        *   `export const INCREMENT_COUNTER = 'INCREMENT_COUNTER';`
    *   **2. Create Action Creators:**
        *   `// actions/counterActions.js`
        *   `import { INCREMENT_COUNTER } from './types';`
        *   `export const increment = () => ({ type: INCREMENT_COUNTER });`
    *   **3. Create Reducers:**
        *   `// reducers/counterReducer.js`
        *   `import { INCREMENT_COUNTER } from '../actions/types';`
        *   `const initialState = { count: 0 };`
        *   `export default function(state = initialState, action) { switch(action.type) { case INCREMENT_COUNTER: return { ...state, count: state.count + 1 }; default: return state; } }`
    *   **4. Combine Reducers (if multiple):**
        *   `// reducers/index.js`
        *   `import { combineReducers } from 'redux'; import counterReducer from './counterReducer';`
        *   `export default combineReducers({ counter: counterReducer });`
    *   **5. Create the Store:**
        *   `// store.js`
        *   `import { createStore } from 'redux'; import rootReducer from './reducers';`
        *   `const store = createStore(rootReducer); export default store;`
    *   **6. Provide the Store to the App (using `Provider` from `react-redux`):**
        *   `// App.js`
        *   `import { Provider } from 'react-redux'; import store from './store';`
        *   `// return <Provider store={store}><AppNavigator /></Provider>;`
    *   <YouTube videoId_ REACT_NATIVE_REDUX_SETUP_FROM_SCRATCH_by_Codevolution title="React Native Redux Setup From Scratch by Codevolution" /> (Placeholder)

*   **Lesson 4.9: Connecting React Native Components to Redux Store (`useSelector`, `useDispatch`)**
    *   `react-redux` library provides hooks to interact with the Redux store from React components.
    *   **`useSelector` Hook:** Allows you to extract data (select parts of the state) from the Redux store state.
        *   Takes a selector function as an argument: `(state) => state.someValue`.
        *   Subscribes to the store, and re-renders the component if the selected state changes.
        *   **Example:** `const count = useSelector(state => state.counter.count);`
    *   **`useDispatch` Hook:** Returns a reference to the `dispatch` function from the Redux store.
        *   Used to dispatch actions.
        *   **Example:**
            ```javascript
            // import { useDispatch } from 'react-redux';
            // import { increment } from './actions/counterActions';
            // const dispatch = useDispatch();
            // <Button title="Increment" onPress={() => dispatch(increment())} />
            ```
    *   Replacing `connect` Higher-Order Component (older way) with hooks.
    *   <YouTube videoId_ REACT_REDUX_HOOKS_USESELECTOR_USEDISPATCH_by_The_Net_Ninja title="React Redux Hooks - useSelector & useDispatch by The Net Ninja" /> (Placeholder)

*   **Lesson 4.10: Asynchronous Actions in Redux with Thunks (`redux-thunk`)**
    *   Redux reducers must be pure and synchronous. API calls and other async operations cannot happen directly in reducers.
    *   Middleware like `redux-thunk` allows action creators to return a function (a "thunk") instead of a plain action object.
    *   This thunk function receives `dispatch` and `getState` as arguments, allowing it to perform async operations and dispatch actions (e.g., `REQUEST`, `SUCCESS`, `FAILURE` actions for an API call).
    *   Installation: `npm install redux-thunk`.
    *   Applying middleware when creating the store:
        *   `// store.js`
        *   `import { createStore, applyMiddleware } from 'redux'; import thunk from 'redux-thunk';`
        *   `const store = createStore(rootReducer, applyMiddleware(thunk));`
    *   **Example (Thunk Action Creator for fetching data):**
        ```javascript
        // actions/dataActions.js
        // export const fetchData = () => async dispatch => {
        //   dispatch({ type: 'FETCH_DATA_REQUEST' });
        //   try {
        //     const response = await fetch('https://api.example.com/data');
        //     const data = await response.json();
        //     dispatch({ type: 'FETCH_DATA_SUCCESS', payload: data });
        //   } catch (error) {
        //     dispatch({ type: 'FETCH_DATA_FAILURE', payload: error.message });
        //   }
        // };
        ```
    *   <YouTube videoId="1QI-UE3-0c4" title="Redux Thunk Tutorial by Traversy Media" />

*   **Lesson 4.11: Introduction to Redux Toolkit (Modern, Opinionated Redux)**
    *   Why Redux Toolkit? The official, recommended way to write Redux logic.
        *   Simplifies Redux development, significantly reduces boilerplate code.
        *   Includes best practices by default (Immer for immutable updates, Thunk for async, DevTools integration).
    *   Key APIs:
        *   `configureStore()`: Replaces `createStore`. Automatically sets up Thunk middleware and Redux DevTools Extension.
        *   `createSlice()`: Generates action creators and action types automatically from a "slice" of state and its reducers. Uses Immer internally to simplify immutable updates.
        *   `createAsyncThunk()`: For handling common asynchronous action patterns (like API requests) with pending/fulfilled/rejected action types generated automatically.
    *   Installation: `npm install @reduxjs/toolkit react-redux` (Redux Toolkit includes Redux core).
    *   <YouTube videoId="0XgB7SgC-V4" title="Redux Toolkit Crash Course 2023 by Laith Harb" />
    *   <YouTube videoId="NqzdVN2tyvQ" title="Redux Toolkit Tutorial by Codevolution" />

*   **Lesson 4.12: Using `createSlice` from Redux Toolkit**
    *   A slice represents a portion of your Redux state and the logic to update it.
    *   `createSlice({ name, initialState, reducers })`:
        *   `name`: A string name for the slice (used to generate action type prefixes).
        *   `initialState`: The initial state value for this slice.
        *   `reducers`: An object where keys are action names and values are reducer functions.
            *   These "mini-reducers" can mutate state directly thanks to Immer (e.g., `state.count++`).
            *   Automatically generates action creators with the same names (e.g., `mySlice.actions.increment()`).
    *   **Example (Counter Slice):**
        ```javascript
        // features/counter/counterSlice.js
        // import { createSlice } from '@reduxjs/toolkit';
        // const initialState = { value: 0 };
        // const counterSlice = createSlice({
        //   name: 'counter',
        //   initialState,
        //   reducers: {
        //     increment: (state) => { state.value += 1; },
        //     decrement: (state) => { state.value -= 1; },
        //     incrementByAmount: (state, action) => { state.value += action.payload; },
        //   },
        // });
        // export const { increment, decrement, incrementByAmount } = counterSlice.actions;
        // export default counterSlice.reducer;
        ```
    *   Configuring the store with slice reducers:
        ```javascript
        // app/store.js
        // import { configureStore } from '@reduxjs/toolkit';
        // import counterReducer from '../features/counter/counterSlice';
        // export const store = configureStore({ reducer: { counter: counterReducer } });
        ```
    *   <YouTube videoId_ REDUX_TOOLKIT_CREATESLICE_EXPLAINED_by_The_Net_Ninja title="Redux Toolkit createSlice Explained by The Net Ninja" /> (Placeholder)

*   **Lesson 4.13: Using `createAsyncThunk` from Redux Toolkit**
    *   Simplifies asynchronous logic like API calls.
    *   `createAsyncThunk(actionTypePrefix, payloadCreator)`:
        *   `actionTypePrefix`: String used to generate pending, fulfilled, and rejected action types (e.g., `'users/fetchUsers'`).
        *   `payloadCreator`: An async function that performs the async logic and returns a promise. The resolved value becomes the `action.payload` of the fulfilled action. If it throws an error, the rejected action is dispatched.
    *   Automatically dispatches lifecycle actions: `pending`, `fulfilled`, `rejected`.
    *   Handle these actions in a slice's `extraReducers` field using the builder API.
    *   **Example (Fetching Users):**
        ```javascript
        // features/users/usersSlice.js
        // import { createSlice, createAsyncThunk } from '@reduxjs/toolkit';
        // export const fetchUsers = createAsyncThunk('users/fetchUsers', async () => {
        //   const response = await fetch('https://jsonplaceholder.typicode.com/users');
        //   return response.json();
        // });
        // const usersSlice = createSlice({
        //   name: 'users', initialState: { entities: [], loading: 'idle' }, reducers: {},
        //   extraReducers: (builder) => {
        //     builder.addCase(fetchUsers.pending, (state) => { state.loading = 'loading'; })
        //            .addCase(fetchUsers.fulfilled, (state, action) => { state.loading = 'succeeded'; state.entities = action.payload; })
        //            .addCase(fetchUsers.rejected, (state, action) => { state.loading = 'failed'; /* state.error = action.error.message */ });
        //   }
        // });
        // export default usersSlice.reducer;
        ```
    *   Dispatching the thunk: `dispatch(fetchUsers());`
    *   <YouTube videoId_ REDUX_TOOLKIT_CREATEASYNCTHUNK_TUTORIAL_by_Codevolution title="Redux Toolkit createAsyncThunk Tutorial by Codevolution" /> (Placeholder)

*   **Lesson 4.14: Other State Management Libraries (Brief Overview: Zustand, Jotai, Recoil)**
    *   While Redux (especially Toolkit) and Context API are very common, other libraries offer different approaches.
    *   **Zustand:** Simpler, smaller, less boilerplate than traditional Redux. Uses hooks, feels more like `useState` for global state. State is updated by mutating it (uses Immer internally).
    *   **Jotai:** Atom-based state management. Atoms are small, independent, composable pieces of state. Minimalist API.
    *   **Recoil (by Meta/Facebook):** Also atom-based. Provides more advanced features like selectors for derived state and asynchronous data fetching capabilities.
    *   Briefly discuss their core ideas, pros/cons, and when they might be considered as alternatives.
    *   The choice often depends on project size, team preference, and specific needs (e.g., Jotai/Recoil for granular state, Zustand for simplicity).
    *   <YouTube videoId_ ZUSTAND_VS_REDUX_VS_CONTEXT_by_Jack_Herrington title="Zustand vs Redux vs Context by Jack Herrington" /> (Placeholder)
    *   <YouTube videoId_ JOTAI_ATOM_BASED_STATE_MANAGEMENT_by_Fireship title="Jotai - Atom Based State Management by Fireship" /> (Placeholder)
    *   <YouTube videoId_ RECOIL_REACT_STATE_MANAGEMENT_by_Traversy_Media title="Recoil - React State Management by Traversy Media" /> (Placeholder)

*   **Lesson 4.15: Choosing the Right State Management Strategy for Your React Native App**
    *   No single "best" solution fits all scenarios.
    *   Factors to consider:
        *   **Application Size & Complexity:** Simple apps might only need component state (`useState`, `useReducer`). Larger, complex apps with deeply nested components or significant shared state might benefit from Context API, Redux Toolkit, or Zustand/Jotai/Recoil.
        *   **Type of State:**
            *   Local UI state (e.g., form input, modal visibility) -> `useState`.
            *   Complex local state -> `useReducer`.
            *   Global application state (theme, user auth, language) -> Context API (for low-frequency updates) or a dedicated global state library.
            *   Server cache state (data fetched from APIs) -> Specialized libraries like React Query (TanStack Query) or SWR are often better than putting API responses directly into global Redux state.
        *   **Team Familiarity & Learning Curve:** Choose tools your team is comfortable with or willing to learn.
        *   **Performance Needs:** High-frequency updates might require more optimized solutions or careful use of Context/Redux to avoid unnecessary re-renders.
        *   **Boilerplate and Developer Experience:** Redux Toolkit significantly reduces Redux boilerplate. Zustand/Jotai aim for even less.
    *   General guidelines:
        *   Start simple with React's built-in state management.
        *   Introduce Context API for theming, auth, or simple global data.
        *   Consider Redux Toolkit (or Zustand/Jotai) for more complex global state, many interconnected components, or when advanced debugging/middleware capabilities (like Redux DevTools, Thunks/Sagas) are crucial.
    *   It's common to use a combination of these strategies in one app (e.g., `useState` for local, Context for theme, Redux/Zustand for complex app-wide data).
    *   <YouTube videoId_ HOW_TO_CHOOSE_A_REACT_STATE_MANAGEMENT_LIBRARY_by_Ben_Awad title="How to Choose a React State Management Library by Ben Awad" /> (Placeholder)
    *   <YouTube videoId_ STATE_MANAGEMENT_IN_REACT_NATIVE_OVERVIEW_AND_CHOICES_2023_by_Academind title="State Management in React Native - Overview and Choices 2023 by Academind" /> (Placeholder)

This completes the expansion for Module 4 of Course 3.
---
### Module 5: Working with APIs, Local Storage, and Native Features (Expanded)

This module covers fetching data from remote servers, storing data locally on the device, and interacting with some native device features, with expanded detail.

*   **Lesson 5.1: Introduction to APIs (Application Programming Interfaces)**
    *   What is an API? A set of rules and protocols that allows different software applications to communicate and exchange data with each other.
    *   Analogy: A waiter in a restaurant (you tell the waiter your order, waiter tells the kitchen, waiter brings food back).
    *   Types of Web APIs:
        *   REST APIs (Representational State Transfer): Most common for web/mobile. Uses HTTP methods (GET, POST, PUT, DELETE), stateless, often returns JSON.
        *   GraphQL APIs: Query language for your API, allows clients to request only the data they need.
        *   SOAP APIs (older, XML-based).
    *   Why mobile apps use APIs: To fetch data from servers, send user data, authenticate users, integrate with third-party services.
    *   Understanding API Endpoints (URLs), HTTP Methods, Headers, Request Body, Response Body, Status Codes (200 OK, 404 Not Found, 500 Server Error, etc.).
    *   <YouTube videoId="s7wmiS2mSUE" title="What is an API? In English, please. by freeCodeCamp.org" />
    *   <YouTube videoId_ REST_API_CONCEPTS_AND_EXAMPLES_by_Traversy_Media title="REST API Concepts and Examples by Traversy Media" /> (Placeholder)

*   **Lesson 5.2: Making Network Requests with the `fetch` API**
    *   The `fetch` API is a modern JavaScript interface for making HTTP requests (available in React Native globally).
    *   It's Promise-based.
    *   **Making a GET request:**
        ```javascript
        fetch('https://jsonplaceholder.typicode.com/todos/1')
          .then(response => {
            if (!response.ok) { // Check for HTTP error status (4xx, 5xx)
              throw new Error('Network response was not ok: ' + response.statusText);
            }
            return response.json(); // Parses the response body as JSON
          })
          .then(data => console.log(data))
          .catch(error => console.error('Fetch error:', error));
        ```
    *   **Making a POST request (and other methods):**
        *   The second argument to `fetch` is an options object.
        *   `method: 'POST'`, `headers: { 'Content-Type': 'application/json' }`, `body: JSON.stringify(dataObject)`.
    *   Handling different response types (JSON, text).
    *   Error handling: `fetch` only rejects a promise for network errors, not for HTTP error statuses (like 404 or 500). You must check `response.ok` or `response.status`.
    *   Using `async/await` with `fetch` for cleaner syntax.
    *   <YouTube videoId="cuEtnrL9-H0" title="JavaScript Fetch API by Traversy Media" />
    *   <YouTube videoId_ FETCH_API_IN_REACT_NATIVE_by_Codevolution title="Fetch API in React Native by Codevolution" /> (Placeholder)

*   **Lesson 5.3: Using `Axios` for Network Requests**
    *   Axios is a popular, promise-based HTTP client for the browser and Node.js (works well in React Native).
    *   Installation: `npm install axios` or `yarn add axios`.
    *   Benefits over `fetch`:
        *   Automatic JSON data transformation (no need for `response.json()` manually).
        *   Better error handling (rejects promise on HTTP error statuses 4xx, 5xx).
        *   Request and response interceptors (for global error handling, adding auth tokens, etc.).
        *   Easier to set default headers, timeout configuration.
    *   **Making a GET request with Axios:**
        ```javascript
        // import axios from 'axios';
        // axios.get('https://jsonplaceholder.typicode.com/todos/1')
        //   .then(response => console.log(response.data)) // response.data contains the JSON
        //   .catch(error => console.error('Axios error:', error));
        ```
    *   **Making a POST request with Axios:**
        *   `axios.post('https://api.example.com/users', dataObject, { headers: { ... } });`
    *   Creating an Axios instance with base URL and default configurations.
    *   <YouTube videoId="6M5k3DCYl" title="Axios Crash Course | HTTP Client by Traversy Media" />
    *   <YouTube videoId_ AXIOS_VS_FETCH_IN_REACT_NATIVE_by_The_Net_Ninja title="Axios vs Fetch in React Native by The Net Ninja" /> (Placeholder)

*   **Lesson 5.4: Handling API Data in Components - Loading States, Error States**
    *   When fetching data, you typically need to manage different UI states:
        *   `loading`: While the request is in progress.
        *   `data`: When the data is successfully fetched.
        *   `error`: If the request fails.
    *   Using `useState` to manage these states:
        ```javascript
        // const [data, setData] = useState(null);
        // const [loading, setLoading] = useState(true);
        // const [error, setError] = useState(null);
        ```
    *   Using `useEffect` to fetch data when the component mounts:
        ```javascript
        // useEffect(() => {
        //   const fetchData = async () => {
        //     try {
        //       setLoading(true);
        //       const response = await fetch('...');
        //       const result = await response.json();
        //       setData(result);
        //       setError(null);
        //     } catch (e) {
        //       setError(e.message);
        //       setData(null);
        //     } finally {
        //       setLoading(false);
        //     }
        //   };
        //   fetchData();
        // }, []); // Empty dependency array: run once on mount
        ```
    *   Conditionally rendering UI based on these states:
        *   Show an `<ActivityIndicator />` when `loading` is true.
        *   Show an error message when `error` is not null.
        *   Display the data (e.g., in a `FlatList`) when `data` is available.
    *   <YouTube videoId_ HANDLING_API_LOADING_ERROR_STATES_IN_REACT_NATIVE_by_Academind title="Handling API Loading & Error States in React Native by Academind" /> (Placeholder)

*   **Lesson 5.5: Displaying Fetched Data in Lists (`FlatList` with API Data)**
    *   Integrating API calls with `FlatList`.
    *   Fetching an array of data and setting it to a state variable used by `FlatList`'s `data` prop.
    *   Handling loading and error states specifically for the list.
    *   Implementing "Pull to Refresh" functionality with `FlatList` to re-fetch data.
    *   Implementing "Infinite Scroll" or "Load More" functionality to fetch paginated data as the user scrolls.
        *   Managing page numbers or cursors in state.
        *   Appending new data to the existing data array.
    *   <YouTube videoId_ REACT_NATIVE_FLATLIST_WITH_API_DATA_PAGINATION_by_NotJustDev title="React Native FlatList with API Data & Pagination by NotJust.dev" /> (Placeholder)

*   **Lesson 5.6: Asynchronous JavaScript Review - Promises In-Depth**
    *   Recap: Promises represent the eventual result (or failure) of an asynchronous operation.
    *   States of a Promise: `pending`, `fulfilled` (resolved), `rejected`.
    *   `.then(onFulfilled, onRejected)`: Attaches callbacks for fulfillment and rejection. `onRejected` is optional; often prefer `.catch()`.
    *   `.catch(onRejected)`: Handles errors/rejections from the promise or any preceding `.then()` callbacks.
    *   `.finally(onFinally)`: Executes a callback when the promise is settled (either fulfilled or rejected).
    *   Chaining Promises: Returning a new promise from a `.then()` callback allows further chaining.
    *   `Promise.all(iterable)`: Takes an iterable of promises and returns a single promise that fulfills when all input promises have fulfilled (with an array of their values), or rejects if any input promise rejects.
    *   `Promise.race(iterable)`: Returns a promise that fulfills or rejects as soon as one of the promises in the iterable fulfills or rejects.
    *   Creating your own Promises with the `new Promise((resolve, reject) => { ... })` constructor.
    *   <YouTube videoId="DHvZLI7Db8E" title="Async JS Crash Course - Callbacks, Promises, Async Await by Traversy Media" /> (Focus on Promises)

*   **Lesson 5.7: Asynchronous JavaScript Review - `async/await` Syntax**
    *   `async` keyword: Placed before a function declaration to make it an `async function`.
        *   Async functions always implicitly return a Promise. If the function returns a value, the Promise will resolve with that value. If it throws an error, the Promise will reject.
    *   `await` keyword: Can only be used inside an `async function`.
        *   Pauses the execution of the `async function` and waits for the Promise (that `await` is called on) to resolve or reject.
        *   If the Promise resolves, `await` returns the resolved value.
        *   If the Promise rejects, `await` throws the rejected error (which can be caught by `try...catch`).
    *   Makes asynchronous code look and behave a bit more like synchronous code, improving readability.
    *   **Example (Refactoring fetch with async/await):**
        ```javascript
        // async function fetchData() {
        //   try {
        //     const response = await fetch('https://api.example.com/data');
        //     if (!response.ok) throw new Error('Network error');
        //     const data = await response.json();
        //     console.log(data);
        //   } catch (error) {
        //     console.error('Error:', error);
        //   }
        // }
        ```
    *   Error handling with `try...catch` blocks around `await` expressions.
    *   <YouTube videoId="DHvZLI7Db8E" title="Async JS Crash Course - Callbacks, Promises, Async Await by Traversy Media" /> (Focus on async/await)

*   **Lesson 5.8: Introduction to Local Storage - Why and When?**
    *   What is Local Storage in a mobile context? Storing small amounts of data persistently on the user's device.
    *   Why use local storage?
        *   Caching frequently accessed data to reduce API calls and improve performance.
        *   Storing user preferences or settings.
        *   Storing authentication tokens.
        *   Saving application state for offline use (basic offline support).
    *   Limitations:
        *   Not for large amounts of data (use SQLite or other databases for that).
        *   Generally unencrypted by default (don't store highly sensitive plain text).
        *   Can be cleared by the user or OS under certain conditions.
    *   Different from component state or global state management libraries (which are in-memory).
    *   <YouTube videoId_ REACT_NATIVE_LOCAL_STORAGE_OPTIONS_OVERVIEW_by_Academind title="React Native Local Storage Options Overview by Academind" /> (Placeholder)

*   **Lesson 5.9: Using `AsyncStorage` for Key-Value Persistence**
    *   `AsyncStorage` is a simple, unencrypted, asynchronous, persistent key-value storage system for React Native.
    *   It's now a community package: `@react-native-async-storage/async-storage`.
    *   Installation: `npm install @react-native-async-storage/async-storage` or `yarn add ...` (and `pod install` for iOS if bare).
    *   Core methods (all return Promises):
        *   `AsyncStorage.setItem('key', 'value')`: Stores a string value. Non-string values must be `JSON.stringify()`'d.
        *   `AsyncStorage.getItem('key')`: Retrieves a string value. Must `JSON.parse()` if original was an object/array. Returns `null` if key doesn't exist.
        *   `AsyncStorage.removeItem('key')`: Deletes an item.
        *   `AsyncStorage.mergeItem('key', 'value')`: Merges an existing string value with a new one (if value is JSON string).
        *   `AsyncStorage.clear()`: Clears all AsyncStorage data for the app.
        *   `AsyncStorage.getAllKeys()`: Gets all keys.
        *   `AsyncStorage.multiGet(['key1', 'key2'])`, `AsyncStorage.multiSet([['k1','v1'],['k2','v2']])`, `AsyncStorage.multiRemove(['k1', 'k2'])`.
    *   **Example:**
        ```javascript
        // import AsyncStorage from '@react-native-async-storage/async-storage';
        // const storeData = async (value) => { try { await AsyncStorage.setItem('@myApp:key', value) } catch (e) { /* saving error */ } }
        // const getData = async () => { try { const value = await AsyncStorage.getItem('@myApp:key'); if(value !== null) { return value; } } catch(e) { /* error reading value */ } }
        ```
    *   Best practice: Wrap AsyncStorage calls in `try...catch` blocks.
    *   <YouTube videoId="tN3Adna4u38" title="React Native AsyncStorage Tutorial by Codedamn" />
    *   <YouTube videoId_ REACT_NATIVE_PERSISTING_USER_SETTINGS_WITH_ASYNCSTORAGE_by_The_Net_Ninja title="React Native - Persisting User Settings with AsyncStorage by The Net Ninja" /> (Placeholder)

*   **Lesson 5.10: Alternatives to AsyncStorage for Complex Data (SQLite, Realm - Overview)**
    *   When `AsyncStorage` isn't enough (complex querying, relationships, larger datasets).
    *   **SQLite:** A full-fledged relational database that can be embedded in mobile apps.
        *   Libraries like `react-native-sqlite-storage` or Expo's `expo-sqlite`.
        *   Allows SQL queries for data manipulation and retrieval.
        *   Good for structured data, offline-first apps.
    *   **Realm:** A mobile-first, object-oriented database.
        *   Faster than SQLite for many operations, simpler API (no SQL needed).
        *   Supports data synchronization with Realm Sync (cloud service).
        *   Libraries like `realm`.
    *   Brief discussion of pros/cons and when to choose them. This is an awareness lesson.
    *   <YouTube videoId_ REACT_NATIVE_SQLITE_VS_REALM_VS_ASYNCSTORAGE_by_Academind title="React Native SQLite vs Realm vs AsyncStorage by Academind" /> (Placeholder)
    *   <YouTube videoId_ GETTING_STARTED_WITH_EXPO_SQLITE_by_Expo_Team title="Getting Started with Expo SQLite by Expo Team" /> (Placeholder)

*   **Lesson 5.11: Accessing Device Permissions (Expo Permissions / `react-native-permissions`)**
    *   Mobile apps often need user permission to access sensitive features like camera, location, contacts, microphone, etc.
    *   Permissions must be requested at runtime (Android M+ and iOS).
    *   **Expo Approach (using specific modules like `expo-camera`, `expo-location` which handle their own permissions):**
        *   Modules often provide `requestPermissionsAsync()` and `getPermissionsAsync()` methods.
        *   Check permission status before trying to use a feature.
        *   **Example (Expo Location):**
            ```javascript
            // import * as Location from 'expo-location';
            // const [status, requestPermission] = Location.useForegroundPermissions();
            // if (!status || status.status !== Location.PermissionStatus.GRANTED) { /* requestPermission(); or show message */ }
            ```
    *   **Bare RN Approach (`react-native-permissions` library):**
        *   A comprehensive library for managing permissions.
        *   `check(permission)`, `request(permission)`, `openSettings()`.
    *   Best practices: Ask only when needed, explain why permission is required, handle denial gracefully.
    *   <YouTube videoId="d1kM6moiD3I" title="Handle Permissions in React Native (Expo & Bare Workflow) by Code with Nader" />
    *   <YouTube videoId_ EXPO_PERMISSIONS_API_EXPLAINED_by_Codevolution title="Expo Permissions API Explained by Codevolution" /> (Placeholder - note Expo's API has evolved)

*   **Lesson 5.12: Using the Camera (`expo-camera`)**
    *   Accessing the device camera for taking photos and videos.
    *   Installation: `expo install expo-camera`.
    *   Requesting camera and microphone (for video) permissions.
    *   The `<Camera>` component from `expo-camera`.
        *   Props: `type` (`front` or `back`), `flashMode`, `ratio`, `onCameraReady`.
        *   Methods (accessed via a ref): `takePictureAsync()`, `recordAsync()`, `stopRecording()`.
    *   Displaying camera preview.
    *   Handling captured photos/videos (saving to device, displaying in app).
    *   **Example Structure:**
        ```javascript
        // import { Camera } from 'expo-camera';
        // const [hasPermission, setHasPermission] = useState(null);
        // const cameraRef = useRef(null);
        // useEffect(() => { (async () => { const { status } = await Camera.requestCameraPermissionsAsync(); setHasPermission(status === 'granted'); })(); }, []);
        // if (hasPermission === null) return <View />; if (hasPermission === false) return <Text>No camera access</Text>;
        // const takePic = async () => { if (cameraRef.current) { let photo = await cameraRef.current.takePictureAsync(); console.log(photo.uri); } }
        // return <Camera ref={cameraRef} type={Camera.Constants.Type.back}><Button title="Snap" onPress={takePic} /></Camera>;
        ```
    *   <YouTube videoId="IZGggIpc72U" title="React Native Camera & Image Picker Tutorial (Expo) by NotJust.dev" /> (Focus on Camera part)

*   **Lesson 5.13: Accessing the Photo Library (`expo-image-picker`)**
    *   Allowing users to select images or videos from their device's media library.
    *   Installation: `expo install expo-image-picker`.
    *   Requesting media library permissions.
    *   Key methods from `expo-image-picker`:
        *   `launchImageLibraryAsync(options)`: Opens the image library.
        *   `launchCameraAsync(options)`: (Also available here, but `expo-camera` offers more control).
        *   Options: `mediaTypes` (`Images`, `Videos`, `All`), `allowsEditing`, `aspect`, `quality`.
    *   Handling the response: The promise resolves with an object containing `uri`, `width`, `height`, `type`, `cancelled`.
    *   Displaying selected images/videos in the app.
    *   **Example:**
        ```javascript
        // import * as ImagePicker from 'expo-image-picker';
        // const [imageUri, setImageUri] = useState(null);
        // const pickImage = async () => {
        //   let result = await ImagePicker.launchImageLibraryAsync({ mediaTypes: ImagePicker.MediaTypeOptions.Images, allowsEditing: true, aspect: [4,3], quality: 1 });
        //   if (!result.cancelled) { setImageUri(result.uri); }
        // };
        // return <View><Button title="Pick Image" onPress={pickImage} />{imageUri && <Image source={{ uri: imageUri }} style={{ width: 200, height: 200 }} />}</View>;
        ```
    *   <YouTube videoId="IZGggIpc72U" title="React Native Camera & Image Picker Tutorial (Expo) by NotJust.dev" /> (Focus on Image Picker part)

*   **Lesson 5.14: Geolocation (`expo-location`) and Displaying Maps (`react-native-maps`)**
    *   **`expo-location`:** Accessing device's GPS location.
        *   Installation: `expo install expo-location`.
        *   Requesting location permissions (`requestForegroundPermissionsAsync`, `requestBackgroundPermissionsAsync`).
        *   `getCurrentPositionAsync(options)`: Get current location once. Options for accuracy.
        *   `watchPositionAsync(options, callback)`: Get continuous location updates.
    *   **`react-native-maps` (Community library, works with Expo):**
        *   Installation: `expo install react-native-maps` (Expo handles linking). For Bare RN: `npm install react-native-maps` then native setup.
        *   The `<MapView>` component.
        *   Props: `initialRegion` or `region` (latitude, longitude, latitudeDelta, longitudeDelta), `showsUserLocation`, `followsUserLocation`.
        *   Adding Markers: `<MapView.Marker coordinate={{latitude, longitude}} title="Title" description="Desc" />`.
        *   Drawing Polygons, Polylines.
        *   Handling map events (onRegionChange, onPress).
    *   <YouTube videoId="q7hH4jVgxpI" title="Expo Location Tutorial - Get User's Location by Codedamn" />
    *   <YouTube videoId="qK459405HSk" title="React Native Maps Tutorial (Expo & Bare) by NotJust.dev" />

*   **Lesson 5.15: Using the Device File System (`expo-file-system`)**
    *   `expo-file-system`: Provides access to a portion of the device's file system local to your app.
    *   Installation: `expo install expo-file-system`.
    *   Key directories:
        *   `FileSystem.documentDirectory`: For user-generated content that should persist.
        *   `FileSystem.cacheDirectory`: For temporary cache files that can be cleared by the OS.
    *   Common methods:
        *   `getInfoAsync(fileUri)`: Get info about a file/directory.
        *   `readAsStringAsync(fileUri, options)`: Read file content as string.
        *   `writeAsStringAsync(fileUri, contents, options)`: Write string to a file.
        *   `deleteAsync(fileUri, options)`: Delete a file/directory.
        *   `makeDirectoryAsync(fileUri, options)`: Create a directory.
        *   `downloadAsync(uri, fileUri, options)`: Download a file from a remote URI to local file system. Returns download progress.
    *   Use cases: Saving downloaded files, caching images, storing user-generated documents.
    *   <YouTube videoId_ EXPO_FILE_SYSTEM_TUTORIAL_READ_WRITE_DOWNLOAD_FILES_by_Codevolution title="Expo File System Tutorial (Read, Write, Download Files) by Codevolution" /> (Placeholder)
    *   <YouTube videoId_ REACT_NATIVE_MANAGING_FILES_WITH_EXPO_FILE_SYSTEM_by_NotJustDev title="React Native - Managing Files with Expo File System by NotJust.dev" /> (Placeholder)

This completes the expansion for Module 5 of Course 3.
---
### Module 6: Debugging, Testing, and Deployment (Expanded)

This module covers essential skills for finalizing your React Native application: debugging, writing tests, and preparing for deployment to app stores, with expanded detail.

*   **Lesson 6.1: Debugging React Native Apps - Using the Developer Menu**
    *   Accessing the Developer Menu:
        *   Shake gesture on physical devices.
        *   Emulator shortcuts (e.g., `Cmd+D` on iOS Simulator, `Cmd+M` or `Ctrl+M` on Android Emulator).
    *   Key Options in the Developer Menu:
        *   **Reload:** Reloads the JavaScript bundle.
        *   **Debug JS Remotely / Open Debugger:** Opens Chrome DevTools (or preferred debugger) connected to your app's JavaScript context. Allows setting breakpoints, inspecting variables, using the console.
        *   **Enable/Disable Fast Refresh:** (Formerly Hot Reloading & Live Reloading). Instantly updates UI for most changes without losing component state.
        *   **Performance Monitor:** Shows an overlay with FPS, RAM usage, JS heap, View counts, etc.
        *   **Element Inspector:** Allows tapping on UI elements to see their properties and hierarchy (similar to web dev tools).
        *   **Toggle Inspector.**
    *   Understanding how remote JS debugging works (JS runs in Chrome's V8, not directly on device/emulator's JS engine).
    *   <YouTube videoId="4gPCMm2Qc3w" title="Debugging React Native Apps - Tips & Tools by Academind" /> (Recap and expand on Dev Menu)

*   **Lesson 6.2: Advanced Debugging with Chrome DevTools and React Native Debugger**
    *   **Chrome DevTools for React Native:**
        *   Console Tab: `console.log()`, `warn()`, `error()`, viewing logs from native modules.
        *   Sources Tab: Setting breakpoints in your JS code, stepping through execution (step over, step into, step out), inspecting call stack and variable scopes.
        *   Network Tab (limited for native requests, but can show `fetch`/`XMLHttpRequest` if debugger is attached).
    *   **React Native Debugger (Standalone Application):**
        *   Combines Chrome DevTools, React DevTools, and Redux DevTools (if using Redux) into one app.
        *   Installation and setup.
        *   Benefits: Dedicated window, better UI inspection with React DevTools, integrated state inspection for Redux.
    *   **React DevTools (Standalone or Browser Extension, connects to RN):**
        *   Inspecting the component hierarchy.
        *   Viewing and editing component props and state.
        *   Identifying component re-renders (profiler).
    *   <YouTube videoId_ REACT_NATIVE_DEBUGGING_WITH_CHROME_DEVTOOLS_AND_REACT_NATIVE_DEBUGGER_by_The_Net_Ninja title="React Native Debugging with Chrome DevTools and React Native Debugger by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId_ USING_REACT_DEVTOOLS_WITH_REACT_NATIVE_by_Codevolution title="Using React DevTools with React Native by Codevolution" /> (Placeholder)

*   **Lesson 6.3: Flipper - Extensible Mobile App Debugger by Facebook**
    *   What is Flipper? A platform for debugging iOS, Android, and React Native apps.
    *   Extensible via plugins.
    *   Built-in plugins:
        *   Logs: View device and app logs.
        *   Layout Inspector: Inspect native UI hierarchy and properties.
        *   Network Inspector: Inspect native network requests.
        *   Crash Reporter.
        *   Shared Preferences/AsyncStorage Viewer.
        *   React Native specific plugins (e.g., for Hermes debugger).
    *   Setting up Flipper with your React Native project (Bare RN often requires more setup than Expo).
    *   Benefits: Deeper native insights, unified debugging experience.
    *   <YouTube videoId_ INTRODUCTION_TO_FLIPPER_FOR_REACT_NATIVE_DEBUGGING_by_Facebook_Engineering title="Introduction to Flipper for React Native Debugging by Facebook Engineering" /> (Placeholder for official or good overview)
    *   <YouTube videoId_ FLIPPER_REACT_NATIVE_SETUP_AND_TUTORIAL_by_NotJustDev title="Flipper React Native Setup and Tutorial by NotJust.dev" /> (Placeholder)

*   **Lesson 6.4: Error Handling Strategies and Error Boundaries**
    *   Common types of errors in React Native: JavaScript errors, native crashes, network errors, promise rejections.
    *   Using `try...catch` blocks for synchronous JavaScript errors.
    *   Handling Promise rejections with `.catch()` or `try...catch` with `async/await`.
    *   **Error Boundaries (React feature applicable to React Native):**
        *   Class components that catch JavaScript errors anywhere in their child component tree, log those errors, and display a fallback UI instead of the crashed component tree.
        *   Implement `static getDerivedStateFromError(error)` to update state and `componentDidCatch(error, errorInfo)` to log error information.
        *   **Example:**
            ```javascript
            // class ErrorBoundary extends React.Component {
            //   constructor(props) { super(props); this.state = { hasError: false }; }
            //   static getDerivedStateFromError(error) { return { hasError: true }; }
            //   componentDidCatch(error, errorInfo) { logErrorToMyService(error, errorInfo); }
            //   render() { if (this.state.hasError) { return <FallbackUI />; } return this.props.children; }
            // }
            ```
        *   Wrap parts of your application (or the whole app) with an ErrorBoundary.
    *   Global error handlers (`ErrorUtils.setGlobalHandler` - use with caution).
    *   <YouTube videoId="Cswn5A0ZJ6c" title="React Error Boundaries In 11 Minutes by Web Dev Simplified" /> (Concept applies to RN)

*   **Lesson 6.5: Introduction to Testing in React Native - Why and What to Test**
    *   Why test? Catch bugs early, ensure code quality, facilitate refactoring, improve maintainability, provide documentation.
    *   Testing Pyramid:
        *   **Unit Tests:** Test individual functions or components in isolation. Fast, numerous.
        *   **Integration Tests:** Test how multiple components/modules work together.
        *   **End-to-End (E2E) Tests:** Test the entire application flow from a user's perspective. Slow, fewer.
    *   What to test in React Native:
        *   Component rendering (given certain props, does it render correctly?).
        *   Component behavior (user interactions, state changes).
        *   Business logic (functions, utilities).
        *   Redux actions, reducers, selectors (if using Redux).
        *   API interactions (mocking APIs).
    *   Tools: Jest (testing framework), React Native Testing Library (for component testing), Detox/Appium (for E2E).
    *   <YouTube videoId_ INTRODUCTION_TO_TESTING_REACT_NATIVE_APPS_by_Academind title="Introduction to Testing React Native Apps by Academind" /> (Placeholder)

*   **Lesson 6.6: Unit Testing with Jest - Setup and Basic Tests**
    *   Jest: A popular JavaScript testing framework, often included by default in React Native projects (Expo and React Native CLI).
    *   Key Jest concepts:
        *   Test files (e.g., `MyComponent.test.js` or `__tests__/MyComponent.test.js`).
        *   `describe(name, fn)`: Groups related tests.
        *   `it(name, fn)` or `test(name, fn)`: Defines an individual test case.
        *   `expect(value)`: Used with matcher functions to assert conditions.
        *   Matcher functions: `toBe()`, `toEqual()` (for objects/arrays), `toBeTruthy()`, `toBeFalsy()`, `toContain()`, `toHaveBeenCalled()`, `toMatchSnapshot()`, etc.
    *   Writing simple unit tests for utility functions.
        *   **Example:** `// sum.js: export const sum = (a,b) => a+b; // sum.test.js: import {sum} from './sum'; test('adds 1+2 to equal 3', () => { expect(sum(1,2)).toBe(3); });`
    *   Running tests: `npm test` or `yarn test`.
    *   Snapshot Testing: Jest captures a snapshot of a component's rendered output and compares it on subsequent runs. Useful for detecting unintentional UI changes.
    *   <YouTube videoId_ JEST_CRASH_COURSE_JAVASCRIPT_UNIT_TESTING_by_Traversy_Media title="Jest Crash Course - JavaScript Unit Testing by Traversy Media" /> (General Jest, applicable)
    *   <YouTube videoId_ REACT_NATIVE_UNIT_TESTING_WITH_JEST_GETTING_STARTED_by_Codevolution title="React Native Unit Testing with Jest - Getting Started by Codevolution" /> (Placeholder)

*   **Lesson 6.7: Component Testing with React Native Testing Library**
    *   React Native Testing Library (RNTL): Provides utilities to test React Native components in a way that resembles how users interact with them. Encourages testing behavior over implementation details.
    *   Installation: `@testing-library/react-native` (often included or easily added).
    *   Core RNTL functions:
        *   `render(Component)`: Renders the component.
        *   Query functions to find elements: `getByText`, `getByTestId`, `getByPlaceholderText`, `findBy*` (async), `queryBy*` (doesn't throw error if not found).
        *   `fireEvent`: Simulates user events (e.g., `fireEvent.press(button)`).
    *   Testing component rendering:
        *   **Example:** `const { getByText } = render(<MyButton title="Submit" />); expect(getByText('Submit')).toBeTruthy();`
    *   Testing component interactions:
        *   Simulating button presses, text input.
        *   Asserting that state changes or callbacks are invoked.
    *   Mocking child components or external dependencies (e.g., API calls) using Jest mocks.
    *   <YouTube videoId="FgnxcWiS5LQE" title="React Native Testing Tutorial with Jest & React Testing Library by The Net Ninja" />
    *   <YouTube videoId_ REACT_NATIVE_TESTING_LIBRARY_BEST_PRACTICES_by_Kent_C_Dodds title="React Native Testing Library Best Practices by Kent C. Dodds" /> (Placeholder - Kent is the author of Testing Library)

*   **Lesson 6.8: End-to-End (E2E) Testing Overview (Detox/Appium)**
    *   What is E2E testing? Testing the entire application flow from the user's perspective, interacting with the actual app running on an emulator/device.
    *   Why E2E tests? Catches integration issues, verifies critical user journeys.
    *   **Detox (by Wix):** Gray box E2E testing framework specifically for mobile apps.
        *   Fast and reliable by synchronizing with the app's UI thread.
        *   JavaScript-based test scripts.
    *   **Appium:** Open-source tool for automating native, mobile web, and hybrid applications.
        *   Uses WebDriver protocol, supports multiple languages for test scripts.
        *   Can be slower than Detox.
    *   Basic concepts: Writing test scripts (e.g., "launch app, tap login button, enter credentials, verify home screen appears"), selecting elements by ID/text, performing actions (tap, swipe, type), making assertions.
    *   This is an overview; full E2E testing setup and writing is a large topic.
    *   <YouTube videoId="s30shW0Lg5c" title="React Native E2E Testing with Detox - Getting Started by NotJust.dev" />
    *   <YouTube videoId_ APPIUM_TUTORIAL_FOR_REACT_NATIVE_E2E_TESTING_by_Appium_Pro title="Appium Tutorial for React Native E2E Testing by Appium Pro" /> (Placeholder)

*   **Lesson 6.9: Building for Release - Android (APK/AAB)**
    *   Difference between debug and release builds. Release builds are optimized, signed, and ready for distribution.
    *   **Generating a Signing Key:**
        *   Using `keytool` (part of JDK).
        *   Storing the keystore file (`.keystore` or `.jks`) securely.
    *   **Configuring Gradle for Release Signing:**
        *   Editing `android/app/build.gradle` to include signing configurations.
        *   Storing keystore password and alias credentials securely (e.g., in `gradle.properties`, environment variables, or CI secrets, NOT hardcoded in `build.gradle`).
    *   **Generating an Android App Bundle (AAB):** (Recommended by Google Play)
        *   `cd android && ./gradlew bundleRelease`
        *   AAB contains compiled code and resources for all device configurations; Google Play uses it to generate optimized APKs for each user.
    *   Generating a Universal APK (less common now for Play Store):
        *   `cd android && ./gradlew assembleRelease`
    *   Understanding ProGuard/R8 for code shrinking and obfuscation.
    *   <YouTube videoId="nfYLoK0V7AU" title="React Native - Generate Signed APK For Play Store (Android) by Code Step By Step" /> (Adapt for AAB)
    *   <YouTube videoId_ REACT_NATIVE_ANDROID_RELEASE_BUILD_AAB_KEYSTORE_GRADLE_by_Codevolution title="React Native Android Release Build (AAB, Keystore, Gradle) by Codevolution" /> (Placeholder)

*   **Lesson 6.10: Building for Release - iOS (IPA)**
    *   Requires macOS and Xcode.
    *   **Apple Developer Program Membership:** Needed for deploying to physical devices and App Store.
    *   **Certificates, Identifiers & Profiles:**
        *   App ID: Unique identifier for your app.
        *   Certificates (Development and Distribution): To sign your app.
        *   Provisioning Profiles (Development and Distribution): Connect certificates and App IDs to devices.
        *   Managing these in Xcode or Apple Developer portal.
    *   **Configuring Xcode for Release:**
        *   Setting bundle identifier, version, build number.
        *   Choosing signing team and provisioning profile.
        *   Scheme configuration (Release).
    *   **Archiving the App:** In Xcode (Product > Archive).
    *   **Distributing the App (Generating IPA):**
        *   From Xcode Organizer: Distribute App > App Store Connect (for TestFlight/App Store) or Ad Hoc/Enterprise.
        *   IPA file is created.
    *   <YouTube videoId_ REACT_NATIVE_IOS_RELEASE_BUILD_ARCHIVE_IPA_XCODE_by_The_Net_Ninja title="React Native iOS Release Build (Archive, IPA, Xcode) by The Net Ninja" /> (Placeholder)
    *   <YouTube videoId_ IOS_APP_SIGNING_AND_PROVISIONING_EXPLAINED_by_Ray_Wenderlich title="iOS App Signing and Provisioning Explained by Ray Wenderlich" /> (Placeholder - conceptual)

*   **Lesson 6.11: Over-The-Air (OTA) Updates (Expo Updates / CodePush)**
    *   What are OTA Updates? Updating the JavaScript bundle and assets of your app without needing to submit a new version to the app stores.
    *   Useful for bug fixes, small feature updates, A/B testing.
    *   Cannot update native code via OTA.
    *   **Expo Updates:**
        *   Built into Expo managed workflow and EAS Update service.
        *   Publishing updates via `expo publish` (classic) or `eas update` (modern).
        *   Configuration in `app.json` / `app.config.js` (update channels, runtime versions).
    *   **Microsoft CodePush (for Bare RN or ejected Expo apps):**
        *   A service for deploying OTA updates.
        *   Requires integrating CodePush SDK into your app and using App Center CLI to release updates.
    *   Benefits and limitations of OTA updates.
    *   <YouTube videoId_ EXPO_OTA_UPDATES_WITH_EAS_UPDATE_by_Expo_Team title="Expo OTA Updates with EAS Update by Expo Team" /> (Placeholder)
    *   <YouTube videoId_ REACT_NATIVE_CODEPUSH_TUTORIAL_by_NotJustDev title="React Native CodePush Tutorial by NotJust.dev" /> (Placeholder)

*   **Lesson 6.12: Publishing to Google Play Store (Android)**
    *   Creating a Google Play Developer account (one-time fee).
    *   Preparing Store Listing:
        *   App Title, Short Description, Full Description.
        *   Screenshots (phone, tablet), Feature Graphic, Promo Video.
        *   App Icon.
        *   Categorization, Content Rating questionnaire.
        *   Privacy Policy URL.
    *   Uploading your Android App Bundle (AAB) to a new release.
    *   Managing Release Tracks: Internal Testing, Closed Testing (Alpha), Open Testing (Beta), Production.
    *   Setting pricing and distribution (countries).
    *   Submitting for review (Google's review process is usually faster than Apple's).
    *   Monitoring app performance, reviews, and crashes in Google Play Console.
    *   <YouTube videoId="HZeT0t4GBhQ" title="Publish React Native App to Google Play Store & Apple App Store (2023) by Code with Nader" /> (Focus on Play Store part)

*   **Lesson 6.13: Publishing to Apple App Store (iOS)**
    *   Enrolling in the Apple Developer Program (annual fee).
    *   Creating an App Store Connect record for your app.
    *   Preparing Store Listing:
        *   App Name, Subtitle, Bundle ID.
        *   App Previews (videos) and Screenshots (for different device sizes).
        *   Promotional Text, Description, Keywords.
        *   App Icon.
        *   Category, Content Rating.
        *   Privacy Policy URL, App Privacy details (data collection practices).
    *   Uploading your build (IPA) using Xcode (Archive then Distribute App) or Transporter app.
    *   **TestFlight:** Apple's platform for beta testing with internal and external testers.
    *   Submitting for App Store Review (can take a few hours to several days). Addressing rejections if any.
    *   Managing releases, pricing, and availability.
    *   <YouTube videoId="HZeT0t4GBhQ" title="Publish React Native App to Google Play Store & Apple App Store (2023) by Code with Nader" /> (Focus on App Store part)
    *   <YouTube videoId_ IOS_APP_STORE_SUBMISSION_GUIDE_by_CodeWithChris title="iOS App Store Submission Guide by CodeWithChris" /> (Placeholder)

*   **Lesson 6.14: App Store Optimization (ASO) Basics**
    *   What is ASO? The process of optimizing mobile apps to rank higher in app store search results.
    *   Key factors:
        *   App Title and Subtitle (keywords).
        *   Keywords field (iOS).
        *   App Description (keywords, compelling copy).
        *   App Icon (first impression).
        *   Screenshots and App Previews (showcasing value).
        *   Ratings and Reviews.
        *   Update frequency.
        *   Downloads and engagement.
    *   Tools for ASO research (e.g., AppTweak, Sensor Tower - mention, not detailed usage).
    *   This is an introduction to the concept.
    *   <YouTube videoId_ APP_STORE_OPTIMIZATION_ASO_TUTORIAL_FOR_BEGINNERS_by_AppFigures title="App Store Optimization (ASO) Tutorial for Beginners by AppFigures" /> (Placeholder)

*   **Lesson 6.15: Post-Launch - Monitoring, Analytics, and User Feedback**
    *   Monitoring app stability and performance (Firebase Crashlytics, Sentry, App Store consoles).
    *   App Analytics (Firebase Analytics, Mixpanel, Amplitude, App Store consoles):
        *   Tracking user engagement, retention, screen views, events.
        *   Understanding user behavior to inform future development.
    *   Collecting and responding to user reviews and feedback.
    *   Planning for future updates and iterations based on data and feedback.
    *   The app development lifecycle is continuous.
    *   <YouTube videoId_ REACT_NATIVE_APP_ANALYTICS_WITH_FIREBASE_by_NotJustDev title="React Native App Analytics with Firebase by NotJust.dev" /> (Placeholder)
    *   <YouTube videoId_ IMPORTANCE_OF_USER_FEEDBACK_FOR_MOBILE_APPS_by_MobileAction title="Importance of User Feedback for Mobile Apps by MobileAction" /> (Placeholder)

This completes the expansion for all modules of Course 3.
