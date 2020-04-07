---
tags: runtime-traditionalweb; 
summary: CharacterCount displays the number of characters left to be entered in a target input field.
---

# Character Count

You can use the Character Count UI Pattern to inform users about the maximum and remaining number of characters they can enter into an input field. 

 ![](<images/charactercount-image-5.png>)

**How to use the Character Count UI Pattern**

<!---1. In Service Studio, in the Toolbox, search for `Input`. 

    The Input widget is displayed.

    ![](<images/charactercount-image-6.png>)

1. From the Toolbox, drag the Input widget onto your application’s screen.

1. On the **Properties** tab, enter a name for the Input widget, for example, CharacterCount.

    ![](<images/charactercount-image-3.png>)

1. From the **Main Flow** menu, right-click **CharacterCount**, and choose **Add Local Variable**.
 

1. Set the variable's **Data Type** to **Text**.

    ![](<images/charactercount-image-4.png>) -->

**Prerequisites:** You have created an Input widget called CharacterCount.

1. In Service Studio, in the Toolbox, search for `Character Count`. 

    The Character Count widget is displayed.

    ![](<images/charactercount-image-7.png>)

1. From the Toolbox, drag the Character Count widget into the Main Content area of your application's screen.

    ![](<images/charactercount-image-8.png>)

1. On the **Properties** tab, set the **InputWidgetId** property to the Input widget name (CharacterCount) and use the **Limit** property to set the maximum number of characters allowed, for example, 50.

    ![](<images/charactercount-image-1.png>)

After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| **Property** |  **Description** |
|---|---|
| InputWidgetId (Text): Mandatory | Input element name that triggers the count. A valid expression must be set for this property. |
| Limit (Integer): Mandatory  | Character count limit. This value should be the same as the Max Length of the Input widget. |
| IsDescending (Boolean): Optional  | If set to False, the count goes from 0 to the limit set for the Limit property. If set to True, the count goes from the Limit property to 0. This is the default setting.|

<!---## See also
* OutSystems UI Live Style Guide: [Character Count](https://outsystemsui.outsystems.com/WebStyleGuidePreview/CharacterCount.aspx) -->
