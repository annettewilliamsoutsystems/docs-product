---
tags: runtime-traditionalweb; 
summary: MoveOnDevice defines where information is displayed thereby improving the display on different devices.
---

# Move on Device

You can use the Move on Device UI pattern to define the target container for several elements in different devices without duplicating them. Depending on the device, for example, a tablet or mobile phone, this UI pattern defines where information is displayed on the screen, thereby improving the display on the specified device.


**How to Use the Move on Device UI Pattern**  

**Prerequisite**: Your application must have containers. 
1. In Service Studio, select the **Interface** tab.
1. On the left side of the screen, in the **Search** field, enter **Move on Device**. 

    The Move on Load on Visible block is displayed.


1. From the Toolbox, drag the Move on Device block onto your application’s screen.
1. Add the required content to the placeholder, for example, menu items or images. 
1. Set the target container IDs you want to move the content to.

    ![](<images/moveondevice-image-2.png>)

After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| **Properties** |  **Description** |  **Usage** | 
|---|---|---|
| PhoneWidgetId (Text): Optional  | Target container receives this block on phones. |
| TabletWidgetId (Text): Optional | Target container that receives this block on tablets. |


## See Also
* OutSystems UI Live Style Guide: [Move on Device](https://outsystemsui.outsystems.com/WebStyleGuidePreview/MoveOnDevice.aspx)
