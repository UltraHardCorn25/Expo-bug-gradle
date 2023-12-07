Running 'gradlew :app:assembleDebug' in /home/expo/workingdir/build/android
Downloading https://services.gradle.org/distributions/gradle-8.0.1-all.zip
10
%.
20%
30%
40%
50
%.
60%
70
%.
80
%.
90
%.
100%
Welcome to Gradle 8.0.1!
Here are the highlights of this release:
 - Improvements to the Kotlin DSL
 - Fine-grained parallelism from the first build with configuration cache
 - Configurable Gradle user home cache cleanup
For more details see https://docs.gradle.org/8.0.1/release-notes.html
To honour the JVM settings for this build a single-use Daemon process will be forked. See https://docs.gradle.org/8.0.1/userguide/gradle_daemon.html#sec:disabling_the_daemon.
Daemon will be stopped at the end of the build
> Task :expo-updates-gradle-plugin:pluginDescriptors
> Task :expo-updates-gradle-plugin:processResources
> Task :expo-dev-launcher-gradle-plugin:pluginDescriptors
> Task :expo-dev-launcher-gradle-plugin:processResources
> Task :gradle-plugin:pluginDescriptors
> Task :gradle-plugin:processResources
> Task :expo-dev-launcher-gradle-plugin:compileKotlin
> Task :expo-dev-launcher-gradle-plugin:compileJava NO-SOURCE
> Task :expo-dev-launcher-gradle-plugin:classes
> Task :expo-dev-launcher-gradle-plugin:jar
> Task :expo-dev-launcher-gradle-plugin:inspectClassesForKotlinIC
> Task :gradle-plugin:compileKotlin
> Task :gradle-plugin:compileJava NO-SOURCE
> Task :gradle-plugin:classes
> Task :gradle-plugin:jar
> Task :gradle-plugin:inspectClassesForKotlinIC
> Task :expo-updates-gradle-plugin:compileKotlin
> Task :expo-updates-gradle-plugin:compileJava
NO-SOURCE
> Task :expo-updates-gradle-plugin:classes
> Task :expo-updates-gradle-plugin:jar
> Task :expo-updates-gradle-plugin:inspectClassesForKotlinIC
> Configure project :app
 ℹ️  Applying gradle plugin 'expo-dev-launcher-gradle-plugin' (expo-dev-launcher@2.4.14)
 ℹ️  Applying gradle plugin 'expo-updates-gradle-plugin' (expo-updates@0.18.17)
> Configure project :expo-modules-core
Checking the license for package NDK (Side by side) 23.1.7779620 in /home/expo/Android/Sdk/licenses
License for package NDK (Side by side) 23.1.7779620 accepted.
Preparing "Install NDK (Side by side) 23.1.7779620 (revision: 23.1.7779620)".
"Install NDK (Side by side) 23.1.7779620 (revision: 23.1.7779620)" ready.
Installing NDK (Side by side) 23.1.7779620 in /home/expo/Android/Sdk/ndk/23.1.7779620
"Install NDK (Side by side) 23.1.7779620 (revision: 23.1.7779620)" complete.
"Install NDK (Side by side) 23.1.7779620 (revision: 23.1.7779620)" finished.
Checking the license for package CMake 3.22.1 in /home/expo/Android/Sdk/licenses
License for package CMake 3.22.1 accepted.
Preparing "Install CMake 3.22.1 (revision: 3.22.1)".
"Install CMake 3.22.1 (revision: 3.22.1)" ready.
Installing CMake 3.22.1 in /home/expo/Android/Sdk/cmake/3.22.1
"Install CMake 3.22.1 (revision: 3.22.1)" complete.
"Install CMake 3.22.1 (revision: 3.22.1)" finished.
> Configure project :expo
Using expo modules
  - expo-application (5.3.1)
  - expo-constants (14.4.2)
  - expo-dev-client (2.4.12)
  - expo-dev-launcher (2.4.14)
  - expo-dev-menu (3.2.2)
  - expo-eas-client (0.6.0)
  - expo-file-system (15.4.4)
  - expo-font (11.4.0)
  - expo-json-utils (0.7.1)
  - expo-keep-awake (12.3.0)
  - expo-linear-gradient (12.3.0)
  - expo-manifests (0.7.2)
  - expo-modules-core (1.5.11)
  - expo-modules-core$android-annotation (1.5.11)
  - expo-modules-core$android-annotation-processor (1.5.11)
  - expo-splash-screen (0.20.5)
  - expo-structured-headers (3.3.0)
  - expo-updates (0.18.17)
