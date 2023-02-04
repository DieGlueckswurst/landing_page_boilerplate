# Landing Page

## Splash Screen
To change the App Icon simply change the asset in "assets/app_icons/app_icon.png" 
and run:

    flutter pub run flutter_native_splash:create

You can change the background color in `pubspec.yaml` inside `flutter_native_splash:`.


## Firebase Hosting 

**Step 1**

`firebase init`

**Step 2**

select `Hosting:...`

**Step 3**

>public directory:      
`build/web`

>single-page app?       
`y`

**Step 4**

`flutter build web`

**Step 5**

`firebsae deploy`

