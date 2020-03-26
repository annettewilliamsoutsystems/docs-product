---
tags: runtime-traditionalweb; 
summary: UserInitials display user information in a circular badge.
---

# User Initials

**_Note:_**  _Applicable to Traditional Web Apps Only_.

Display user information in a circular badge.

You can use the User Initials UI pattern to display a user’s initials or their image in a circular badge. 

![](<images/userinitials-image-4.png>)

**How to Use the User Initials UI Pattern**

1. In Service Studio, select the **Interface** tab.
2. On the left side of the screen, in the **Search** field, enter **User Initials**. 

    The Stacked Icon block is displayed.      
        ![](<images/userinitials-image-9.png>)
    
    
3. From the Toolbox, drag the Stacked Icon block onto your application's screen.

  
4. On the **Properties** tab, set the relevant properties. 

    ![](<images/userinitials-image-10.png>)
    
 
After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| **Property** |  **Description** |  **Usage** | **Mandatory** | **Default Value** |
|---|---|---|---|---|
| Name (Text): Optional  |  The username used in the pattern. | 
| Color (Color Identifier): Optional  |  Badge color. | 
| Shape (Shape Identifier): Optional|  Badge shape. | 
| Size (Size Identifier): Optional  |  Badge size. | |
| IsLight (Boolean): Optional | If set to True, the lightest color version is applied to the background. If set to False, the darker color version is applied. |
| ExtendedClass (Text): Optional  |  Add custom style classes to the block.
 |




### See Also
* OutSystems UI Live Style Guide: [User Initials](https://outsystemsui.outsystems.com/WebStyleGuidePreview/UserInitials.aspx)
* OutSystems UI Pattern Page: [User Avatar](https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternDetail?PatternId=80)