> Configure project :react-native-firebase
react-native-firebase: using React Native prebuilt binary from /home/expo/workingdir/build/node_modules/react-native/android
> Configure project :react-native-firebase_app
:react-native-firebase_app package.json found at /home/expo/workingdir/build/node_modules/@react-native-firebase/app/package.json
:react-native-firebase_app:firebase.bom using default value: 32.2.3
:react-native-firebase_app:play.play-services-auth using default value: 20.6.0
:react-native-firebase_app package.json found at /home/expo/workingdir/build/node_modules/@react-native-firebase/app/package.json
:react-native-firebase_app:version set from package.json: 18.4.0 (18,4,0 - 18004000)
:react-native-firebase_app:android.compileSdk using custom value: 33
:react-native-firebase_app:android.targetSdk using custom value: 33
:react-native-firebase_app:android.minSdk using custom value: 21
:react-native-firebase_app:reactNativeAndroidDir /home/expo/workingdir/build/node_modules/react-native/android
> Configure project :react-native-firebase_firestore
:react-native-firebase_firestore package.json found at /home/expo/workingdir/build/node_modules/@react-native-firebase/firestore/package.json
:react-native-firebase_app package.json found at /home/expo/workingdir/build/node_modules/@react-native-firebase/app/package.json
:react-native-firebase_firestore:firebase.bom using default value: 32.2.3
:react-native-firebase_firestore package.json found at /home/expo/workingdir/build/node_modules/@react-native-firebase/firestore/package.json
:react-native-firebase_firestore:version set from package.json: 18.4.0 (18,4,0 - 18004000)
:react-native-firebase_firestore:android.compileSdk using custom value: 33
:react-native-firebase_firestore:android.targetSdk using custom value: 33
:react-native-firebase_firestore:android.minSdk using custom value: 21
:react-native-firebase_firestore:reactNativeAndroidDir /home/expo/workingdir/build/node_modules/react-native/android
> Configure project :react-native-firebase_messaging
:react-native-firebase_messaging package.json found at /home/expo/workingdir/build/node_modules/@react-native-firebase/messaging/package.json
:react-native-firebase_app package.json found at /home/expo/workingdir/build/node_modules/@react-native-firebase/app/package.json
:react-native-firebase_messaging:firebase.bom using default value: 32.2.3
:react-native-firebase_messaging package.json found at /home/expo/workingdir/build/node_modules/@react-native-firebase/messaging/package.json
:react-native-firebase_messaging:version set from package.json: 18.4.0 (18,4,0 - 18004000)
:react-native-firebase_messaging:android.compileSdk using custom value: 33
:react-native-firebase_messaging:android.targetSdk using custom value: 33
:react-native-firebase_messaging:android.minSdk using custom value: 21
:react-native-firebase_messaging:reactNativeAndroidDir /home/expo/workingdir/build/node_modules/react-native/android
Checking the license for package Android SDK Build-Tools 30.0.3 in /home/expo/Android/Sdk/licenses
License for package Android SDK Build-Tools 30.0.3 accepted.
Preparing "Install Android SDK Build-Tools 30.0.3 (revision: 30.0.3)".
"Install Android SDK Build-Tools 30.0.3 (revision: 30.0.3)" ready.
Installing Android SDK Build-Tools 30.0.3 in /home/expo/Android/Sdk/build-tools/30.0.3
"Install Android SDK Build-Tools 30.0.3 (revision: 30.0.3)" complete.
"Install Android SDK Build-Tools 30.0.3 (revision: 30.0.3)" finished.
Checking the license for package Android SDK Platform 33 in /home/expo/Android/Sdk/licenses
License for package Android SDK Platform 33 accepted.
Preparing "Install Android SDK Platform 33 (revision: 3)".
"Install Android SDK Platform 33 (revision: 3)" ready.
Installing Android SDK Platform 33 in /home/expo/Android/Sdk/platforms/android-33
"Install Android SDK Platform 33 (revision: 3)" complete.
"Install Android SDK Platform 33 (revision: 3)" finished.
Checking the license for package Android SDK Build-Tools 33 in /home/expo/Android/Sdk/licenses
License for package Android SDK Build-Tools 33 accepted.
Preparing "Install Android SDK Build-Tools 33 (revision: 33.0.0)".
"Install Android SDK Build-Tools 33 (revision: 33.0.0)" ready.
Installing Android SDK Build-Tools 33 in /home/expo/Android/Sdk/build-tools/33.0.0
"Install Android SDK Build-Tools 33 (revision: 33.0.0)" complete.
"Install Android SDK Build-Tools 33 (revision: 33.0.0)" finished.
The Kotlin Gradle plugin was loaded multiple times in different subprojects, which is not supported and may break the build. 
This might happen in subprojects that apply the Kotlin plugins with the Gradle 'plugins { ... }' DSL if they specify explicit versions, even if the versions are equal.
Please add the Kotlin plugin to the common parent project or the root project, then remove the versions in the subprojects.
If the parent project does not need the plugin, add 'apply false' to the plugin line.
See: https://docs.gradle.org/current/userguide/plugins.html#sec:subprojects_plugins_dsl
The Kotlin plugin was loaded in the following projects: ':expo', ':expo-modules-core', ':react-native-safe-area-context', ':react-native-screens'
> Task :expo-modules-core$android-annotation-processor:processResources
> Task :expo-application:preBuild UP-TO-DATE
> Task :expo-application:preDebugBuild UP-TO-DATE
> Task :expo-modules-core:preBuild UP-TO-DATE
> Task :expo-modules-core:preDebugBuild UP-TO-DATE
> Task :expo-modules-core:compileDebugAidl NO-SOURCE
> Task :expo-application:compileDebugAidl NO-SOURCE
> Task :expo-constants:preBuild UP-TO-DATE
> Task :expo-constants:preDebugBuild UP-TO-DATE
> Task :expo-constants:compileDebugAidl NO-SOURCE
> Task :expo-dev-client:preBuild UP-TO-DATE
> Task :expo-dev-client:preDebugBuild UP-TO-DATE
> Task :expo-dev-client:compileDebugAidl NO-SOURCE
> Task :expo-dev-launcher:preBuild UP-TO-DATE
> Task :expo-dev-launcher:preDebugBuild UP-TO-DATE
> Task :expo-dev-menu:preBuild UP-TO-DATE
> Task :expo-dev-menu:preDebugBuild UP-TO-DATE
> Task :expo-dev-menu-interface:preBuild UP-TO-DATE
> Task :expo-dev-menu-interface:preDebugBuild UP-TO-DATE
> Task :expo-dev-menu-interface:compileDebugAidl NO-SOURCE
> Task :expo-json-utils:preBuild UP-TO-DATE
> Task :expo-json-utils:preDebugBuild UP-TO-DATE
> Task :expo-json-utils:compileDebugAidl NO-SOURCE
> Task :expo-manifests:preBuild UP-TO-DATE
> Task :expo-manifests:preDebugBuild UP-TO-DATE
> Task :expo-manifests:compileDebugAidl NO-SOURCE
> Task :expo-dev-menu:compileDebugAidl NO-SOURCE
> Task :expo-eas-client:preBuild UP-TO-DATE
> Task :expo-eas-client:preDebugBuild UP-TO-DATE
> Task :expo-eas-client:compileDebugAidl NO-SOURCE
> Task :expo-structured-headers:preBuild UP-TO-DATE
> Task :expo-structured-headers:preDebugBuild UP-TO-DATE
> Task :expo-structured-headers:compileDebugAidl NO-SOURCE
> Task :expo-updates:preBuild UP-TO-DATE
> Task :expo-updates:preDebugBuild UP-TO-DATE
> Task :expo-updates-interface:preBuild UP-TO-DATE
> Task :expo-updates-interface:preDebugBuild UP-TO-DATE
> Task :expo-updates-interface:compileDebugAidl NO-SOURCE
> Task :expo-updates:compileDebugAidl NO-SOURCE
> Task :expo-dev-launcher:compileDebugAidl NO-SOURCE
> Task :expo-file-system:preBuild UP-TO-DATE
> Task :expo-file-system:preDebugBuild UP-TO-DATE
> Task :expo-file-system:compileDebugAidl NO-SOURCE
> Task :expo-font:preBuild UP-TO-DATE
> Task :expo-font:preDebugBuild UP-TO-DATE
> Task :expo-font:compileDebugAidl NO-SOURCE
> Task :expo-keep-awake:preBuild UP-TO-DATE
> Task :expo-keep-awake:preDebugBuild UP-TO-DATE
> Task :expo-keep-awake:compileDebugAidl NO-SOURCE
> Task :expo-linear-gradient:preBuild UP-TO-DATE
> Task :expo-linear-gradient:preDebugBuild UP-TO-DATE
> Task :expo-linear-gradient:compileDebugAidl NO-SOURCE
> Task :expo-splash-screen:preBuild UP-TO-DATE
> Task :expo-splash-screen:preDebugBuild UP-TO-DATE
> Task :expo-splash-screen:compileDebugAidl NO-SOURCE
> Task :react-native-firebase:preBuild UP-TO-DATE
> Task :react-native-firebase:preDebugBuild UP-TO-DATE
> Task :react-native-firebase:compileDebugAidl NO-SOURCE
> Task :react-native-firebase_app:preBuild UP-TO-DATE
> Task :react-native-firebase_app:preDebugBuild UP-TO-DATE
> Task :react-native-firebase_app:compileDebugAidl NO-SOURCE
> Task :react-native-firebase_firestore:preBuild UP-TO-DATE
> Task :react-native-firebase_firestore:preDebugBuild UP-TO-DATE
> Task :react-native-firebase_firestore:compileDebugAidl NO-SOURCE
> Task :react-native-firebase_messaging:preBuild UP-TO-DATE
> Task :react-native-firebase_messaging:preDebugBuild UP-TO-DATE
> Task :react-native-firebase_messaging:compileDebugAidl NO-SOURCE
> Task :react-native-picker_picker:preBuild UP-TO-DATE
> Task :react-native-picker_picker:preDebugBuild UP-TO-DATE
> Task :react-native-picker_picker:compileDebugAidl NO-SOURCE
> Task :react-native-safe-area-context:preBuild UP-TO-DATE
> Task :react-native-safe-area-context:preDebugBuild UP-TO-DATE
> Task :react-native-safe-area-context:compileDebugAidl NO-SOURCE
> Task :react-native-screens:preBuild UP-TO-DATE
> Task :react-native-screens:preDebugBuild UP-TO-DATE
> Task :react-native-screens:compileDebugAidl NO-SOURCE
> Task :expo-application:packageDebugRenderscript NO-SOURCE
> Task :expo-constants:packageDebugRenderscript NO-SOURCE
> Task :expo-dev-client:packageDebugRenderscript NO-SOURCE
> Task :expo-dev-launcher:packageDebugRenderscript NO-SOURCE
> Task :expo-dev-menu:packageDebugRenderscript NO-SOURCE
> Task :expo-eas-client:packageDebugRenderscript NO-SOURCE
> Task :expo-file-system:packageDebugRenderscript NO-SOURCE
> Task :expo-font:packageDebugRenderscript NO-SOURCE
> Task :expo-json-utils:packageDebugRenderscript NO-SOURCE
> Task :expo-keep-awake:packageDebugRenderscript NO-SOURCE
> Task :expo-linear-gradient:packageDebugRenderscript NO-SOURCE
> Task :expo-manifests:packageDebugRenderscript NO-SOURCE
> Task :expo-modules-core:packageDebugRenderscript NO-SOURCE
> Task :expo-splash-screen:packageDebugRenderscript NO-SOURCE
> Task :expo-structured-headers:packageDebugRenderscript NO-SOURCE
> Task :expo-updates:packageDebugRenderscript NO-SOURCE
> Task :react-native-firebase:packageDebugRenderscript NO-SOURCE
> Task :react-native-firebase_app:packageDebugRenderscript NO-SOURCE
> Task :react-native-firebase_firestore:packageDebugRenderscript NO-SOURCE
> Task :react-native-firebase_messaging:packageDebugRenderscript NO-SOURCE
> Task :react-native-picker_picker:packageDebugRenderscript NO-SOURCE
> Task :react-native-safe-area-context:packageDebugRenderscript NO-SOURCE
> Task :react-native-screens:packageDebugRenderscript
NO-SOURCE
> Task :expo:generateExpoModulesPackageList
> Task :expo:preBuild
> Task :expo:preDebugBuild
> Task :expo:compileDebugAidl NO-SOURCE
> Task :expo:packageDebugRenderscript NO-SOURCE
> Task :expo-application:writeDebugAarMetadata
> Task :expo-constants:writeDebugAarMetadata
> Task :expo:writeDebugAarMetadata
> Task :expo-dev-client:writeDebugAarMetadata
> Task :expo-dev-launcher:writeDebugAarMetadata
> Task :expo-dev-menu:writeDebugAarMetadata
> Task :expo-dev-menu-interface:writeDebugAarMetadata
> Task :expo-eas-client:writeDebugAarMetadata
> Task :expo-file-system:writeDebugAarMetadata
> Task :expo-font:writeDebugAarMetadata
> Task :expo-json-utils:writeDebugAarMetadata
> Task :expo-keep-awake:writeDebugAarMetadata
> Task :expo-linear-gradient:writeDebugAarMetadata
> Task :expo-manifests:writeDebugAarMetadata
> Task :expo-modules-core:writeDebugAarMetadata
> Task :expo-splash-screen:writeDebugAarMetadata
> Task :expo-updates:writeDebugAarMetadata
> Task :expo-structured-headers:writeDebugAarMetadata
> Task :expo-updates-interface:writeDebugAarMetadata
> Task :react-native-firebase:writeDebugAarMetadata
> Task :react-native-firebase_firestore:writeDebugAarMetadata
> Task :react-native-firebase_app:writeDebugAarMetadata
> Task :react-native-firebase_messaging:writeDebugAarMetadata
> Task :react-native-picker_picker:writeDebugAarMetadata
> Task :react-native-safe-area-context:writeDebugAarMetadata
> Task :react-native-screens:writeDebugAarMetadata
> Task :expo:compileDebugRenderscript NO-SOURCE
> Task :expo-application:compileDebugRenderscript NO-SOURCE
> Task :expo:generateDebugResValues
> Task :expo-application:generateDebugResValues
> Task :expo:generateDebugResources
> Task :expo-modules-core$android-annotation:processResources NO-SOURCE
> Task :expo-application:generateDebugResources
> Task :expo-modules-core$android-annotation:compileKotlin
> Task :expo-modules-core$android-annotation:compileJava
NO-SOURCE
> Task :expo-modules-core$android-annotation:classes UP-TO-DATE
> Task :expo-modules-core$android-annotation:jar
> Task :expo-modules-core$android-annotation:inspectClassesForKotlinIC
> Task :expo-application:packageDebugResources
> Task :expo-constants:compileDebugRenderscript NO-SOURCE
> Task :expo:packageDebugResources
> Task :expo-dev-client:compileDebugRenderscript NO-SOURCE
> Task :expo-constants:generateDebugResValues
> Task :expo-constants:generateDebugResources
> Task :expo-dev-client:generateDebugResValues
> Task :expo-dev-client:generateDebugResources
> Task :expo-constants:packageDebugResources
> Task :expo-dev-menu-interface:packageDebugRenderscript NO-SOURCE
> Task :expo-updates-interface:packageDebugRenderscript NO-SOURCE
> Task :expo-dev-launcher:compileDebugRenderscript NO-SOURCE
> Task :expo-dev-client:packageDebugResources
> Task :expo-dev-menu:compileDebugRenderscript NO-SOURCE
> Task :expo-dev-launcher:generateDebugResValues
> Task :expo-dev-launcher:generateDebugResources
> Task :expo-dev-menu:generateDebugResValues
> Task :expo-dev-menu:generateDebugResources
> Task :expo-dev-menu:packageDebugResources
> Task :expo-dev-launcher:packageDebugResources
> Task :expo-modules-core$android-annotation-processor:compileKotlin
> Task :expo-modules-core$android-annotation-processor:compileJava NO-SOURCE
> Task :expo-modules-core$android-annotation-processor:classes
> Task :expo-modules-core$android-annotation-processor:jar
> Task :expo-modules-core$android-annotation-processor:inspectClassesForKotlinIC
> Task :expo-dev-menu-interface:compileDebugRenderscript NO-SOURCE
> Task :expo-dev-menu-interface:generateDebugResValues
> Task :expo-dev-menu-interface:generateDebugResources
> Task :expo-dev-menu-interface:packageDebugResources
> Task :expo-eas-client:compileDebugRenderscript NO-SOURCE
> Task :expo-eas-client:generateDebugResValues
> Task :expo-eas-client:generateDebugResources
> Task :expo-eas-client:packageDebugResources
> Task :expo-file-system:compileDebugRenderscript NO-SOURCE
> Task :expo-file-system:generateDebugResValues
> Task :expo-file-system:generateDebugResources
> Task :expo-file-system:packageDebugResources
> Task :expo-font:compileDebugRenderscript NO-SOURCE
> Task :expo-font:generateDebugResValues
> Task :expo-font:generateDebugResources
> Task :expo-font:packageDebugResources
> Task :expo-json-utils:compileDebugRenderscript NO-SOURCE
> Task :expo-json-utils:generateDebugResValues
> Task :expo-json-utils:generateDebugResources
> Task :expo-json-utils:packageDebugResources
> Task :expo-keep-awake:compileDebugRenderscript NO-SOURCE
> Task :expo-keep-awake:generateDebugResValues
> Task :expo-keep-awake:generateDebugResources
> Task :expo-keep-awake:packageDebugResources
> Task :expo-linear-gradient:compileDebugRenderscript NO-SOURCE
> Task :expo-linear-gradient:generateDebugResValues
> Task :expo-linear-gradient:generateDebugResources
> Task :expo-linear-gradient:packageDebugResources
> Task :expo-manifests:compileDebugRenderscript NO-SOURCE
> Task :expo-manifests:generateDebugResValues
> Task :expo-manifests:generateDebugResources
> Task :expo-manifests:packageDebugResources
> Task :expo-modules-core:compileDebugRenderscript NO-SOURCE
> Task :expo-modules-core:generateDebugResValues
> Task :expo-modules-core:generateDebugResources
> Task :expo-modules-core:packageDebugResources
> Task :expo-splash-screen:compileDebugRenderscript NO-SOURCE
> Task :expo-splash-screen:generateDebugResValues
> Task :expo-splash-screen:generateDebugResources
> Task :expo-splash-screen:packageDebugResources
> Task :expo-structured-headers:compileDebugRenderscript NO-SOURCE
> Task :expo-structured-headers:generateDebugResValues
> Task :expo-structured-headers:generateDebugResources
> Task :expo-structured-headers:packageDebugResources
> Task :expo-updates:compileDebugRenderscript NO-SOURCE
> Task :expo-updates:generateDebugResValues
> Task :expo-updates:generateDebugResources
> Task :expo-updates:packageDebugResources
> Task :expo-updates-interface:compileDebugRenderscript NO-SOURCE
> Task :expo-updates-interface:generateDebugResValues
> Task :expo-updates-interface:generateDebugResources
> Task :expo-updates-interface:packageDebugResources
> Task :react-native-firebase:compileDebugRenderscript NO-SOURCE
> Task :react-native-firebase:generateDebugResValues
> Task :react-native-firebase:generateDebugResources
> Task :react-native-firebase:packageDebugResources
> Task :react-native-firebase_app:compileDebugRenderscript NO-SOURCE
> Task :react-native-firebase_app:generateDebugResValues
> Task :react-native-firebase_app:generateDebugResources
> Task :react-native-firebase_app:packageDebugResources
> Task :react-native-firebase_firestore:compileDebugRenderscript NO-SOURCE
> Task :react-native-firebase_firestore:generateDebugResValues
> Task :react-native-firebase_firestore:generateDebugResources
> Task :react-native-firebase_firestore:packageDebugResources
> Task :react-native-firebase_messaging:compileDebugRenderscript NO-SOURCE
> Task :react-native-picker_picker:compileDebugRenderscript NO-SOURCE
> Task :react-native-safe-area-context:compileDebugRenderscript NO-SOURCE
> Task :react-native-firebase_messaging:generateDebugResValues
> Task :react-native-firebase_messaging:generateDebugResources
> Task :react-native-firebase_messaging:packageDebugResources
> Task :react-native-picker_picker:generateDebugResValues
> Task :react-native-picker_picker:generateDebugResources
> Task :react-native-picker_picker:packageDebugResources
> Task :react-native-safe-area-context:generateDebugResValues
> Task :react-native-safe-area-context:generateDebugResources
> Task :react-native-safe-area-context:packageDebugResources
> Task :react-native-screens:compileDebugRenderscript NO-SOURCE
> Task :react-native-screens:generateDebugResValues
> Task :react-native-screens:generateDebugResources
> Task :react-native-screens:packageDebugResources
> Task :expo-application:extractDeepLinksDebug
> Task :expo:extractDeepLinksDebug
> Task :expo:processDebugManifest
> Task :expo-constants:extractDeepLinksDebug
> Task :expo-application:processDebugManifest
> Task :expo-dev-client:extractDeepLinksDebug
> Task :expo-constants:processDebugManifest
> Task :expo-dev-client:processDebugManifest
> Task :expo-dev-launcher:extractDeepLinksDebug
> Task :expo-dev-menu:extractDeepLinksDebug
> Task :expo-dev-launcher:processDebugManifest
> Task :expo-dev-menu-interface:extractDeepLinksDebug
> Task :expo-dev-menu:processDebugManifest
> Task :expo-dev-menu-interface:processDebugManifest
> Task :expo-eas-client:extractDeepLinksDebug
> Task :expo-file-system:extractDeepLinksDebug
> Task :expo-eas-client:processDebugManifest
> Task :expo-font:extractDeepLinksDebug
> Task :expo-file-system:processDebugManifest
/home/expo/workingdir/build/node_modules/expo-file-system/android/src/main/AndroidManifest.xml:6:9-8:20 Warning:
	provider#expo.modules.filesystem.FileSystemFileProvider@android:authorities was tagged at AndroidManifest.xml:6 to replace other declarations but no other declaration present
