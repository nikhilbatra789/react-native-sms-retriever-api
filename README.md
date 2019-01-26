
# react-native-sms-retriever

## Getting started

`$ npm install react-native-sms-retriever --save`

### Mostly automatic installation

`$ react-native link react-native-sms-retriever`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-sms-retriever` and add `RNSmsRetriever.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNSmsRetriever.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNSmsRetrieverPackage;` to the imports at the top of the file
  - Add `new RNSmsRetrieverPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-sms-retriever'
  	project(':react-native-sms-retriever').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-sms-retriever/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-sms-retriever')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNSmsRetriever.sln` in `node_modules/react-native-sms-retriever/windows/RNSmsRetriever.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Sms.Retriever.RNSmsRetriever;` to the usings at the top of the file
  - Add `new RNSmsRetrieverPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNSmsRetriever from 'react-native-sms-retriever';

// TODO: What to do with the module?
RNSmsRetriever;
```
  
