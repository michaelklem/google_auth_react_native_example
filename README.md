# google_auth_react_native_example
Basic app to show Google Auth working

I needed to generate a debug.keystore file even though one already existed. I used this command:

~/projects/<app_root>/android/app$ keytool -genkey -v -keystore debug.keystore -storepass android -alias androiddebugkey -keypass android -keyalg RSA -keysize 2048 -validity 10000


References:
https://www.instamobile.io/mobile-development/google-login-react-native-firebase/

https://www.freecodecamp.org/news/google-login-with-react-native-and-firebase/