> Task :expo-json-utils:extractDeepLinksDebug
> Task :expo-font:processDebugManifest
> Task :expo-keep-awake:extractDeepLinksDebug
> Task :expo-json-utils:processDebugManifest
> Task :expo-keep-awake:processDebugManifest
> Task :expo-linear-gradient:extractDeepLinksDebug
> Task :expo-manifests:extractDeepLinksDebug
> Task :expo-linear-gradient:processDebugManifest
> Task :expo-manifests:processDebugManifest
> Task :expo-modules-core:extractDeepLinksDebug
> Task :expo-splash-screen:extractDeepLinksDebug
> Task :expo-splash-screen:processDebugManifest
> Task :expo-structured-headers:extractDeepLinksDebug
> Task :expo-modules-core:processDebugManifest
/home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/AndroidManifest.xml:8:9-11:45 Warning:
	meta-data#com.facebook.soloader.enabled@android:value was tagged at AndroidManifest.xml:8 to replace other declarations but no other declaration present
> Task :expo-updates:extractDeepLinksDebug
> Task :expo-structured-headers:processDebugManifest
> Task :expo-updates:processDebugManifest
> Task :expo-updates-interface:extractDeepLinksDebug
> Task :react-native-firebase:extractDeepLinksDebug
> Task :expo-updates-interface:processDebugManifest
> Task :react-native-firebase_app:extractDeepLinksDebug
> Task :react-native-firebase:processDebugManifest
package="io.invertase.firebase" found in source AndroidManifest.xml: /home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/AndroidManifest.xml.
Setting the namespace via a source AndroidManifest.xml's package attribute is deprecated.
Please instead set the namespace (or testNamespace) in the module's build.gradle file, as described here: https://developer.android.com/studio/build/configure-app-module#set-namespace
This migration can be done automatically using the AGP Upgrade Assistant, please refer to https://developer.android.com/studio/build/agp-upgrade-assistant for more information.
> Task :react-native-firebase_firestore:extractDeepLinksDebug
> Task :react-native-firebase_app:processDebugManifest
package="io.invertase.firebase" found in source AndroidManifest.xml: /home/expo/workingdir/build/node_modules/@react-native-firebase/app/android/src/main/AndroidManifest.xml.
Setting the namespace via a source AndroidManifest.xml's package attribute is deprecated.
Please instead set the namespace (or testNamespace) in the module's build.gradle file, as described here: https://developer.android.com/studio/build/configure-app-module#set-namespace
This migration can be done automatically using the AGP Upgrade Assistant, please refer to https://developer.android.com/studio/build/agp-upgrade-assistant for more information.
> Task :react-native-firebase_messaging:extractDeepLinksDebug
> Task :react-native-firebase_firestore:processDebugManifest
package="io.invertase.firebase.firestore" found in source AndroidManifest.xml: /home/expo/workingdir/build/node_modules/@react-native-firebase/firestore/android/src/main/AndroidManifest.xml.
Setting the namespace via a source AndroidManifest.xml's package attribute is deprecated.
Please instead set the namespace (or testNamespace) in the module's build.gradle file, as described here: https://developer.android.com/studio/build/configure-app-module#set-namespace
This migration can be done automatically using the AGP Upgrade Assistant, please refer to https://developer.android.com/studio/build/agp-upgrade-assistant for more information.
> Task :react-native-picker_picker:extractDeepLinksDebug
> Task :react-native-picker_picker:processDebugManifest
package="com.reactnativecommunity.picker" found in source AndroidManifest.xml: /home/expo/workingdir/build/node_modules/@react-native-picker/picker/android/src/main/AndroidManifest.xml.
Setting the namespace via a source AndroidManifest.xml's package attribute is deprecated.
Please instead set the namespace (or testNamespace) in the module's build.gradle file, as described here: https://developer.android.com/studio/build/configure-app-module#set-namespace
This migration can be done automatically using the AGP Upgrade Assistant, please refer to https://developer.android.com/studio/build/agp-upgrade-assistant for more information.
> Task :react-native-firebase_messaging:processDebugManifest
package="io.invertase.firebase.messaging" found in source AndroidManifest.xml: /home/expo/workingdir/build/node_modules/@react-native-firebase/messaging/android/src/main/AndroidManifest.xml.
Setting the namespace via a source AndroidManifest.xml's package attribute is deprecated.
Please instead set the namespace (or testNamespace) in the module's build.gradle file, as described here: https://developer.android.com/studio/build/configure-app-module#set-namespace
This migration can be done automatically using the AGP Upgrade Assistant, please refer to https://developer.android.com/studio/build/agp-upgrade-assistant for more information.
> Task :react-native-safe-area-context:extractDeepLinksDebug
> Task :react-native-screens:extractDeepLinksDebug
> Task :react-native-screens:processDebugManifest
package="com.swmansion.rnscreens" found in source AndroidManifest.xml: /home/expo/workingdir/build/node_modules/react-native-screens/android/src/main/AndroidManifest.xml.
Setting the namespace via a source AndroidManifest.xml's package attribute is deprecated.
Please instead set the namespace (or testNamespace) in the module's build.gradle file, as described here: https://developer.android.com/studio/build/configure-app-module#set-namespace
This migration can be done automatically using the AGP Upgrade Assistant, please refer to https://developer.android.com/studio/build/agp-upgrade-assistant for more information.
> Task :react-native-safe-area-context:processDebugManifest
package="com.th3rdwave.safeareacontext" found in source AndroidManifest.xml: /home/expo/workingdir/build/node_modules/react-native-safe-area-context/android/src/main/AndroidManifest.xml.
Setting the namespace via a source AndroidManifest.xml's package attribute is deprecated.
Please instead set the namespace (or testNamespace) in the module's build.gradle file, as described here: https://developer.android.com/studio/build/configure-app-module#set-namespace
This migration can be done automatically using the AGP Upgrade Assistant, please refer to https://developer.android.com/studio/build/agp-upgrade-assistant for more information.
> Task :expo:compileDebugLibraryResources
> Task :expo-application:parseDebugLocalResources
> Task :expo-modules-core:parseDebugLocalResources
> Task :expo:parseDebugLocalResources
> Task :expo-dev-client:parseDebugLocalResources
> Task :expo-constants:parseDebugLocalResources
> Task :expo-dev-client:generateDebugRFile
> Task :expo-dev-launcher:parseDebugLocalResources
> Task :expo-dev-menu:parseDebugLocalResources
> Task :expo-dev-menu-interface:parseDebugLocalResources
> Task :expo-json-utils:parseDebugLocalResources
> Task :expo-json-utils:generateDebugRFile
> Task :expo-manifests:parseDebugLocalResources
> Task :expo-manifests:generateDebugRFile
> Task :expo-eas-client:parseDebugLocalResources
> Task :expo-structured-headers:parseDebugLocalResources
> Task :expo-structured-headers:generateDebugRFile
> Task :expo-updates:parseDebugLocalResources
> Task :expo-updates-interface:parseDebugLocalResources
> Task :expo-updates-interface:generateDebugRFile
> Task :expo-file-system:parseDebugLocalResources
> Task :expo-font:parseDebugLocalResources
> Task :expo-keep-awake:parseDebugLocalResources
> Task :expo-linear-gradient:parseDebugLocalResources
> Task :expo-splash-screen:parseDebugLocalResources
> Task :expo-application:compileDebugLibraryResources
> Task :expo-constants:compileDebugLibraryResources
> Task :expo-dev-client:compileDebugLibraryResources
> Task :expo-dev-launcher:compileDebugLibraryResources
> Task :expo-dev-menu:compileDebugLibraryResources
> Task :expo-eas-client:compileDebugLibraryResources
> Task :expo-file-system:compileDebugLibraryResources
> Task :expo-font:compileDebugLibraryResources
> Task :expo-json-utils:compileDebugLibraryResources
> Task :expo-keep-awake:compileDebugLibraryResources
> Task :expo-linear-gradient:compileDebugLibraryResources
> Task :expo-manifests:compileDebugLibraryResources
> Task :expo-splash-screen:compileDebugLibraryResources
> Task :expo-structured-headers:compileDebugLibraryResources
> Task :expo-updates:compileDebugLibraryResources
> Task :expo-updates-interface:compileDebugLibraryResources
> Task :react-native-firebase:compileDebugLibraryResources
> Task :react-native-firebase:parseDebugLocalResources
> Task :app:buildCodegenCLI SKIPPED
> Task :app:generateCodegenSchemaFromJavaScript SKIPPED
> Task :app:generateCodegenArtifactsFromSchema SKIPPED
> Task :app:generatePackageList
> Task :app:preBuild
> Task :app:preDebugBuild
> Task :app:mergeDebugNativeDebugMetadata NO-SOURCE
> Task :app:compileDebugAidl NO-SOURCE
> Task :app:compileDebugRenderscript NO-SOURCE
> Task :app:generateDebugBuildConfig
> Task :app:javaPreCompileDebug
> Task :react-native-firebase:generateDebugRFile
> Task :expo-dev-menu-interface:compileDebugLibraryResources
> Task :expo-modules-core:generateDebugRFile
> Task :expo-modules-core:compileDebugLibraryResources
> Task :expo-constants:generateDebugRFile
> Task :expo-dev-menu-interface:generateDebugRFile
> Task :expo-eas-client:generateDebugRFile
> Task :expo-application:generateDebugRFile
> Task :expo-file-system:generateDebugRFile
> Task :expo-updates:generateDebugRFile
> Task :expo-font:generateDebugRFile
> Task :expo-keep-awake:generateDebugRFile
> Task :expo-linear-gradient:generateDebugRFile
> Task :expo-dev-menu:generateDebugRFile
> Task :react-native-firebase_app:compileDebugLibraryResources
> Task :react-native-firebase_app:parseDebugLocalResources
> Task :expo-splash-screen:generateDebugRFile
> Task :react-native-firebase_firestore:compileDebugLibraryResources
> Task :react-native-firebase_firestore:parseDebugLocalResources
> Task :react-native-firebase_messaging:compileDebugLibraryResources
> Task :expo-dev-launcher:generateDebugRFile
> Task :react-native-firebase_messaging:parseDebugLocalResources
> Task :react-native-picker_picker:compileDebugLibraryResources
> Task :react-native-picker_picker:parseDebugLocalResources
> Task :react-native-firebase_app:generateDebugRFile
> Task :react-native-picker_picker:generateDebugRFile
> Task :expo:generateDebugRFile
> Task :react-native-safe-area-context:compileDebugLibraryResources
> Task :react-native-safe-area-context:parseDebugLocalResources
> Task :react-native-safe-area-context:generateDebugRFile
> Task :react-native-firebase_messaging:generateDebugRFile
> Task :react-native-firebase_firestore:generateDebugRFile
> Task :expo:generateDebugBuildConfig
> Task :expo-application:generateDebugBuildConfig
> Task :expo-modules-core:generateDebugBuildConfig
> Task :react-native-screens:compileDebugLibraryResources
> Task :react-native-screens:parseDebugLocalResources
> Task :expo-application:javaPreCompileDebug
> Task :expo-constants:generateDebugBuildConfig
> Task :expo-constants:javaPreCompileDebug
> Task :expo-dev-client:dataBindingMergeDependencyArtifactsDebug
> Task :react-native-screens:generateDebugRFile
> Task :expo-dev-client:dataBindingGenBaseClassesDebug
> Task :expo-dev-client:generateDebugBuildConfig
> Task :expo-dev-client:compileDebugKotlin NO-SOURCE
> Task :expo-dev-client:javaPreCompileDebug
> Task :expo-dev-launcher:dataBindingMergeDependencyArtifactsDebug
> Task :expo-dev-launcher:dataBindingGenBaseClassesDebug
> Task :expo-dev-launcher:generateDebugBuildConfig
> Task :expo-dev-menu:generateDebugBuildConfig
> Task :expo-dev-menu-interface:generateDebugBuildConfig
> Task :expo-dev-menu-interface:compileDebugKotlin
> Task :expo-modules-core:javaPreCompileDebug
> Task :expo-dev-menu-interface:javaPreCompileDebug
> Task :expo-dev-client:compileDebugJavaWithJavac
> Task :expo-dev-client:bundleLibCompileToJarDebug
> Task :expo-json-utils:generateDebugBuildConfig
> Task :expo-dev-menu-interface:compileDebugJavaWithJavac
> Task :expo-dev-menu-interface:bundleLibCompileToJarDebug
> Task :expo-json-utils:javaPreCompileDebug
> Task :expo-manifests:generateDebugBuildConfig
> Task :expo-manifests:javaPreCompileDebug
> Task :expo-dev-menu:javaPreCompileDebug
> Task :expo-eas-client:generateDebugBuildConfig
> Task :expo-eas-client:javaPreCompileDebug
> Task :expo-structured-headers:generateDebugBuildConfig
> Task :expo-structured-headers:compileDebugKotlin NO-SOURCE
> Task :expo-structured-headers:javaPreCompileDebug
> Task :expo-json-utils:compileDebugKotlin
> Task :expo-json-utils:compileDebugJavaWithJavac
> Task :expo-json-utils:bundleLibCompileToJarDebug
> Task :expo-structured-headers:compileDebugJavaWithJavac
> Task :expo-structured-headers:bundleLibCompileToJarDebug
> Task :expo-updates:generateDebugBuildConfig
> Task :expo-updates-interface:generateDebugBuildConfig
> Task :expo-updates-interface:compileDebugKotlin NO-SOURCE
> Task :expo-updates-interface:javaPreCompileDebug
> Task :expo-updates-interface:compileDebugJavaWithJavac
> Task :expo-updates-interface:bundleLibCompileToJarDebug
> Task :expo-updates:javaPreCompileDebug
> Task :expo-dev-launcher:javaPreCompileDebug
> Task :expo-file-system:generateDebugBuildConfig
> Task :expo-file-system:javaPreCompileDebug
> Task :expo-font:generateDebugBuildConfig
> Task :expo-font:javaPreCompileDebug
> Task :expo-keep-awake:generateDebugBuildConfig
> Task :expo-keep-awake:javaPreCompileDebug
> Task :expo-linear-gradient:generateDebugBuildConfig
> Task :expo-linear-gradient:javaPreCompileDebug
> Task :expo-splash-screen:generateDebugBuildConfig
> Task :expo-splash-screen:javaPreCompileDebug
> Task :expo:javaPreCompileDebug
> Task :react-native-firebase:generateDebugBuildConfig
> Task :react-native-firebase:javaPreCompileDebug
> Task :expo-manifests:compileDebugKotlin
w: file:///home/expo/workingdir/build/node_modules/expo-manifests/android/src/main/java/expo/modules/manifests/core/BaseLegacyManifest.kt:10:16 This declaration overrides deprecated member but not marked as deprecated itself. This deprecation won't be inherited in future releases. Please add @Deprecated annotation or suppress. See https://youtrack.jetbrains.com/issue/KT-47902 for details
w: file:///home/expo/workingdir/build/node_modules/expo-manifests/android/src/main/java/expo/modules/manifests/core/BaseLegacyManifest.kt:10:86 'getLegacyID(): String' is deprecated. Prefer scopeKey or projectId depending on use case
w: file:///home/expo/workingdir/build/node_modules/expo-manifests/android/src/main/java/expo/modules/manifests/core/BaseLegacyManifest.kt:12:72 'getStableLegacyID(): String?' is deprecated. Overrides deprecated member in 'expo.modules.manifests.core.Manifest'. Prefer scopeKey or projectId depending on use case
w: file:///home/expo/workingdir/build/node_modules/expo-manifests/android/src/main/java/expo/modules/manifests/core/Manifest.kt:28:12 'getRawJson(): JSONObject' is deprecated. Prefer to use specific field getters
w: file:///home/expo/workingdir/build/node_modules/expo-manifests/android/src/main/java/expo/modules/manifests/core/Manifest.kt:239:65 Elvis operator (?:) always returns the left operand of non-nullable type List<PluginType>
w: file:///home/expo/workingdir/build/node_modules/expo-manifests/android/src/main/java/expo/modules/manifests/core/NewManifest.kt:18:16 This declaration overrides deprecated member but not marked as deprecated itself. This deprecation won't be inherited in future releases. Please add @Deprecated annotation or suppress. See https://youtrack.jetbrains.com/issue/KT-47902 for details
w: file:///home/expo/workingdir/build/node_modules/expo-manifests/android/src/main/java/expo/modules/manifests/core/NewManifest.kt:52:72 'getSDKVersionFromRuntimeVersion(): String?' is deprecated. exposdk:... runtime version is deprecated
> Task :app:checkDebugAarMetadata
> Task :app:generateDebugResValues
> Task :app:processDebugGoogleServices
Parsing json file: /home/expo/workingdir/build/android/app/google-services.json
> Task :app:mapDebugSourceSetPaths
> Task :app:generateDebugResources
> Task :expo-manifests:compileDebugJavaWithJavac
> Task :expo-manifests:bundleLibCompileToJarDebug
> Task :react-native-firebase_app:generateDebugBuildConfig
> Task :react-native-firebase_app:javaPreCompileDebug
> Task :react-native-firebase:compileDebugJavaWithJavac
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/messaging/RNFirebaseMessaging.java:7: error: cannot find symbol
import android.support.v4.app.NotificationManagerCompat;
                             ^
  symbol:   class NotificationManagerCompat
  location: package android.support.v4.app
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/messaging/RNFirebaseMessaging.java:8: error: package android.support.v4.content does not exist
import android.support.v4.content.LocalBroadcastManager;
                                 ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/messaging/RNFirebaseMessagingService.java:5: error: package android.support.v4.content does not exist
