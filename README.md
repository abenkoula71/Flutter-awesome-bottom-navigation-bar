# Flutter-awesome-bottom-navigat
<h1>🐱‍👤 Fast code and awesome design-ui for flutter navigation bar 🔥</h1>
<hr>

<img src="https://raw.githubusercontent.com/leesnhyun/flashy_tab_bar/master/docs/animation.gif" alt="flash"  />

<hr>
<h2>Getting Started #</h2>
<h4>First you need to add flashy_tab_bar 0.0.3 in the dependency at pubspec.yaml:</h4>
<pre><code> dependencies:
  ...
  flashy_tab_bar: ^0.0.3 </code></pre>

<h2>Basic Usage #</h2>
<h4>Add this inside your main.dart or your page !</h4>
<pre><code>
bottomNavigationBar: FlashyTabBar(
     selectedIndex: _selectedIndex,
     showElevation: true,
     onItemSelected: (index) => setState(() {
       _selectedIndex = index;
     }),
     items: [
        FlashyTabBarItem(
          icon: Icon(Icons.event),
          title: Text('Events'),
        ),
        FlashyTabBarItem(
          icon: Icon(Icons.search),
          title: Text('Search'),
        ),
        FlashyTabBarItem(
          icon: Icon(Icons.highlight),
          title: Text('Highlights'),
        ),
        FlashyTabBarItem(
          icon: Icon(Icons.settings),
          title: Text('Settings'),
        ),
        FlashyTabBarItem(
          icon: Icon(Icons.settings),
          title: Text('한국어'),
        ),
      ],
),
</code></pre>

<h4>and Add this also in your Class </h4>
<pre><code>
var _selectedIndex = 0 ;
</code></pre>



Note From : flashy_tab_bar in <a href="https://pub.dev/packages/flashy_tab_bar">pub.dev</a> !! 
<br>
Note : This flashy_tab_bar Don't Support Null Safety if you need flashy_tab_bar with null Safty install :
flashy_tab_bar2 from => <a href="https://pub.dev/packages/flashy_tab_bar2">pub.dev</a>

<h1> 🐱‍👤 made with algeria 🖤 by DZ-TM071</h1>
