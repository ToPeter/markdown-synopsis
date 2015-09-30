---
title: "Sample document"
subtitle: "A sample document for learning Markdown"
author: "John Doe"
date: \today
version: 1.0
numbersections: true
toc: true
toc-depth: 2
lof: true
lot: false
---

This is a sample document which shows how to correctly format text in MarkDown language. When these guidelines are followed, the output document follows the standards of *Gratex International*. If these standards are not followed, there is **no** guarantee on the quality of the output document.

The best way to learn from this document is to open both the ``pdf`` file and ``md`` file in an editior of your choice (such as ReText) and see how the formatting of the output file is achieved in the source file.

For more detailed information about MarkDown language see [this page](http://johnmacfarlane.net/pandoc/README.html).

# Document metadata
Each new document that will become a PDF should contain metadata, which include document title, author or date. Metadata **must** be put on top of the document, with three dashes (-) above and below the text.

~~~
---
title: "<Insert title>"
author: "<Insert author(s)>"
date: "<Month Day, Year>"
numbersections: <Boolean>
toc: <Boolean>
toc-depth: <Integer>
lof: <Boolean>
---
~~~

Metadata contain following fields:

- **title**: This field is mandatory and will apear on title page. When this field is not filled out, the title page will not be generated.
- **author**: This field is optional and can include a name of one author, names of several authors or the name of a company.
- **date**: This field is optional and contains the date when the document was created. 
    - Example: ``date: "December 23, 2014"``
    - When lazy, you may also use this option to generate today's date: ``date: \today``
- **toc**: This field is optional and specifies whether a table of contents will be generated or not. It can be only ``true`` or ``false``.
    - Default: ``toc: true``
- **toc-depth**: This field is optional and contains a number that specifies the deepest level that will be shown in Table of Contents.
    - Example: ``toc-depth: 2`` specifies that only level one and level two headings will be shown in ToC.
    - Default: ``toc-depth: 3``
- **lof**: This field is optional and specifies whether a list of figures will be generated after ToC or not. It can be only ``true`` or ``false``. If table of contents is not generated, neither is the list of figures.
    - Default: ``lof: false``
- **lot**: This field is optional and specifies whether a list of tables will be generated after ToC or not. It can be only ``true`` or ``false``. If table of contents is not generated, neither is the list of tables.
    - Default: ``lot: false``

\pagebreak

\part{Sectioning}

A part is the highest level of splitting the document. Parts should be used for separating two pieces of content that are completely different from each other. For other purposes level-one headings should be used. 

A level-one heading
==================
This text is under a top-level heading, which creates sections. When the headings are numbered, a new section increases the first-left number in the series, as in **Section 2**. There are two ways to define a section heading, both can be found in the original **.md** document.

**Beware**: When a new part is specified, the numbering of level-one headings (sections) is not automatically increased. Thus, it is recommended to add a level-one heading right after a new part.

A level-two heading
------------------
This text is under a second-level heading, which creates sub-sections. Again, there are two ways to define a sub-section. A new sub-section increases the second-left number in series, as in **Section 1.2**.

### Level three heading
This text is under a third-level heading, which creates a sub-sub-section. There is only one way to define it. A new sub-sub-section increases the third-left number in the series, as in **Section 1.1.2**.

#### Level four heading
Level 4 is the first level that is not  numbered.

##### Level five heading
This is the last level of heading which is supported with this template and is also unnumbered.

## Second-level heading defined in a different way
*Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sollicitudin aliquet est. Etiam id eros libero.* Nullam lobortis eget ex vel aliquam. Duis eu augue eget ex sodales egestas vitae vel ipsum. Proin in mi quis erat iaculis accumsan. Vivamus a nunc libero. Morbi porta pharetra diam eget ullamcorper. Vestibulum eu luctus turpis. Pellentesque habitant.

Suspendisse luctus, justo quis egestas consectetur, turpis ante ultrices orci, eu porta nunc ipsum euismod odio. Morbi id condimentum nisi. Praesent cursus commodo enim cursus facilisis. Aenean aliquam, turpis vitae scelerisque tempus, urna velit auctor ipsum, quis maximus turpis massa a eros. In hac habitasse platea dictumst. Aliquam erat volutpat. Nunc tempor tortor purus, non dignissim risus dignissim vel. Curabitur eu blandit elit. Aliquam hendrerit massa eu metus suscipit euismod.

#### Another level Four heading
Lorem ipsum dolor sit amet, consectetur adipiscing elit. *Aenean* augue metus, lacinia id velit sit amet, ultrices hendrerit sem. Pellentesque ultricies dignissim consectetur. Curabitur iaculis vitae tellus non mattis. Suspendisse egestas pulvinar cursus. Nulla aliquam nisi in tincidunt blandit. Vestibulum luctus eros at rhoncus porta. Curabitur vehicula nibh sit amet imperdiet dapibus. Quisque sed nulla ac tortor feugiat cursus. *Pellentesque laoreet lacus nec libero mollis*, non viverra mauris tristique. Etiam.

### Another Level three heading
Vivamus luctus felis pretium enim semper, eget egestas dui mattis. Maecenas lorem lectus, vehicula non.

## Second-level heading that is veeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeery loooooong
Phasellus urna leo, imperdiet sit amet aliquet eu, porttitor eu mi. Donec tincidunt justo ac neque finibus, ut accumsan tortor laoreet. Nulla vel gravida justo, nec bibendum sapien. Morbi tincidunt mauris non neque egestas molestie. Donec nec dolor odio. Pellentesque tincidunt risus quis magna eleifend varius. Duis iaculis dolor ut felis elementum laoreet. Pellentesque at porttitor erat. Fusce euismod nisi in massa lacinia, dapibus tincidunt purus luctus. Suspendisse ac justo a nisl fringilla tristique in a dolor. Aenean aliquam rutrum arcu, sed vestibulum tellus imperdiet non.

# Section heading defined differently

\'\'Cras\'\' sed ultricies nisi. Etiam ornare, ipsum sed cursus **maximus**, sem ligula sagittis odio, quis porttitor sapien enim vel dolor. Phasellus turpis purus, finibus eu nulla eget, lobortis fermentum nisl. Mauris in orci ultricies, dignissim lorem nec, pulvinar lorem. Nulla ut rutrum felis. Vestibulum in nisi pulvinar, pulvinar leo et, placerat nisi. Nunc ornare turpis risus, at viverra eros laoreet at. Nunc non neque nec dui imperdiet aliquam.

> Proin tincidunt dolor dui, ac ornare massa gravida eget. Vivamus aliquam cursus purus, nec dapibus neque faucibus quis. Pellentesque ornare, metus a maximus vulputate, justo libero faucibus eros, a semper
> nisl nunc cursus est. Quisque non urna eu orci pretium vestibulum. Pellentesque ac accumsan eros. Maecenas ut lectus vel arcu hendrerit porttitor vitae nec ipsum. In hac habitasse platea dictumst.

Aenean in diam eget magna iaculis molestie. Vivamus aliquam ligula vitae turpis tristique efficitur. Fusce lobortis, enim vel viverra ultrices, nibh tellus dictum tellus, posuere eleifend ligula mi ut felis. Aliquam erat volutpat. Maecenas hendrerit, enim in imperdiet hendrerit, orci ante hendrerit diam, quis ornare neque enim id leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec blandit turpis neque, sed pulvinar purus rutrum sed. Etiam ornare erat ex, faucibus hendrerit mi cursus a. Nullam lacinia felis convallis posuere cursus. Praesent tempus laoreet ligula in suscipit. 

### Skipping one level causes numbering problems, but maybe you're ok with it

 Duis accumsan rhoncus turpis, id luctus dui euismod et. Curabitur odio justo, rutrum eget sapien sed, dictum porta turpis. Nam ac urna elit. Suspendisse ac ante sed diam vestibulum dapibus. Phasellus sagittis leo vitae ex ornare sagittis. In vitae accumsan nulla, placerat interdum felis. Suspendisse felis diam, mattis eu ornare viverra, dapibus a justo. In sit amet ornare velit. Donec finibus risus finibus tellus euismod, a accumsan nunc iaculis. Morbi mattis, enim sed auctor pretium, velit metus vehicula lectus, sit. 

\pagebreak      <!-- pagebreak is mandatory before a new part, unless we want the new part to stay on the same page as the text before it-->
\part{Formatting}
                <!-- no pagebreak after the part, this will be done automatically-->

*This is a text in italics,* followed by normal text. One can also use **bold text** and ``verbatim`` text. When you want to use ''quotation marks'' in text, you should \'\'escape\'\' them, otherwise they look ugly. 'Single quotes' are okay.

An empty line creates a new paragraph. An empty line is also used to separate special types of text, such as lists, blocks, headings or commands from regular text.

# Blocks of text

## Block quote

This section shows an example of a block quote that is separated from left margin by one tab and is not in verbatim.

> This is a block quote. This
> paragraph has two lines.

The following text is then not indented.

##### List inside a block quote

You can also put a list inside a block quote.

> Some text before the list
>
> 1. This is a list inside a block quote.
> 2. Second item.
>
> ...and some other text after the list

And the following text should be separated by an empty line.

## Block code
A block of code follows. This is done by indenting the text by 4 spaces (one tab):

    if (a > 3) {
      moveShip(5 * gravity, DOWN);
    }

or by using a long row of at least three tildes (``~~~``) before the block (recommended), as here:

~~~~~~~
if (a <= 3) {
   moveShip(5 * gravity, UP);
}
~~~~~~~

### Syntax highlighting
When including pieces of souce code into your document you can use syntax highlighting. To use this functionality, you need to insert the following:

~~~
```{.language}
your code
```
~~~

where ``language`` is the name of the programming language from the list below.

The following blocks of code are sorting algorithms implemented in Java and Haskell.

```{.java}
public void bubbleSort(int[] arr) {
      boolean swapped = true;
      int j = 0;
      int tmp;
      while (swapped) {
            swapped = false;
            j++;
            for (int i = 0; i < arr.length - j; i++) {                                       
                  if (arr[i] > arr[i + 1]) {                          
                        tmp = arr[i];
                        arr[i] = arr[i + 1];
                        arr[i + 1] = tmp;
                        swapped = true;
                  }
            }                
      }
}
```

```{.haskell}
quicksort :: (Ord a) => [a] -> [a]  
quicksort [] = []  
quicksort (x:xs) =   
    let smallerSorted = quicksort [a | a <- xs, a <= x]  
        biggerSorted = quicksort [a | a <- xs, a > x]  
    in  smallerSorted ++ [x] ++ biggerSorted  
```

Syntax highlighting is supported for the following languages:

actionscript, ada, apache, asn1, asp, awk, bash, bibtex, boo, c, changelog,
clojure, cmake, coffee, coldfusion, commonlisp, cpp, cs, css, curry, d,
diff, djangotemplate, doxygen, doxygenlua, dtd, eiffel, email, erlang,
fortran, fsharp, gnuassembler, go, haskell, haxe, html, ini, java, javadoc,
javascript, json, jsp, julia, latex, lex, literatecurry, literatehaskell,
lua, makefile, mandoc, markdown, matlab, maxima, metafont, mips, modelines,
modula2, modula3, monobasic, nasm, noweb, objectivec, objectivecpp, ocaml,
octave, pascal, perl, php, pike, postscript, prolog, python, r,
relaxngcompact, rhtml, roff, ruby, rust, scala, scheme, sci, sed, sgml, sql,
sqlmysql, sqlpostgresql, tcl, texinfo, verilog, vhdl, xml, xorg, xslt, xul,
yacc, yaml


## Line blocks

If you need to preserve the division into lines with any leading spaces, use line blocks:

| The Right Honorable Most Venerable and Righteous 
  Samuel L. Jackson
|            200 Main St.
|            Berkeley, CA 94718


# Lists
There are two main types of lists:

- numbered lists
- unnumbered lists

They may be combined in any order. A new list is separated from regular text by an empty line.

## Unnumbered lists

### Simple lists
An example of a compact list:

* First item
* Second item
* Third item
* Fourth item

The text needs to be separated from the list by an empty line.


## Numbered lists {#num-lists}

### Simple lists
In standard markdown, enumerators are decimal numbers followed by a period and a space.

1.  one
2.  two
3.  three

This is a numbered list starting from 5. Pandoc overwrites the numbers in lists and assigns them in ascending order, so there is no need to write the correct numbers (except for the first one which sets the starting number):

5.  one
9.  two
1.  three
7. four
11. five

This has a negative effect when the unordered numbers are *intended*. In such case, using a verbatim text or an unordered list is recommended:

~~~
5. five
7. seven
9. nine
3. three
~~~

#### \'\'Lazy\'\' lists
This is a numbered list when you are lazy to keep track of numbers. Pandoc takes care of numbering by itself.

#. one
#. two
#. three

### Complex lists
You can also specify numbering styles:

 9)  Ninth
