---
title: Voxel: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Voxel Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/voxel:Voxel

---

Theme Override Settings
-----
One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Voxel Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs. 

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style
| Override |                 Option |                                           Setting |  
| :------- | ---------------------: | ------------------------------------------------: |  
| Default  |                   Logo |                                             Voxel |  
| Default  |        Load Transition |                                                On |  
| Default  |             Pagination |                        Style: Full, Side Pages: 8 |  
| Default  |         Thumbnail Size |          Width: 267, Height: 160, Position: Right |  
| Default  |               WebFonts | Show: Off, WebFonts Source: Google Font Directory |  
| Default  |          Font Settings |            Font Family: Voxel, Font Size: Default |  
| Default  | Use WordPress Comments |                                                On |  
| Default  |             Custom CSS |                                             Blank |  

### Gizmos
| Override   |                Option |                                       Setting |  
| :--------- | --------------------: | --------------------------------------------: |  
| Default    |           Page Suffix |                    Enabled: Off, Class: Blank |  
| Default    |            Feed Links |                                            On |  
| Default    |           Load Images | Show: On, Offset Y: 200, XPath Ignores: Blank |  
| Default    |      Custom Title Tag |                                         Blank |  
| Default    | Typography Shortcodes |                                            On |  
| Default    | Shortcodes in Widgets |                                            On |  
| Default    |              RokStyle |                                            On |  
| Default    |      Google Analytics |                  Enabled: Off, UA Code: Blank |  
| Front Page |           Page Suffix |               Enabled: On, Class: `menu-home` |  

### Layouts
| Override |               Option |               Setting |  
| :------- | -------------------: | --------------------: |  
| Default  |        Top Positions | Positions: 4, 3:3:3:3 |  
| Default  | Navigation Positions |     Positions: 2, 9:3 |  
| Default  |     Header Positions |     Positions: 2, 6:6 |  
| Default  |   Showcase Positions | Positions: 4, 3:3:3:3 |  
| Default  |    Feature Positions | Positions: 4, 3:3:3:3 |  
| Default  |    Utility Positions |      Positions: 1, 12 |  
| Default  |    MainTop Positions | Positions: 4, 3:3:3:3 |  
| Default  |   MainBody Positions |     Positions: 2, 8:4 |  
| Default  | MainBottom Positions | Positions: 4, 3:3:3:3 |  
| Default  |  Extension Positions | Positions: 4, 3:3:3:3 |  
| Default  |     Bottom Positions | Positions: 4, 3:3:3:3 |  
| Default  |     Footer Positions | Positions: 4, 3:3:3:3 |  
| Default  |  Copyright Positions |   Positions: 3, 3:6:3 |  

### Advanced
| Override |                  Option |                                                           Setting |  
| :------- | ----------------------: | ----------------------------------------------------------------: |  
| Default  |             Layout Mode |                                                        Responsive |  
| Default  |        Maintenance Mode |                                                               Off |  
| Default  |            Gantry Cache |                                      Enabled: On, Cache Time: 900 |  
| Default  |          Gantry GZipper | Enabled: On, Cache Time: 600, Expires: 1440, Strip Whitespace: On |  
| Default  |         Display Content |                                                                On |  
| Default  |        Display Mainbody |                                                                On |  
| Default  |             RTL Support |                                                                On |  
| Default  |           RT Typography |                              Enabled: On, Typography Style: Light |  
| Default  | Disable Auto Paragraphs |                                   Enabled: On, Content Type: Both |  
| Default  |       Disable Texturize |                                                               Off |  

### Assignments
| Override   |              Option |               Setting |  
| :--------- | ------------------: | --------------------: |  
| Front Page | Template Page Types | Home Page, Front Page |  

[override]: http://gantry-framework.org/documentation/wordpress/configure/