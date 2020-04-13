---
tags: runtime-traditionalweb; 
summary: MoveOnDevice defines where information is displayed thereby improving the display on different devices.
---

# Move on Device

You can use the Move on Device UI Pattern to define the placement of information depending on the device.

![](<images/moveondevice-image-3.png>)

**How to use the Move on Device UI Pattern**  

**Prerequisite**: You have added containers to your application. 

1. In Service Studio, in the Toolbox, search for `Move on Device`. 

    The Move on Device widget is displayed.
    
    ![](<images/moveondevice-image-4.png>)

1. From the Toolbox, drag the Move on Device widget into the Container area of your application's screen.

    ![](<images/moveondevice-image-5.png>)

1. Add the required content to the Move on Device placeholder, for example, menu items or images. 

1. On the **Properties** tab, set the target container IDs you want to move the content to.

    ![](<images/moveondevice-image-2.png>)

After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| **Properties** |  **Description** |
|---|---|
| PhoneWidgetId (Text): Optional  | Target container that displays this widget on phones. <p>Examples <ul><li>_Blank_ - </li><li>_Phone.Id_ - </li></ul></p>|
| TabletWidgetId (Text): Optional | Target container that displays this widget on tablets.<p>Examples <p>Examples <ul><li>_Blank_ - </li><li>_Tablet.Id_ - </li></ul></p>||



<!---  Added to yml file
## See also
* OutSystems UI Live Style Guide: [Move on Device](https://outsystemsui.outsystems.com/WebStyleGuidePreview/MoveOnDevice.aspx)
