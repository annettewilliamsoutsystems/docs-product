---
tags: runtime-traditionalweb; 
summary: CharacterCount displays the number of characters left to be entered in a target input field.
---

# Character Count

You can use the Character Count UI pattern to inform users about the maximum and remaining number of characters they can enter into an input field. 

[//]: # (Add preview screenshot here if possible)

**How to Use the Character Count UI Pattern**

1. In Service Studio, select the **Interface** tab.
1. On the left side of the screen, in the **Search** field, enter **Input Count**.

    The Character Count block is displayed.

    [//]: # (Add Input icon here)
   
1. From the Toolbox, drag the Input block onto your application's screen.
1. Enter a name for the Input block, for example, CharacterCount.

    ![](<images/charactercount-image-3.png>)

1. From the **Main Flow** menu, right-click **CharacterCount**, and choose **Add Local Variable**.
 

1. Set the variable's **Data Type** to **Text**.
       ![](<images/charactercount-image-4.png>)

1. From the Toolbox, search for the Character Count pattern and drag it onto the screen.

1. On the **Properties** tab, set the **InputWidgetId** property to the Input block name (CharacterCount) and use the **Limit** property to set the maximum number of characters allowed, for example, 50.


    ![](<images/charactercount-image-1.png>)

After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| **Property** |  **Description** | **Usage** |
|---|---|---|
| InputWidgetId (Text): Mandatory | Input element name that triggers the count. |
| Limit (Integer): Mandatory  | Character count limit. This value should be the same as the Max Length for the input block. |
| IsDescending (Boolean): Optional  | If set to False, the count goes from 0 to the limit set for the Limit property.|

## See Also
* OutSystems UI Live Style Guide: [Character Count](https://outsystemsui.outsystems.com/WebStyleGuidePreview/CharacterCount.aspx)
