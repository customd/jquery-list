jQuery Floating/Fixed List Header Plugin
========================================

This is a [jQuery](http://jquery.com/) plugin which allows the user to create a list with 
floating headings while scrolling, a-la iOS & iCal day view. The plugin allows arbitrary 
markup of the header and list items, and will work nicely with nested elements. 

- View at the [jQuery Plugin Registry](http://plugins.jquery.com/df-list/).

Demos
-----

The Demos for this plugin live under the examples/ directory. Open them directly in your web browser, or view the following online examples:

- [Basic Demo](http://www.teamdf.com/jquery-plugins/list/examples/demo-basic.html)
- [Australian States & Cities Demo](http://www.teamdf.com/jquery-plugins/list/examples/demo-australia.html)
- [ScrollTo Demo](http://www.teamdf.com/jquery-plugins/list/examples/demo-scrollto.html)
- [headerChange Demo](http://www.teamdf.com/jquery-plugins/list/examples/demo-headerchange.html)

The following are Demos not included in the examples/ directory and can only be viewed online:

- [Showcasing jQuery List with a fake iPhone](http://www.teamdf.com/web/showcasing-jquery-list-with-a-fake-iphone/147/)

Documentation
-------------
### Basic list setup

The basic setup will work with any standard dl element with no extra config options.

	$('dl').list();

If you want to use the plugin with any other HTML structure, you can use the 'headerSelector' setting
to tell the plugin what elements to use as headers.

	$('ul').list({ headerSelector : 'li.header' });

Other capabilities include methods which will scroll the list to any heading, with optional animation,
and a method which will report the current heading that the user sees. You can also bind to an event
which will fire whenever the currently viewed heading changes.

	$('dl').list().bind( 'headingChange', myFunction );

### Full plugin documentation

The Documentation for this plugin lives under the docs/ directory. Open it directly 
in your web browser, or see the [online documentation](http://teamdf.com/jquery-plugins/list/).