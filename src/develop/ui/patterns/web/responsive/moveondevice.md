---
tags: runtime-traditionalweb; 
summary: MoveOnDevice defines where information is displayed thereby improving the display on different devices.
---

# Move on Device

You can use the Move on Device UI Pattern to define the target container for several elements in different devices without duplicating them. Depending on the device, for example, a tablet or mobile phone, this UI pattern defines where information is displayed on the screen, thereby improving the display on the specified device.

![](<images/moveondevice-image-3.png>)

**How to use the Move on Device UI Pattern**  

**Prerequisite**: Your application must have containers. 

1. In Service Studio, in the Toolbox, search for `Move on Device`. 

    The Move on Device widget is displayed.
    
    ![](<images/moveondevice-image-4.png>)

1. From the Toolbox, drag the Move on Device widget onto your application’s screen.
1. Add the required content to the placeholder, for example, menu items or images. 
1. Set the target container IDs you want to move the content to.

    ![](<images/moveondevice-image-2.png>)

After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| **Properties** |  **Description** |  **Usage** | 
|---|---|---|
| PhoneWidgetId (Text): Optional  | Target container receives this block on phones. |
| TabletWidgetId (Text): Optional | Target container that receives this block on tablets. |


## See also
* OutSystems UI Live Style Guide: [Move on Device](https://outsystemsui.outsystems.com/WebStyleGuidePreview/MoveOnDevice.aspx)
