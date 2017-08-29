# ApiDemos

Project creation step by step

1. git clone https://github.com/android/platform_development.git
2. import platform_development/samples/ApiDemos to Android Studio
3. Rename **preference_switch** to **preference_switch.xml**
4. Exclude **MmsMessagingDemo.java** and **MmsWapPushReceiver.java** from compilation, because thoes classes tried to reference **com.google.android.mms** which is not included in ApiDemos
5. Add *try/catch* for **DocumentsContract** series API in **DocumentsSample.java**
