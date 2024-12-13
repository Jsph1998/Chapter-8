# Chapter-8
In this chapter, i learned to use the Navigator widget to manage a stack of routes so as to allow navigation between pages. I optionally passed data to the navigation page and back to the original page. The hero animation allows a widget transition to fly into place from one page to another. The widget to animate from and to is wrapped in a Hero widget by a unique key. I used the BottomNavigationBar widget to display a horizontal list of BottomNavigation-BarItems containing an icon and a title at the bottom of the page. When the user taps each BottomNavigationBarItem, the appropriate page is displayed. To enhance the look of a bottom navigation bar, you used the BottomAppBar widget and enabled the optional notch. The notch is the result of embedding a FloatingActionButton to a BottomAppBar by setting the BottomAppBar
shape to a CircularNotchedRectangle() class and setting the Scaffold floatingActionButton-Location property to FloatingActionButtonLocation.endDocked.
The TabBar widget displays a horizontal row of tabs. The tabs property takes a List of widgets, and tabs are added by using the Tab widget. The TabBarView widget is used in conjunction with the TabBar widget to display the page of the selected tab. Users can swipe left or right to change content 
or tap each Tab. The TabController class handled the syncing of the TabBar and selected TabBar-
View. The TabController requires the use of with SingleTickerProviderStateMixin in the class.
The Drawer widget allows the user to slide a panel from left or right. The Drawer widget is added by setting the Scaffold drawer or endDrawer property. To easily align menu items in a list, you pass a ListView as a child of the Drawer. Since this menu list is short, i use the standard ListView constructor instead of a ListView builder, which is covered in the next chapter. You have two prebuilt drawer header options, UserAccountsDrawerHeader or DrawerHeader. When the user taps one of the menu items, the onTap property calls Navigator.pop() to close Drawer and calls Navigator.
push() to navigate to the selected page.