10)  Tenth
11)  Eleventh
       i. subone
      ii. subtwo
     iii. subthree
        (b) subsubone
        (c) subsubtwo

## Nested lists
List items may include other lists. In this case the preceding blank line is optional. The nested list must be indented four spaces or one tab:

- Animalia
    + Chordata
        * Mammalia
            - Perissodactyla
                - Equidae
                    - Horse
                    - Zebra
            - Carnivora
                - Canidae
                    - dog
        * Reptilia

Numbered lists can also be nested, such as here:

#. First-level
    #. Second-level
        #. Third-level
            #. Fourth-level
                #. Fifth-level
                    #. Sixth-level


Please note that *at most* six levels of nesting are supported.

## Definition lists
Pandoc also supports definition lists. Each term must fit on one line, which may optionally be followed by a blank line, and must be followed by one or more definitions. A definition begins with a colon or tilde followed by three spaces.

Term 1
:   Nulla rutrum pretium justo at sodales. Vivamus id.

Term 2 with *inline markup*

:   Nam faucibus nec erat eu lacinia. Nulla eu lectus nullam sodales:

        { some code, part of Definition 2 }

    Fusce pellentesque tellus gravida libero pharetra tristique. Curabitur sagittis posuere.

Term 3

:   Donec blandit facilisis nisl id consequat. Duis vel vulputate erat.

 Etiam vehicula nec tortor in pharetra. Curabitur consectetur tincidunt risus. Nam sollicitudin magna id iaculis tincidunt. Nulla sed convallis eros, ac tempus eros. Quisque vitae facilisis ipsum, sagittis dapibus velit.


