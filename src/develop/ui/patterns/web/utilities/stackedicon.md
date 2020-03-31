---
tags: runtime-traditionalweb; 
summary: StackedIcon expands the icon set and creates new graphical representation of concepts.
---

# Stacked Icon

You can use the Stacked Icon Pattern to stack two icons on top of each other, expand the icon set, and to create new graphical representations of concepts.  

![](<images/stackedicon-image-8.png>)

**How to use the Stacked Icon UI Pattern**

1. In Service Studio, in the Toolbox, search for `Stacked Icon`. 

    The Stacked Icon widget is displayed.

   ![](<images/stackedicon-image-9.png>)

  1. From the Toolbox, drag the Stacked Icon widget onto your application’s screen.

1. On the **Properties** tab, set the relevant properties for the icons. 

    ![](<images/stackedicon-image-7.png>)


After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| **Property** |  **Description** |  **Usage** |
|---|---|---|
| IconFront (IconName Identifier): Optional| The icon that displays in front of the other icon. |
| IconBack (IconName Identifier): Optional | The icon that displays behind the icon.|
| IconFrontColor (Color Identifier): Optional | Front icon color. | 
| IconBackColor (Color Identifier): Optional | Back Icon color. |
| IconSize (IconSize Identifier): Optional| Icon size. |
| InvertSize (Boolean): Optional | Set to True to swap the icon sizes. |
| ExtendedClass (Text): Optional |  Add custom style classes to the block. | 


## See also
* OutSystems UI Live Style Guide: [Stacked Icon](https://outsystemsui.outsystems.com/WebStyleGuidePreview/StackedIcon.aspx)
