---
tags: runtime-traditionalweb; 
summary: Badge display numerical information as notification.
---

# Badge

 **_Note:_**  _Applicable to Traditional Web Apps Only_.

You can use the Badge UI pattern to display numerical information as a notification. The Badge UI pattern is frequently used to notify users about new messages or tasks.  

![](<images/badge-image-7.png>)

**How to Use the Badge UI Pattern**


1. In Service Studio, select the **Interface** tab.
2. On the left side of the screen, in the **Search** field, enter **Badge**.

    The Badge block is displayed.

    ![](<images/badge-image-9.png>)

3. From the Toolbox, drag the Badge block onto your application's screen.
4. On the **Properties** tab, set the relevant Badge properties, for example, color, shape, and size.

    ![](<images/badge-image-8.png>)


After following these steps and publishing the module, you can test the pattern in your app.
     


## Properties

| **Property** |  **Description** |  **Usage** |
|---|---|---|---|---|
| Number (Integer): Optional  | Number that appears inside the badge. | 
| Color (Color Identifier): Optional  | Set the badge color. | 
| Shape (Shape Identifier): Optional  | Set the badge shape. | 
| Size (Size Identifier): Optional  | Set the badge size. |
| IsLight (Boolean): Optional  | If set to True, the lightest color version is applied to the background and a darker color applied to the text. If set to False, the darker color version is applied to the background, and the lighter color to the text. |
| ExtendedClass (Text): Optional |  Add custom style classes to the block. | 


## Additional Notes

If the number on Badge pattern is greater than 99, it is displayed as 99+.

![](<images/badge-image-6.png>)



  ## See Also

* OutSystems UI Live Style Guide: [Badge](https://outsystemsui.outsystems.com/WebStyleGuidePreview/Badge.aspx)
* OutSystems UI Pattern Page: [Badge](https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternDetail?PatternId=7)

 