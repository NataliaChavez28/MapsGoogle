# MapsGoogle
Taller12

<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    package="com.example.mapaandroid">

    <application
        android:allowBackup="true"
        android:dataExtractionRules="@xml/data_extraction_rules"
        android:fullBackupContent="@xml/backup_rules"
        android:icon="@mipmap/ic_launcher"
        android:label="@string/app_name"
        android:roundIcon="@mipmap/ic_launcher_round"
        android:supportsRtl="true"
        android:theme="@style/Theme.MapaAndroid"
        tools:targetApi="31">

        <!--
             TODO: Before you run your application, you need a Google Maps API key.

             To get one, follow the directions here:

                https://developers.google.com/maps/documentation/android-sdk/get-api-key

             Once you have your API key (it starts with "AIza"), define a new property in your
             project's local.properties file (e.g. MAPS_API_KEY=Aiza...), and replace the
             "YOUR_API_KEY" string in this file with "${MAPS_API_KEY}".
        -->
        <meta-data
            android:name="com.google.android.geo.AIzaSyAEWdthdrCvOQe_0ii0FDkOIebveaSZfhA"
            android:value="AIzaSyAEWdthdrCvOQe_0ii0FDkOIebveaSZfhA" />

        <activity
            android:name=".MapsActivity"
            android:exported="true"
            android:label="@string/title_activity_maps">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
    </application>

</manifest>
