Things to remember

***For changing status bar color light theme
  -> themes.xml
  -> <resources>
         <style name="Theme.Woof" parent="android:Theme.Material.Light.NoActionBar">
             <item name="android:statusBarColor">@color/grey_50</item>
             <item name="android:windowLightStatusBar">true</item> //Override Resources in values-v23 //override and delete this
         </style>
     </resources>
    
    Dark theme
    -> In the res folder, add a new Android Resources Directory called values-night.
    -> Navigate to app > src > main > res > values-night.
    -> Within values-night, add a Values Resource File called themes.xml.
    -> <resources>
           <style name="Theme.Woof" parent="android:style/Theme.Material.NoActionBar">
               <item name="android:statusBarColor">@color/grey_900</item>
           </style>
       </resources>

***Source
https://developer.android.com/codelabs/basic-android-kotlin-compose-material-theming?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-compose-unit-3-pathway-3%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-compose-material-theming#4
