GitHub Flavored Markdown
================================

[TOC]

Line Breaks
-----------

Let's get the whole "linebreak" thing out of the way. The next paragraph contains two phrases separated by a single newline character:

Roses are red
Violets are blue

The next paragraph has the same phrases, but now they are separated by two spaces and a newline character:

Roses are red  
Violets are blue

Oh, and one thing I cannot stand is the mangling of words with multiple underscores in them like perform_complicated_task or do_this_and_do_that_and_another_thing.

Text Formatting
---------------

Text can be formatted in a vareity of ways including:

* Bold
* Italics
* Sizing

---

`**This is Bold**` or `__This is Bold__`

e.g.

**This is Bold** or __This is Bold__

---

`*This is in Italics*` or `_This is in Italics_`

e.g.

*This is in Italics* or _This in in Italics_

---

```
# = H1
## = H2
### = H3
#### = H4
##### = H5
###### = H6

H1 - Can be any length, minimum of three
=======

H2 - Can be any length, minimum of three
-------
```

Where H1 is the largest text size and the smallest is H6.

Links
-----

Links can be defined by doing:

`[Text](link)`
`[Source](Formatting_Tutorial.txt)`

e.g. [Homepage](Formatting_Tutorial.txt)

The link can either point to the wiki itself or external links, in our case above we are staying within the wiki. So the link is relative to our current directory, since
"Formatting_Tutorial.txt" is stored in the same Directory you can just use the file name.

For external links just use the entire link within the brackets e.g.

`[Github](https://github.com/Snappey/Zecon-Wiki)`

You can also apply text formatting to links by using the above around the content

`*[Text](link)*`

Will italicise the link


Math is hard, let's go shopping
-------------------------------

In first grade I learned that 5 > 3 and 2 < 7. Maybe some arrows. 1 -> 2 -> 3. 9 <- 8 <- 7.

Triangles man! a^2 + b^2 = c^2

We all like making lists
------------------------

The above header should be an H2 tag. Now, for a list of fruits:

* Red Apples
* Purple Grapes
* Green Kiwifruits

Some people seem to like definition lists

<dl>
  <dt>Lower cost</dt>
  <dd>The new version of this product costs significantly less than the previous one!</dd>
  <dt>Easier to use</dt>
  <dd>We've changed the product so that it's much easier to use!</dd>
</dl>

I am a robot
------------

Maybe you want to print `robot` to the console 1000 times. Why not?

    for i=1, 1000 do
      print("robot ")
    end

You see, that was formatted as code because it's been indented by four spaces.

How about we throw some angle braces and ampersands in there?

    <div class="footer">
        &copy; 2004 Foo Corporation
    </div>

Set in stone
------------

Preformatted blocks are useful for ASCII art:

<pre>
             ,-. 
    ,     ,-.   ,-. 
   / \   (   )-(   ) 
   \ |  ,.>-(   )-< 
    \|,' (   )-(   ) 
     Y ___`-'   `-' 
     |/__/   `-' 
     | 
     | 
     |    -hrr- 
  ___|_____________ 
</pre>

Playing the blame game
----------------------

If you need to blame someone, the best way to do so is by quoting them:

> I, at any rate, am convinced that He does not throw dice.

Or perhaps someone a little less eloquent:

> I wish you'd have given me this written question ahead of time so I
> could plan for it... I'm sure something will pop into my head here in
> the midst of this press conference, with all the pressure of trying to
> come up with answer, but it hadn't yet...
>
> I don't want to sound like
> I have made no mistakes. I'm confident I have. I just haven't - you
> just put me under the spot here, and maybe I'm not as quick on my feet
> as I should be in coming up with one.

Table for two
-------------

<table>
  <tr>
    <th>ID</th><th>Name</th><th>Rank</th>
  </tr>
  <tr>
    <td>1</td><td>Tom Preston-Werner</td><td>Awesome</td>
  </tr>
  <tr>
    <td>2</td><td>Albert Einstein</td><td>Nearly as awesome</td>
  </tr>
</table>

Crazy linking action
--------------------

I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].

  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"

Link to Source
--------------

*[Link to Source](Formatting_Tutorial.txt)*