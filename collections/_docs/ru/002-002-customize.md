---
title: "Customize Ink/Stitch"
permalink: /ru/docs/customize/
excerpt: ""
last_modified_at: 2019-03-15
toc: true
---

## Shortcut Keys

You can speed up your work with Ink/Stitch, if you assign shortcut keys.

Go to: `Edit > Preferences > Interface > Keyboard Shortcuts` and enter your desired key combinations. [More information](http://wiki.inkscape.org/wiki/index.php/Customizing_Inkscape)

The following list was suggested by lexelby:

Shortcut&nbsp;Keys | Effect
-------- | --------
<key>ctrl</key>+<key>shift</key>+<key>O</key> | Objects panel (Object menu -> Objects)
<key>ctrl</key>+<key>shift</key>+<key>P</key> | Params extension, without inkscape's extension preferences dialog
<key>ctrl</key>+<key>shift</key>+<key>L</key> | Simulate (mnemonic: Live simulation)
<key>ctrl</key>+<key>shift</key>+<key>E</key> | Embroider extension, without inkscape's extension preferences dialog
<key>PageUp</key>                             | "Stack Up" (Inkscape version >= 0.92.2)*
<key>PageDown</key>                           | "Stack Down" (Inkscape version >= 0.92.2)*
<key>ctrl</key>+<key>R</key>                  | Reverse the direction of a path.** 

*A new feature in Inkscape 0.92.2 that allows you to move an object up or down in the stacking order, even if they don't overlap. Stack Up and Stack Down give precise control over the order that objects are stitch in. Very useful in combination with the Objects panel (`Objects > Objects ...`). The stacking order defines, in which order elements are stitched out (from bottom to top).
{: style="font-size: 70%" }

**For satins and running stitch, this changes the direction the stitches go in. Use this with the Inkscape preference in the Node tool settings, `Show path direction on outlines`. If you select just one vertex using the node editor and press `Ctrl+R`, Inkscape will reverse just one path in an object. This way you can make sure that both rails in a satin point the same direction.
{: style="font-size: 70%" }

### Simulation Shortcut Keys

Ink/Stitch [simulation](/docs/simulate) already comes with shortcut keys included.

## Grids

To align your vector-shapes properly, you might want to make use of the grid functionality of Inkscape. Go to `View` and enable `Page Grid`. In `Snap Controls Bar` make sure `Snap to grids` is enabled. It is also possible to adjust spacing and origin of your grids in `File >  Document Properties > Grids`.

![Grids](https://user-images.githubusercontent.com/11083514/40359052-414d3554-5db9-11e8-8b49-3be75c5e9732.png)

## Enabling Path Outlines & Direction

Knowing path directions is important working with Ink/Stitch. Therefore we recommend to enable the checkboxes **Show path direction on outlines** and **Show temporary outline for selected paths** in `Edit > Preferences > Tools > Node`.

Make sure that also **Show path outline** is enabled in `Tool Controls Bar` as you can see in the image below.

[![Path outlines & directions](https://user-images.githubusercontent.com/11083514/40360721-f294ef0a-5dbe-11e8-9d4d-98f469ff1fba.png)](https://user-images.githubusercontent.com/11083514/40360721-f294ef0a-5dbe-11e8-9d4d-98f469ff1fba.png)

## Working with Templates

If you decided to use Ink/Stitch more frequently for your embroidery work, you might get tired of setting up the whole scene over and over again. In this case you are ready to create a template for your basic embroidery setup. Once you organised everything as desired, simply save your file in your templates folder. You can now access it by `File > New from template`.

Operating system|Template Folder
---|---
Linux|`~/.config/inkscape/templates`
Windows|`C:\Users\%USERNAME%\AppData\Roaming\inkscape\templates`

You should confirm the user folder in your inkscape preferences see the [FAQ](/docs/faq/#i-have-downloaded-and-unzipped-the-latest-release-where-do-i-put-it).

**Tip:** Get [predefined templates](/tutorials/resources/templates/) from our tutorial section.
{: .notice--info }

