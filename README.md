tokyo-metro
==========

Copyright (C) 2011-2015 Jerry Chen <mailto:onlyuser@gmail.com>

About
-----

tokyo-metro is a graphviz dot specification for the Tokyo Metro.
東京地鐵系統graphviz dot地圖.

A Motivating Example
--------------------

Radial:

[![picture alt](https://sites.google.com/site/onlyuser/files/tokyo-metro_thumb.png "tokyo-metro")](https://sites.google.com/site/onlyuser/files/tokyo-metro.png)

Tree layout:

[![picture alt](https://sites.google.com/site/onlyuser/files/tokyo-metro_tree_layout_thumb.png "tokyo-metro")](https://sites.google.com/site/onlyuser/files/tokyo-metro_tree_layout.png)

Requirements
------------

* graphviz dot

Installation (Debian)
---------------------

1. git clone https://github.com/onlyuser/tokyo-metro.git
2. sudo aptitude install graphviz

Usage
-----

<pre>
neato tokyo-metro.dot -Tpng -otokyo-metro.png
</pre>

References
----------

<dl>
    <dt>"Tokyo Metro"</dt>
    <dd>https://en.wikipedia.org/wiki/Tokyo_Metro</dd>
</dl>

Keywords
--------

    HongKong MTR, dot, graphviz, graph search, 東京地鐵, 地鐵系統, 地鐵站, 地圖