## List of examples

The special list marker @ can be used for sequentially numbered examples. The first list item with a @ marker will be numbered \'\'1\'\', the next \'\'2\'\', and so on, throughout the document. The numbered examples need not occur in a single list; each new list using @ will take up where the last stopped. So, for example:

(@)  My first example will be numbered (1).
(@)  My second example will be numbered (2).

Explanation of examples.

-------------------

(@)  My third example will be numbered (3).

Numbered examples can be labeled and referred to elsewhere in the document:

(@good_12-3)  This is a very good example.

As Example @good_12-3 illustrates, ...

The label can be any string of alphanumeric characters, underscores (``_``), or hyphens (``-``).

\pagebreak
\part{Tables}

# Tables

## Simple tables

Simple tables look like this:

  Right     Left     Center     Default
-------     ------ ----------   -------
     12     12        12            12
    123     123       123          123
      1     1          1             1

Table:  Demonstration of simple table syntax.

## Complex tables
### Multiline tables

Multiline tables allow headers and table rows to span multiple lines of text (but cells that span multiple columns or rows of the table are not supported). Here is an example:

-------------------------------------------------------------
 Centered   Default           Right Left
  Header    Aligned         Aligned Aligned
----------- ------- --------------- -------------------------
   First    row                12.0 Example of a row that
                                    spans multiple lines.

  Second    row                 5.0 Here's another one. Note
                                    the blank line between
                                    rows.
