---
tags: runtime-traditionalweb; 
summary: Badge display numerical information as notification.
---

# Badge

You can use the Badge UI Pattern to display numerical information as a notification. The Badge UI pattern is frequently used to notify users about new messages or tasks.  

![](<images/badge-image-7.png>)

**How to use the Badge UI Pattern**

1. In Service Studio, in the Toolbox, search for `Badge`. 

    The Badge widget is displayed.

    ![](<images/badge-image-10.png>)
    
1. From the Toolbox, drag the Badge widget onto your application's screen.
1. On the **Properties** tab, set the relevant Badge properties, for example, color, shape, and size.

    ![](<images/badge-image-8.png>)

After following these steps and publishing the module, you can test the pattern in your app.
     
## Properties

| **Property** |  **Description** |  **Usage** |
|---|---|---|
| Number (Integer): Optional  | Number that appears inside the badge. | 
| Color (Color Identifier): Optional  | Set the badge color. | 
| Shape (Shape Identifier): Optional  | Set the badge shape. | 
| Size (Size Identifier): Optional  | Set the badge size. |
| IsLight (Boolean): Optional  | If set to True, the lightest color version is applied to the background and a darker color applied to the text. If set to False, the darker color version is applied to the background, and the lighter color to the text. |
| ExtendedClass (Text): Optional |  Add custom style classes to the block. | 


## Additional notes

If the number on Badge pattern is greater than 99, it is displayed as 99+.

![](<images/badge-image-6.png>)

  ## See also

* OutSystems UI Live Style Guide: [Badge](https://outsystemsui.outsystems.com/WebStyleGuidePreview/Badge.aspx)
* OutSystems UI Pattern Page: [Badge](https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternDetail?PatternId=7)

 