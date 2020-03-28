# Android_BottomNavigation
Guide on how to set up an app with bottom navigation and the navigation component.
## Description
This is a really simple app: we are just able to display four different fragments by using bottom navigation.
## Important notes
If you look at the app you can guess quite easily how it works. The only tricky part is to understand how the bottom_nav menu and the navigator are connected.
In order to make these two elements cooperate we just need to specify consistent ids for the items in the menu: these must be the same of the fragments ids in the navigator xml. To better understand compare the file res/navigation/navigator.xml to res/menu/bottom_nav.xml.
