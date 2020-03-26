---
tags: runtime-traditionalweb; 
summary: IconBadge displays numerical information as notification.
---

# Icon Badge
 **_Note:_**  _Applicable to Traditional Web Apps Only_.

You can use the Icon Badge UI pattern to display numerical information as a notification. This UI pattern is frequently used to notify users about new messages or tasks.

![](<images/iconbadge-image-1.png>)


**How to Use the Icon Badge UI Pattern**

Add an icon to the placeholder, then set the color and apply the light theme.

1. In Service Studio, select the **Interface** tab.
2. On the left side of the screen, in the **Search** field, enter **Icon Badge**.

    The Icon Badge block is displayed.

    ![](<images/iconbadge-image-3.png>)

1. From the Toolbox, drag the Icon Badge block onto your application's screen. 


1. On the **Properties** tab, set the relevant properties for the Icon Badge block.

    ![](<images/iconbadge-image-4.png>)
    
After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| **Property** |  **Description** |  **Usage** |
|---|---|---|---|---|
| Number (Integer): Optional  |  Number that appears inside the icon badge. |
| Color (Color Identifier): Optional  |  Color of icon badge. | 
| IsLight (Boolean): Optional|  Use the lightest color version for the background and the darker color version for the text. |
| ExtendedClass (Text):Optional  |  Add custom style classes to the Block. |


## See Also
* OutSystems UI Live Style Guide: [Icon Badge](https://outsystemsui.outsystems.com/WebStyleGuidePreview/IconBadge.aspx)
* OutSystems UI Pattern Page: [Icon Badge](https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternDetail?PatternId=43)