import android.support.v4.content.LocalBroadcastManager;
                                 ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/RNFirebaseBackgroundNotificationActionReceiver.java:8: error: cannot find symbol
import android.support.v4.app.RemoteInput;
                             ^
  symbol:   class RemoteInput
  location: package android.support.v4.app
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/RNFirebaseNotificationManager.java:20: error: package android.support.annotation does not exist
import android.support.annotation.RequiresApi;
                                 ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/RNFirebaseNotificationManager.java:21: error: package android.support.v4.content does not exist
import android.support.v4.content.LocalBroadcastManager;
                                 ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/RNFirebaseNotifications.java:10: error: cannot find symbol
import android.support.v4.app.RemoteInput;
                             ^
  symbol:   class RemoteInput
  location: package android.support.v4.app
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/RNFirebaseNotifications.java:11: error: package android.support.v4.content does not exist
import android.support.v4.content.LocalBroadcastManager;
                                 ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:15: error: cannot find symbol
import android.support.v4.app.NotificationCompat;
                             ^
  symbol:   class NotificationCompat
  location: package android.support.v4.app
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:16: error: cannot find symbol
import android.support.v4.app.RemoteInput;
                             ^
  symbol:   class RemoteInput
  location: package android.support.v4.app
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:412: error: package NotificationCompat does not exist
  private NotificationCompat.Action createAction(
                            ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:499: error: cannot find symbol
  private RemoteInput createRemoteInput(Bundle remoteInput) {
          ^
  symbol:   class RemoteInput
  location: class DisplayNotificationTask
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/analytics/RNFirebaseAnalyticsPackage.java:3: error: package android.support.annotation does not exist
import android.support.annotation.RequiresPermission;
                                 ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/ReactNativeFirebaseAppRegistrar.java:20: error: package android.support.annotation does not exist
import android.support.annotation.Keep;
                                 ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/ReactNativeFirebaseAppRegistrar.java:29: error: cannot find symbol
@Keep
 ^
  symbol: class Keep
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/storage/RNFirebaseStoragePackage.java:3: error: package android.support.annotation does not exist
import android.support.annotation.RequiresPermission;
                                 ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/RNFirebaseNotificationManager.java:370: error: cannot find symbol
@RequiresApi(api = 26)
   ^
  symbol:   class RequiresApi
  location: class RNFirebaseNotificationManager
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/RNFirebaseNotificationManager.java:384: error: cannot find symbol
  @RequiresApi(api = 26)
   ^
  symbol:   class RequiresApi
  location: class RNFirebaseNotificationManager
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/RNFirebaseNotificationManager.java:398: error: cannot find symbol
  @RequiresApi(api = 26)
   ^
  symbol:   class RequiresApi
  location: class RNFirebaseNotificationManager
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/RNFirebaseNotificationManager.java:414: error: cannot find symbol
  @RequiresApi(api = 26)
   ^
  symbol:   class RequiresApi
  location: class RNFirebaseNotificationManager
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/RNFirebaseNotificationManager.java:457: error: cannot find symbol
  @RequiresApi(api = 26)
   ^
  symbol:   class RequiresApi
  location: class RNFirebaseNotificationManager
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/analytics/RNFirebaseAnalyticsPackage.java:17: error: cannot find symbol
  @RequiresPermission(
   ^
  symbol:   class RequiresPermission
  location: class RNFirebaseAnalyticsPackage
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/storage/RNFirebaseStoragePackage.java:17: error: cannot find symbol
  @RequiresPermission(
   ^
  symbol:   class RequiresPermission
  location: class RNFirebaseStoragePackage
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/messaging/RNFirebaseMessaging.java:36: error: cannot find symbol
    LocalBroadcastManager localBroadcastManager = LocalBroadcastManager.getInstance(context);
    ^
  symbol:   class LocalBroadcastManager
  location: class RNFirebaseMessaging
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/messaging/RNFirebaseMessaging.java:36: error: cannot find symbol
    LocalBroadcastManager localBroadcastManager = LocalBroadcastManager.getInstance(context);
                                                  ^
  symbol:   variable LocalBroadcastManager
  location: class RNFirebaseMessaging
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/messaging/RNFirebaseMessaging.java:90: error: cannot find symbol
    Boolean enabled = NotificationManagerCompat
                      ^
  symbol:   variable NotificationManagerCompat
  location: class RNFirebaseMessaging
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/messaging/RNFirebaseMessagingService.java:26: error: cannot find symbol
    LocalBroadcastManager
    ^
  symbol:   variable LocalBroadcastManager
  location: class RNFirebaseMessagingService
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/messaging/RNFirebaseMessagingService.java:41: error: cannot find symbol
      LocalBroadcastManager
      ^
  symbol:   variable LocalBroadcastManager
  location: class RNFirebaseMessagingService
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/messaging/RNFirebaseMessagingService.java:51: error: cannot find symbol
        LocalBroadcastManager
        ^
  symbol:   variable LocalBroadcastManager
  location: class RNFirebaseMessagingService
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/RNFirebaseBackgroundNotificationActionReceiver.java:62: error: cannot find symbol
      Bundle remoteInput = RemoteInput.getResultsFromIntent(intent);
                           ^
  symbol:   variable RemoteInput
  location: class RNFirebaseBackgroundNotificationActionReceiver
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/RNFirebaseNotificationManager.java:204: error: cannot find symbol
      LocalBroadcastManager
      ^
  symbol:   variable LocalBroadcastManager
  location: class RNFirebaseNotificationManager
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/RNFirebaseNotifications.java:54: error: cannot find symbol
    LocalBroadcastManager localBroadcastManager = LocalBroadcastManager.getInstance(context);
    ^
  symbol:   class LocalBroadcastManager
  location: class RNFirebaseNotifications
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/RNFirebaseNotifications.java:54: error: cannot find symbol
    LocalBroadcastManager localBroadcastManager = LocalBroadcastManager.getInstance(context);
                                                  ^
  symbol:   variable LocalBroadcastManager
  location: class RNFirebaseNotifications
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/RNFirebaseNotifications.java:308: error: cannot find symbol
    Bundle remoteInput = RemoteInput.getResultsFromIntent(intent);
                         ^
  symbol:   variable RemoteInput
  location: class RNFirebaseNotifications
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:81: error: package NotificationCompat does not exist
      NotificationCompat.Builder nb;
                        ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:84: error: package NotificationCompat does not exist
        nb = new NotificationCompat.Builder(context, channelId);
                                   ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:87: error: package NotificationCompat does not exist
        nb = new NotificationCompat.Builder(context);
                                   ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:130: error: package NotificationCompat does not exist
        NotificationCompat.BigPictureStyle bp = new NotificationCompat.BigPictureStyle();
                          ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:130: error: package NotificationCompat does not exist
        NotificationCompat.BigPictureStyle bp = new NotificationCompat.BigPictureStyle();
                                                                      ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:163: error: package NotificationCompat does not exist
        NotificationCompat.BigTextStyle bt = new NotificationCompat.BigTextStyle();
                          ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:163: error: package NotificationCompat does not exist
        NotificationCompat.BigTextStyle bt = new NotificationCompat.BigTextStyle();
                                                                   ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:366: error: package NotificationCompat does not exist
          NotificationCompat.Action action = createAction(context, a, intentClass, notification);
                            ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:429: error: package NotificationCompat.Action does not exist
    NotificationCompat.Action.Builder ab = new NotificationCompat.Action.Builder(
                             ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:429: error: package NotificationCompat.Action does not exist
    NotificationCompat.Action.Builder ab = new NotificationCompat.Action.Builder(
                                                                        ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:442: error: cannot find symbol
        RemoteInput remoteInput = createRemoteInput(ri);
        ^
  symbol:   class RemoteInput
  location: class DisplayNotificationTask
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:501: error: package RemoteInput does not exist
    RemoteInput.Builder rb = new RemoteInput.Builder(resultKey);
               ^
/home/expo/workingdir/build/node_modules/react-native-firebase/android/src/main/java/io/invertase/firebase/notifications/DisplayNotificationTask.java:501: error: package RemoteInput does not exist
    RemoteInput.Builder rb = new RemoteInput.Builder(resultKey);
                                            ^
> Task :react-native-firebase_app:compileDebugJavaWithJavac
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
> Task :app:createDebugCompatibleScreenManifests
> Task :app:extractDeepLinksDebug
> Task :app:mergeDebugResources
> Task :react-native-firebase_app:bundleLibCompileToJarDebug
> Task :react-native-firebase_firestore:generateDebugBuildConfig
> Task :react-native-firebase_firestore:javaPreCompileDebug
> Task :react-native-firebase:compileDebugJavaWithJavac FAILED
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Note: Some input files use unchecked or unsafe operations.
Note: Recompile with -Xlint:unchecked for details.
47 errors
> Task :app:processDebugMainManifest
[:react-native-firebase_app] /home/expo/workingdir/build/node_modules/@react-native-firebase/app/android/build/intermediates/merged_manifest/debug/AndroidManifest.xml Warning:
	Namespace 'io.invertase.firebase' used in: :react-native-firebase_app, :react-native-firebase.
/home/expo/workingdir/build/android/app/src/debug/AndroidManifest.xml:6:5-162 Warning:
	application@android:usesCleartextTraffic was tagged at AndroidManifest.xml:6 to replace other declarations but no other declaration present
/home/expo/workingdir/build/android/app/src/debug/AndroidManifest.xml:21:9-30:20 Warning:
	provider#expo.modules.filesystem.FileSystemFileProvider@android:authorities was tagged at AndroidManifest.xml:21 to replace other declarations but no other declaration present
> Task :expo-modules-core:compileDebugKotlin
> Task :react-native-firebase_firestore:compileDebugJavaWithJavac
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Note: Some input files use unchecked or unsafe operations.
Note: Recompile with -Xlint:unchecked for details.
> Task :expo-modules-core:compileDebugKotlin
w: Argument -Xopt-in is deprecated. Please use -opt-in instead
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/adapters/react/permissions/PermissionsService.kt:157:30 'getPackageInfo(String, Int): PackageInfo!' is deprecated. Deprecated in Java
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/core/utilities/EmulatorUtilities.kt:30:13 'SERIAL: String!' is deprecated. Deprecated in Java
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/Promise.kt:68:18 This declaration overrides deprecated member but not marked as deprecated itself. This deprecation won't be inherited in future releases. Please add @Deprecated annotation or suppress. See https://youtrack.jetbrains.com/issue/KT-47902 for details
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/Utils.kt:8:3 Expected performance impact from inlining is insignificant. Inlining works best for functions with parameters of functional types
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/activityresult/ActivityResultsManager.kt:52:24 Parameter 'activity' is never used
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/activityresult/AppContextActivityResultRegistry.kt:119:51 'getParcelableExtra(String!): T?' is deprecated. Deprecated in Java
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/activityresult/AppContextActivityResultRegistry.kt:180:26 'getParcelable(String?): T?' is deprecated. Deprecated in Java
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/activityresult/AppContextActivityResultRegistry.kt:271:83 'getParcelable(String?): T?' is deprecated. Deprecated in Java
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/activityresult/DataPersistor.kt:67:20 'getSerializable(String?): Serializable?' is deprecated. Deprecated in Java
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/activityresult/DataPersistor.kt:85:26 'getSerializable(String?): Serializable?' is deprecated. Deprecated in Java
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/devtools/cdp/CdpNetworkTypes.kt:184:54 Parameter 'request' is never used
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/devtools/cdp/CdpNetworkTypes.kt:208:54 Parameter 'request' is never used
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/devtools/cdp/CdpNetworkTypes.kt:228:15 Parameter 'now' is never used
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/devtools/cdp/CdpNetworkTypes.kt:228:54 Parameter 'request' is never used
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/events/KModuleEventEmitterWrapper.kt:90:7 'constructor Event<T : Event<(raw) Event<*>>!>(Int)' is deprecated. Deprecated in Java
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/jni/JavaScriptObject.kt:88:33 Parameter 'null' is never used
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/jni/JavaScriptObject.kt:89:34 Parameter 'null' is never used
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/jni/JavaScriptObject.kt:130:5 Parameter 'null' is never used
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/types/Either.kt:24:11 Parameter 'type' is never used
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/types/Either.kt:27:11 Parameter 'type' is never used
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/types/Either.kt:44:11 Parameter 'type' is never used
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/types/Either.kt:59:11 Parameter 'type' is never used
w: file:///home/expo/workingdir/build/node_modules/expo-modules-core/android/src/main/java/expo/modules/kotlin/types/JSTypeConverterHelper.kt:44:17 'get(String!): Any?' is deprecated. Deprecated in Java
w: Detected multiple Kotlin daemon sessions at build/kotlin/sessions
Deprecated Gradle features were used in this build, making it incompatible with Gradle 9.0.
You can use '--warning-mode all' to show the individual deprecation warnings and determine if they come from your own scripts or plugins.
See https://docs.gradle.org/8.0.1/userguide/command_line_interface.html#sec:command_line_warnings
310 actionable tasks: 310 executed
FAILURE: Build failed with an exception.
* What went wrong:
Execution failed for task ':react-native-firebase:compileDebugJavaWithJavac'.
> Compilation failed; see the compiler error output for details.
* Try:
> Run with --stacktrace option to get the stack trace.
> Run with --info or --debug option to get more log output.
> Run with --scan to get full insights.
* Get more help at https://help.gradle.org
BUILD FAILED in 4m 33s
Error: Gradle build failed with unknown error. See logs for the "Run gradlew" phase for more information.
