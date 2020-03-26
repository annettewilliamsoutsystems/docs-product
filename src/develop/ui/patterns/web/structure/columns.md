---
tags: runtime-traditionalweb; 
summary: Columns split content into multiple columns with responsive capabilities to improve the way information is displayed.
---

# Columns
**_Note:_**  _Applicable to Traditional Web Apps Only_.

You can use the Columns pattern to split content into multiple columns with responsive capabilities, improving the way information is displayed on screen.

 ![](<images/columns-image-4.png>)


**How to Use the Columns UI Pattern**


1. In Service Studio, select the **Interface** tab.

1. On the left side of the screen, in the **Search** field, enter **Column**. 
    
    The various Column blocks are displayed. 

    ![](<images/columns-image-5.png>)

1. From the Toolbox, drag the relevant Column block onto your application’s screen.
1. Add the required content to the Column block, for example, counters.

    ![](<images/columns-image-1.png>)

1. On the **Properties** tab, set the relevant properties for the Column block.
    ![](<images/columns-image-2.png>)

After following these steps and publishing the module, you can test the pattern in your app.
  
## Properties

| **Property** |  **Description** |
|---|---|---|---|---|
| GutterSize (GutterSize Identifier): Optional | Set the gutter size. | 
| TabletBehavior (BreakColumns Identifier): Optional | Responsive behavior for tablets. 
| PhoneBehavior (BreakColumns Identifier): Optional | Responsive behavior for phones. | 
| ExtendedClass (Text): Optional  |  Add custom style classes to the block. |


## See Also
* OutSystems UI Live Style Guide: [Columns](https://outsystemsui.outsystems.com/WebStyleGuidePreview/Columns2.aspx)
* OutSystems UI Pattern Page: [Columns](https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternDetail?PatternId=21)