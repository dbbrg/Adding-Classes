Adding-Classes
==============

<h3>Adding classes to the first and the last child of an unordered list.</h3>

<pre><code>$('ul').children('li').first().addClass('first');</code></pre>

Select the first list-element element of an unordered list and add <code>class="first"</code>

<pre><code>$('ul').children('li').last().addClass('last');</code></pre>

Select the last list-element of an unordered list and add <code>class="last"</code>



