# AsciiDoc Snippets for UltiSnips

The **asciidoc.snippets** file provides a complete set of snippets for AsciiDoc. These snippets are inspired by those included in the [AsciiDoc Autocomplete](https://github.com/asciidoctor/atom-autocomplete-asciidoc) package for Atom and where possible, they follow the conventions defined in [Red Hat Documentation Asciidoc Mark-up Conventions](https://github.com/redhat-documentation/asciidoc-markup-conventions) and [Red Hat Modular Documentation Project](https://github.com/redhat-documentation/modular-docs).

## Titles and Sections

<table>
  <tr>
    <th>Trigger</th>
    <th>Description</th>
    <th>Expands to</th>
  </tr>
  <tr>
    <td><strong>=</strong></td>
    <td>Document Title (Level 0)</td>
    <td><pre>= …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=0</strong></td>
    <td>Document Title (Level 0)</td>
    <td><pre>= …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=1</strong></td>
    <td>Document Part (Level 0)</td>
    <td><pre>= …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=[</strong></td>
    <td>Document Title (Level 0) with Custom ID</td>
    <td><pre>[id="…"]
= …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=0[</strong></td>
    <td>Document Title (Level 0) with Custom ID</td>
    <td><pre>[id="…"]
= …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=1[</strong></td>
    <td>Document Part (Level 0) with Custom ID</td>
    <td><pre>[id="…"]
= …

…</pre></td>
  </tr>
  <tr>
    <td><strong>==</strong></td>
    <td>Level 1 Section Title</td>
    <td><pre>== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=2</strong></td>
    <td>Level 1 Section Title</td>
    <td><pre>== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>==[</strong></td>
    <td>Level 1 Section Title with Custom ID</td>
    <td><pre>[id="…"]
== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=2[</strong></td>
    <td>Level 1 Section Title with Custom ID</td>
    <td><pre>[id="…"]
== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>===</strong></td>
    <td>Level 2 Section Title</td>
    <td><pre>=== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=3</strong></td>
    <td>Level 2 Section Title</td>
    <td><pre>=== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>===[</strong></td>
    <td>Level 2 Section Title with Custom ID</td>
    <td><pre>[id="…"]
=== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=3[</strong></td>
    <td>Level 2 Section Title with Custom ID</td>
    <td><pre>[id="…"]
=== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>====</strong></td>
    <td>Level 3 Section Title</td>
    <td><pre>==== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=4</strong></td>
    <td>Level 3 Section Title</td>
    <td><pre>==== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>====[</strong></td>
    <td>Level 3 Section Title with Custom ID</td>
    <td><pre>[id="…"]
==== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=4[</strong></td>
    <td>Level 3 Section Title with Custom ID</td>
    <td><pre>[id="…"]
==== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=====</strong></td>
    <td>Level 4 Section Title</td>
    <td><pre>===== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=5</strong></td>
    <td>Level 4 Section Title</td>
    <td><pre>===== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=====[</strong></td>
    <td>Level 4 Section Title with Custom ID</td>
    <td><pre>[id="…"]
===== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=5[</strong></td>
    <td>Level 4 Section Title with Custom ID</td>
    <td><pre>[id="…"]
===== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>======</strong></td>
    <td>Level 5 Section Title</td>
    <td><pre>====== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=6</strong></td>
    <td>Level 5 Section Title</td>
    <td><pre>====== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>======[</strong></td>
    <td>Level 5 Section Title with Custom ID</td>
    <td><pre>[id="…"]
====== …

…</pre></td>
  </tr>
  <tr>
    <td><strong>=6[</strong></td>
    <td>Level 5 Section Title with Custom ID</td>
    <td><pre>[id="…"]
====== …

…</pre></td>
  </tr>
</table>

## Block Elements

<table>
  <tr>
    <th>Trigger</th>
    <th>Description</th>
    <th>Expands to</th>
  </tr>
  <tr>
    <td><strong>////</strong></td>
    <td>Comment Block</td>
    <td><pre>////
…
////
…</pre></td>
  </tr>
  <tr>
    <td><strong>….</strong></td>
    <td>Literal Block</td>
    <td><pre>....
…
....
…</pre></td>
  </tr>
  <tr>
    <td><strong>----</strong></td>
    <td>Listing Block</td>
    <td><pre>----
…
----
…</pre></td>
  </tr>
  <tr>
    <td><strong>--</strong></td>
    <td>Open Block</td>
    <td><pre>--
…
--
…</pre></td>
  </tr>
  <tr>
    <td><strong>++++</strong></td>
    <td>Passthrough Block</td>
    <td><pre>++++
…
++++
…</pre></td>
  </tr>
  <tr>
    <td><strong>____</strong></td>
    <td>Quote Block</td>
    <td><pre>____
…
____
…</pre></td>
  </tr>
  <tr>
    <td><strong>****</strong></td>
    <td>Sidebar Block</td>
    <td><pre>****
…
****
…</pre></td>
  </tr>
  <tr>
    <td><strong>literal</strong></td>
    <td>Literal Block with Quotes Substitutions</td>
    <td><pre>[literal,subs="…"]
----
…
----
…</pre></td>
  </tr>
  <tr>
    <td><strong>source</strong></td>
    <td>Source Code Block</td>
    <td><pre>[source,…]
----
…
----
…</pre></td>
  </tr>
  <tr>
    <td><strong>caution</strong></td>
    <td>Admonition: Caution</td>
    <td><pre>[CAUTION]
====
…
====
…</pre></td>
  </tr>
  <tr>
    <td><strong>important</strong></td>
    <td>Admonition: Important</td>
    <td><pre>[IMPORTANT]
====
…
====
…</pre></td>
  </tr>
  <tr>
    <td><strong>note</strong></td>
    <td>Admonition: Note</td>
    <td><pre>[NOTE]
====
…
====
…</pre></td>
  </tr>
  <tr>
    <td><strong>tip</strong></td>
    <td>Admonition: Tip</td>
    <td><pre>[TIP]
====
…
====
…</pre></td>
  </tr>
  <tr>
    <td><strong>warning</strong></td>
    <td>Admonition: Warning</td>
    <td><pre>[WARNING]
====
…
====
…</pre></td>
  </tr>
</table>

## User Interface Macros

<table>
  <tr>
    <th>Trigger</th>
    <th>Description</th>
    <th>Expands to</th>
  </tr>
  <tr>
    <td><strong>btn</strong></td>
    <td>Button</td>
    <td><pre>btn:[…]…</pre></td>
  </tr>
  <tr>
    <td><strong>kbd</strong></td>
    <td>Keyboard Shortcut</td>
    <td><pre>kbd:[…]…</pre></td>
  </tr>
  <tr>
    <td><strong>menu</strong></td>
    <td>Menu Selection</td>
    <td><pre>menu:…[…]…</pre></td>
  </tr>
</table>

## Links and Images

<table>
  <tr>
    <th>Trigger</th>
    <th>Description</th>
    <th>Expands to</th>
  </tr>
  <tr>
    <td><strong>link</strong></td>
    <td>Link</td>
    <td><pre>link:…[…]…</pre></td>
  </tr>
  <tr>
    <td><strong>mailto</strong></td>
    <td>Email</td>
    <td><pre>mailto:…[…]…</pre></td>
  </tr>
  <tr>
    <td><strong>image</strong></td>
    <td>Block Image</td>
    <td><pre>image::…[…]…</pre></td>
  </tr>
  <tr>
    <td><strong>video</strong></td>
    <td>Video</td>
    <td><pre>video::…[…]…</pre></td>
  </tr>
</table>

## Text Formatting

<table>
  <tr>
    <th>Trigger</th>
    <th>Description</th>
    <th>Expands to</th>
  </tr>
  <tr>
    <td><strong>*</strong></td>
    <td>Bold Text</td>
    <td><pre>*…*…</pre></td>
  </tr>
  <tr>
    <td><strong>**</strong></td>
    <td>Bold Text (Unconstrained)</td>
    <td><pre>**…**…</pre></td>
  </tr>
  <tr>
    <td><strong>_</strong></td>
    <td>Italic Text</td>
    <td><pre>_…_…</pre></td>
  </tr>
  <tr>
    <td><strong>__</strong></td>
    <td>Italic Text (Unconstrained)</td>
    <td><pre>__…__…</pre></td>
  </tr>
  <tr>
    <td><strong>`</strong></td>
    <td>Monospace Text</td>
    <td><pre>`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>``</strong></td>
    <td>Monospace Text (Unconstrained)</td>
    <td><pre>``…``…</pre></td>
  </tr>
  <tr>
    <td><strong>^</strong></td>
    <td>Superscript Text</td>
    <td><pre>^…^…</pre></td>
  </tr>
  <tr>
    <td><strong>~</strong></td>
    <td>Superscript Text</td>
    <td><pre>~…~…</pre></td>
  </tr>
  <tr>
    <td><strong>'`</strong></td>
    <td>Single Curved Quotes</td>
    <td><pre>'`…`'…</pre></td>
  </tr>
  <tr>
    <td><strong>"`</strong></td>
    <td>Double Curved Quotes</td>
    <td><pre>"`…`"…</pre></td>
  </tr>
</table>

## Sematic Markup

<table>
  <tr>
    <th>Trigger</th>
    <th>Description</th>
    <th>Expands to</th>
  </tr>
  <tr>
  <tr>
    <td><strong>application</strong></td>
    <td>Application Name</td>
    <td><pre>[application]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>app</strong></td>
    <td>Application Name</td>
    <td><pre>[application]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>citetitle</strong></td>
    <td>Cited Work Title</td>
    <td><pre>[citetitle]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>cite</strong></td>
    <td>Cited Work Title</td>
    <td><pre>[citetitle]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>command</strong></td>
    <td>Command</td>
    <td><pre>[command]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>cmd</strong></td>
    <td>Command</td>
    <td><pre>[command]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>directory</strong></td>
    <td>Directory Name</td>
    <td><pre>[filename]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>dir</strong></td>
    <td>Directory Name</td>
    <td><pre>[filename]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>filename</strong></td>
    <td>File Name</td>
    <td><pre>[filename]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>file</strong></td>
    <td>File Name</td>
    <td><pre>[filename]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>function</strong></td>
    <td>Function Name</td>
    <td><pre>[function]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>func</strong></td>
    <td>Function Name</td>
    <td><pre>[function]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>gui</strong></td>
    <td>GUI Element Name</td>
    <td><pre>[gui]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>option</strong></td>
    <td>Option Name</td>
    <td><pre>[option]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>opt</strong></td>
    <td>Option Name</td>
    <td><pre>[option]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>package</strong></td>
    <td>Package Name</td>
    <td><pre>[package]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>pkg</strong></td>
    <td>Package Name</td>
    <td><pre>[package]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>parameter</strong></td>
    <td>Parameter Name</td>
    <td><pre>[parameter]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>param</strong></td>
    <td>Parameter Name</td>
    <td><pre>[parameter]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>systemitem</strong></td>
    <td>System Item</td>
    <td><pre>[systemitem]`…`…</pre></td>
  </tr>
  <tr>
    <td><strong>sys</strong></td>
    <td>System Item</td>
    <td><pre>[systemitem]`…`…</pre></td>
  </tr>
</table>
