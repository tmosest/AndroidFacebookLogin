# AndroidFacebookLogin
Simple Facebook SDK Login on Android

##Signup as Facebook Developer:
Go to Facebook's Developer site and sign up after that they will walk you through creating a project of your choosing.

##Add Facebook SDK to project:
1) Add the Maven Central Repository to build.gradle before dependencies:

repositories {
        mavenCentral()
    }
    
2) Add compile 'com.facebook.android:facebook-android-sdk:[4,5)' to your other build gradle.

3) Synch gradles and download any packages if there is an error.

##Generate Key for Facebook:

keytool -exportcert -alias androiddebugkey -keystore ~/.android/debug.keystore | openssl sha1 -binary | openssl base64
