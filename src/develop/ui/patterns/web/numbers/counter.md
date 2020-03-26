---
tags: runtime-traditionalweb; 
summary: Counter shows the total number of occurrences of several values regarding a single topic.
---

# Counter

**_Note:_**  _Applicable to Traditional Web Apps Only_.

You can use the Counter UI pattern to give feedback about the current count of several elements and to show the total number of occurrences of several values regarding a single topic.

![](<images/counter-image-5.png>)

**How to Use the Counter UI Pattern**


1. In Service Studio, select the **Interface** tab.

2. On the left side of the screen, in the **Search** field, enter **Counter**.
   
    The Counter block is displayed.
    
    ![](<images/counter-image-6.png>)
    
  


3. From the Toolbox, drag the Counter block onto your application’s screen.
4. On the **Properties** tab, set the relevant properties.

    ![](<images/counter-image-3.png>)

After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| **Property** |  **Description** | **Usage** |
|---|---|---|---|---|
| Orientation (Orientation Identifier): Optional  | Set the orientation. |
| Height (Text): Optional  | Height of block (pixel units). | 
| ExtendedClass (Text): Optional  |  Add custom style classes to the block. | 

## Layout and Classes

![](<images/counter-image-2.png>)

## CSS Selectors

| **Element** |  **CSS Class** |  **Description**  |
| --- | --- | --- |
| .center-align | .flex-direction-column |  When Orientation is Vertical  |

## Advanced Use Case

### Add a new style to the Counter pattern

1. Drag the Counter pattern into the preview.

1. Set the Orientation to `Vertical`, Height to `200` and ExtendedClass property to `background-blue shadow-xl`.

    ![](<images/counter-image-3.png>)

1. Drag a container into Counter placeholder and type '26'.

1. Set the Style Classes property of the container to `font-size-display text-neutral-0`.

1. Drag a container into Counter placeholder and type 'Completed Requests'.

1. Drag another container into Counter placeholder.

1. Drag an Icon Widget into the container and set the Name property to `Entities.IconName.check` and Size to `Entities.IconSize.Size_3x`.
    
    ![](<images/counter-image-4.png>)

1. Publish and test.
    
    ![](<images/counter-image-5.png>)


  ## See Also

* OutSystems UI Live Style Guide: [Counter](https://outsystemsui.outsystems.com/WebStyleGuidePreview/Counter.aspx)
* OutSystems UI Pattern Page: [Counter](https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternDetail?PatternId=30)