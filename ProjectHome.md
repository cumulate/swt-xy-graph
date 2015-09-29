**Note:** SWT XYGraph has been moved to [Eclipse Nebula Visualization](http://www.eclipse.org/nebula/widgets/visualization/visualization.php).
This site is not updated anymore.

10/15/2013


---


**SWT XYGraph** is a light weight scientific and engineering widgets library for SWT or Draw2D applications. It has widgets especially for science, engineering and SCADA applications, such as XY Graph, intensity graph, meter, gauge and knob. All the widgets are implemented on Draw2D, so it can be used in both SWT and GEF applications. These widgets are originally from [CSS BOY](http://sourceforge.net/apps/trac/cs-studio/wiki/BOY) project.

## [Getting Started](http://swt-xy-graph.googlecode.com/git/PureJava/org.csstudio.swt.xygraph/html/GettingStarted.html) ##

<a href='http://www.youtube.com/watch?feature=player_embedded&v=rWKcNSJq3cA' target='_blank'><img src='http://img.youtube.com/vi/rWKcNSJq3cA/0.jpg' width='425' height=344 /></a>

SWT XYGraph has the ability to plot real time data in fast speed. It also has an optional toolbar allows interactive operation such as zoom in/out, panning, add/delete annotation, configure properties, undo/redo and so on. Watch the demo below:

<a href='http://www.youtube.com/watch?feature=player_embedded&v=nDplIG7BW0M' target='_blank'><img src='http://img.youtube.com/vi/nDplIG7BW0M/0.jpg' width='425' height=344 /></a>

## News ##
  * 2012-07-15 Version 2.0.1 was released. A plugin example were added to show how to use it in an Eclipse plugin.
  * 2012-07-08 Version 2.0.0 is released. More widgets are added, such as gauge, knob, meter and so on.

## Screenshots ##
<a href='https://swt-xy-graph.googlecode.com/git-history/master/PureJava/org.csstudio.swt.xygraph/html/Screenshots.html'><img src='https://swt-xy-graph.googlecode.com/git/PureJava/org.csstudio.swt.xygraph/html/img/XYGraph.png' alt='XY Graph' height='250' /></a><a href='https://swt-xy-graph.googlecode.com/git-history/master/PureJava/org.csstudio.swt.xygraph/html/Screenshots.html'><img src='https://swt-xy-graph.googlecode.com/git/PureJava/org.csstudio.swt.xygraph/html/img/Widgets.jpg' alt='Widgets' /></a>

## [More screenshots](https://swt-xy-graph.googlecode.com/git-history/master/PureJava/org.csstudio.swt.xygraph/html/Screenshots.html) ##

### Functions of XY Graph ###
  * line chart, scatter chart, bar chart, step chart, area chart...
  * Five Zoom Types: Zoom in/out, Rubberband Zoom, Horizontal Zoom in/out, Vertical Zoom in/out
  * Panning on both graph area and axes
  * Auto Scale
  * Annotation support. Annotations could be either free or snapped to a trace
  * Undo/Redo support for all operations
  * Take snapshot
  * All properties can be interactively configured, such as trace color, line width and axis color etc,.
  * Multiple axes support
  * Log scale, date time format support
  * Grouping legends by axes
  * It is possible to implement your customized data provider based on a simple interface.
  * And more ...


### High lighted features ###
  * Based on SWT/Draw2D
> SWT XYGraph is based on SWT and Draw2D, if you implement Eclipse plug-ins, SWT-based stand alone applications or GEF based projects, SWT XYGraph would be the best candidate for your plot or chart functionality requirements.
  * Comprehensive functions and Easy to use
> The APIs of adding/setting a trace or axis are quite straightforwardly. Each part of the XYGraph(Trace, Axis, Grid, Annotation...) is a draw2d figure. You can easily hook listeners to any part or the whole XYGraph. Besides, you can easily zoom, panning, take snapshot, add/remove annotation, configure all the graph components settings from the toolbar. Finally, all the operations are undo/redo-able.
  * Light Weight and High Performance.
> Even with powerful functionality, the source code of SWT XYGraph is no more than 300KB. It doesn't have any dependencies other than SWT and Draw2D. For Eclipse user, the only additional required plug-in is Draw2D, which can be easily downloaded from Eclipse official website. There are also several design and algorithm optimization inside the code, which bring us the high performance when drawing large amount of data.

[![](http://www.eclipsecon.org/2010/static/image/130x100_speaking.gif)](http://www.eclipsecon.org/2010/sessions/sessions?id=1626)

### Projects using SWT XYGraph ###
  * [Best OPI Yet(BOY)](http://sourceforge.net/apps/trac/cs-studio/wiki/BOY) BOY is an control system operator interface (OPI) development and runtime environment.

  * [Data Browser](https://sourceforge.net/apps/trac/cs-studio/wiki/DataBrowser)

  * [DAWN Science](http://www.dawnsci.org/)

&lt;wiki:gadget url="http://www.ohloh.net/accounts/195086/widgets/account\_detailed.xml" height="55" border="0"/&gt;