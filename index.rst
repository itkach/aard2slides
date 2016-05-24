============================
Aard 2 - http://aarddict.org
============================

.. image:: aard2.svg
   :align: center
   :scale: 50%

What is it?
-----------
.. class:: incremental

   - Word lookup app (a.k.a. dictionary)

     .. image:: sm-lookup.png


What is it?
-----------

- Wikipedia reader/browser

  .. image:: sm-article-pythagorean-theorem.png


Why?
----

.. class:: incremental

   - Quickly look up words from e-book readers and other apps

   - We are still offline a lot

   - A way to learn/explore

     * Python
     * Cross-platform UI with GTK and Qt
     * Android
     * Working with binary data (struct)
     * Unicode/UCA
     * ?

   - Because I can

How?
----

.. class:: incremental

   - Custom binary format

   - Sorted list of keys

   - Unicode Collation

   - Compression


Features
--------

.. class:: incremental

   - Case, diacritics, punctuation insensitive lookups

   - Bookmarks and history

   - Dictionary management (find on device, add manually,
     enable/disable, favorites)

   - Light and dark UI theme

   - Alternate appearance (most dicts come with light/dark theme -
     matchin UI), user CSS

   - High quality math rendering (with MathJax)

   - Explore Wikipedia with random article lookups



Challenges
----------

.. class:: incremental

   - Unicode Collation definition continues to be tweaked in new
     standard versions

   - Loading alternative styles without flashing

   - Getting redistributable, quality content

   - Getting Wikipedia content

     * large

     * very difficult to parse

   - Language aware lookups (finding words specified in any of its
     word forms, such as plurals, past tense, passive voice etc.)


Wish List
---------

.. class:: incremental

   - Offline images

   - Audio

   - Spatial (geo) lookups

   - Better long content scrolling


Resources
---------

- Forum

  http://aarddict.org/forum/

- Dictionaries

  https://github.com/itkach/slob/wiki/Dictionaries

- Source Code

  https://github.com/itkach/aard2-android
