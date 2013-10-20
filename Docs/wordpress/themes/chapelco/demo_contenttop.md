---
title: Chapelco: Recreating the Demo - Content Top
description: Your Guide to Recreating Elements of the Chapelco Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/chapelco:Chapelco

---

Content Top Section
-----
![][contenttop]

#### RokSprocket
You'll need to do two things to prepare this widget so that it looks similar to the one in the demo.

First, you'll need to create the RokSprocket Widget. You can do this by navigating to **Administration -> RokSprocket Admin** and creating a new **Mosaic** widget. 

You can find out more about RokSprocket and how to set up and modify widgets by visiting our [RokSprocket documentation][roksprocket].

Here is a look at the **Mosaic Layout Options** for this widget.

| Option          | Setting                      |  
| :-------------- | :--------------------------- |  
| Theme           | Default                      |  
| Display Limit   | ∞                            |  
| Columns         | 3                            |  
| Preview Length  | 16                           |  
| Strip HTML Tags | Yes                          |  
| Blocks Per View | 3                            |  
| Article Details | Hide Author and Date         |  
| Block Animation | Fade, Scale, Rotate          |  
| Ordering        | Default, Title, Date, Random |  
| Image Resize    | Disable                      |  

You can set the RokSprocket filters to include any category, specific articles, or otherwise you'd like to have featured in this widget.

Once you've created this widget, you can add it via the Widgets menu by clicking **RokSprocket** and dragging it to the appropriate section. When you've done this, you'll need to complete the following.

* Select your RokSprocket Featured widget in the **Choose Widget** field.
* Set the **Custom Variations** option to `nomarginbottom nopaddingbottom`.
* Leaving everything else at its default setting, select **Save**.

The widget should now be created and ready for use on the front page of your WordPress site.

[contenttop]: assets/demo_contenttop.jpeg
[roksprocket]: ../../plugins/roksprocket