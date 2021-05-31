# CookieClickerUiPath
Play [Cookie Clicker](https://orteil.dashnet.org/cookieclicker/) using [UiPath](https://www.uipath.com/)!

This automatically clicks the big cookie, the golden cookie and autopurchases a set number of items while randomly purchasing the cheapest upgrade ocassionally.

Assumptions/Notes 
1. It uses the Edge Browser (Can be changed in CookieClickerSequence.xaml, haven't tried it yet though).
2. There's a boolean flag you'll need to set to false somewhere in Main.xaml if you don't want it to clear your progress everytime you run it 
3. You can run Main.xaml in "Debug" mode, but it's definitely waaaay faster when you "Run" Main.xaml 

TODO:
1. Insert logic for Ascending and beyond
