> <h3>
<blockquote>2. Concepts<br>
</blockquote><blockquote></h3>
<h4>
<blockquote>2.1. Overview<br>
</blockquote></h4>
<p>
<blockquote>As described in the class diagram below, a complete XY Graph is composed of Legend,<br>
Title, Axes, PlotArea. The PlotArea will include Traces, Grids and Annotations.<br>
An XYGraph can also be wrapped into a ToolbarArmedXYGraph, which provides a toolbar<br>
for the interactive operations functionality.<br>
</blockquote><blockquote></p>
</blockquote><p>
<blockquote><img src='http://lh6.ggpht.com/_Dwn6OpYbddo/S4ikGnoTYoI/AAAAAAAAACA/UKp81n0_o6g/XYGraphUML.png' alt='XYGraph Class Diagram' border='1' />
</blockquote></p>
<p>
<blockquote>There are two interfaces <pre><code>IDataProvider</code></pre> and <pre><code>ISample</code></pre> in the class diagram,<br>
which means the user can also implemented there own data provider or sample.<br>
This gives the possibilities to implement a different data provider<br>
with different data source or data storage structure for special applications. For example, the data source in the data provider could be from user input, database or files etc,.<br>
The storage structure could be array, queue, circular buffer or bucket buffer etc,.<br>
<blockquote>A default data provider <pre><code>CircularBufferDataProvider</code></pre> and sample <pre><code>Sample</code></pre>
have been provided with the XYGraph plugin.<br>
</blockquote></blockquote></p>