-------------------------------------------------------------

Table: Here's the caption. It, too, may span
multiple lines.

### Grid tables
Grid tables look like this:

: Sample grid table.

+---------------+---------------+--------------------+
| Fruit         | Price         | Advantages         |
+===============+===============+====================+
| Bananas       | $1.34         | - built-in wrapper |
|               |               | - bright color     |
+---------------+---------------+--------------------+
| Oranges       | $2.10         | - cures scurvy     |
|               |               | - tasty            |
+---------------+---------------+--------------------+


\pagebreak
\part{Figures}

# Figures {#figures}

The simplest way to include a picture in your text is to write:

~~~
![Image caption](path-to-your-figure/figure.jpg)
~~~

For example, when you want to include a picture of your cat:

![This is a cat](./img/cat.jpg)

When you want a reference to your picture, the syntax is a bit more complex.

Figure [2](#image) shows a dog.

[2]: img/dog.jpg 

![This is a dog][2]

\pagebreak

When you want to resize a picture, you need to use a different command[^1]:

[^1]: For more information about the syntax go [here](#insImg).

\imgCap{img/dog.jpg}{1.5}{This is a dog 1.5 times bigger}

## Inline figures

This is an inline figure \imgLine{img/delete_button.jpg} followed by text. To achive this, a special command is needed[^2].

[^2]: For more information about the syntax go [here](#inlImg).

\vfill

\pagebreak

\part{References}

# References

## Footnotes

Pandoc’s markdown allows footnotes, using the following syntax:

Here is a footnote reference,[^3] and another[^longnote].

[^3]: Here is the footnote.

[^longnote]: Here's one with multiple blocks.

    Subsequent paragraphs are indented to show that they
belong to the previous footnote.

        { some.code }

    The whole paragraph can be indented, or just the first
    line.  In this way, multi-paragraph footnotes work like
    multi-paragraph list items.

This paragraph won't be part of the note, because it
isn't indented.

## Inline notes
Inline footnotes are also allowed (though, unlike regular notes, they cannot contain multiple paragraphs). The syntax is as follows:

Here is an inline note.^[Inlines notes are easier to write, since
you don't have to pick an identifier and move down to type the
note.]

## Section references
If you want to refer to a specific section of your document you need to add a tag to the header and then refer to it. See the [Figures](#figures) section for an example.

\vfill

\pagebreak
\part{Additional commands}

This section lists all commands that are not a part of MarkDown, but may be useful in some situations.

#### New page
~~~
\pagebreak
\newpage
~~~
Any of these two commands will create a new page. For most purposes, these commands may be used interchangeably[^4].

[^4]: The difference between these two commands is explained [here](http://tex.stackexchange.com/a/9855).

#### Lanscape page
~~~
\landscapeBegin
{...}
\landscapeEnd
~~~
All text that is between starting and closing command will be put on new page with landscape orientation. This is sometimes needed for very wide tables or code excerpts.

#### Very small text
~~~
\vSmallBegin
{...}
\vSmallEnd
~~~

\vSmallBegin
All text that is between starting and closing command will be made very small. 
\vSmallEnd

This is sometimes needed in case a very wide table doesn't want to fit the page even in landscape page orientation.

#### Reszie figure {#insImg}
To include an image that has a different size from default you may use the following command instead of the Markdown command:

~~~
\img{path}{scale}
~~~

where ``<path>`` is path to your image file, ``<scale>`` is a decimal number representing how much will the image be resized (``scale = 1.0`` means the image will have default size).

##### Resize with caption
To include a caption ``<caption>`` above the figure use the following command:

~~~
\imgCap{path}{scale}{caption}
~~~

#### In-line figure {#inlImg}
To insert a figure in the middle of a line, use the following command:

~~~
\imgLine{path}
~~~

where ``<path>`` is a relative path to your image.

This command will insert a figure (for example, an icon) \imgLine{img/delete_button.jpg} in the middle of a line.


#### Math mode
To write mathematical expressions or equations just use ``$`` sign before **and** after the block of math, such as here:

$x+ 3 = 7$

$a \implies b$

$a_{i+1} = \sum\limits_{i=0}^{n} a_i^2$

$amount\_paid = \$200 + (\$.25 \times x)$

$\frac{x}{3} = \frac{1}{\frac{3}{x}}$

$\rightarrow \leftarrow$

$e^{\pi i} = -1$

500\euro

For more math symbols please consult [Wikipedia](http://en.wikibooks.org/wiki/LaTeX/Mathematics).

##### Equations
Should you require to write more complex equations, use the following commands:

~~~
\begin{displaymath}
...
\end{displaymath}
~~~

such as here:

\begin{displaymath}
\phi (x) = \frac{e^{-\frac{1}{2}x^2}}{\sqrt{2\pi}}
\end{displaymath}

\pagebreak
\part{Best practices}

The following are good practices that are important for correct formatting:

#. do not indent text. Indenting text by 1 tab (4 spaces) is a command in Pandoc Markdown, which starts a [Verbatim](http://en.wikibooks.org/wiki/LaTeX/Paragraph_Formatting#Special_paragraphs) environment in Latex. Use it only when you know what you're doing!
#. when in doubt whether you should use an empty line somewhere, use it.
#. you do not need to number the sections as they will be numbered automatically. Should you need to change the section numbering style (or remove the numbering altogether), follow the guidelines above.
#. When using nested numbered lists do not use hierarchical numbering, because it looks like this:

1) Some item.
    1.1) Some sub-item.
        1.1.1. Some sub-sub-item.
    1.2) Another sub-item.
    
or like this

1) Some item.

    1.1) Some sub-item.

        1.1.1. Some sub-sub-item.

    1.2) Another sub-item.

 It looks better when one line contains only one number, as in [Numbered lists](#num-lists) section.

1) Some item.
    1. Some sub-item.
        i. Some sub-sub-item.
    2. Another sub-item.


5. when creating tables, follow the sample document.
    - do not forget to include a space in the line of dashes (-), which specifies  a new column.
#. when including figures, **do not** use dots (.) in names. Use dashes (-) instead.
    - also, be careful with the uppercase letters - the filename in the MD file should be *exactly* the same as is the name of the file. That also applies to the file extension.
#. when a figure is not placed in the correct section use a ``\pagebreak`` after that figure. This should put the figure in the correct place. On the other hand, it will make a page break after the figure.
#. when in doubt, refer [here](http://johnmacfarlane.net/pandoc/README.html).

\pagebreak

\appendix

Contact
=======
Should you have ideas how to improve the template or should you have any problems with it, do not hesitate to contact me at

    jmichalco@gratex.com

