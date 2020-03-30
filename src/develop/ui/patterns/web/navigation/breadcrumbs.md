---
tags: runtime-traditionalweb; 
summary: Breadcrumbs present the location of the user within the hierarchy of applications.
---

# Breadcrumbs

You can use the Breadcrumbs UI pattern as a navigational aid that helps users keep track of their location within the app.

  ![](<images/breadcrumbs-image-2.png>)

**How to Use the Breadcrumbs UI Pattern**

1. In Service Studio, select the **Interface** tab.

2. On the left side of the screen, in the **Search** field, enter **Breadcrumbs**. 
    
    The Breadcrumbs block is displayed. 
    
    ![](<images/breadcrumbs-image-6.png>)

3. From the Toolbox, drag the Breadcrumbs block onto your application's screen.

4. Drag the required number of Breadcrumb Item blocks into the Content placeholder.
    
    ![](<images/breadcrumbs-image-7.png>)
    
    **Note**: Each Breadcrumb Item represents a different location in the breadcrumb trail.

5. On the **Properties** tab, set the content in the placeholders, for example, titles, icons, and links to the relevant pages.

    ![](<images/breadcrumbs-image-1.png>)


  After following these steps and publishing the module, you can test the pattern in your app.

## Properties

### Breadcrumbs

| **Property** |  **Description** |  **Usage** | 
|---|---|---|
| ExtendedClass (Text): Optional  |  Add custom style classes to the block. | 

### Breadcrumb Item

| **Property** |  **Description** |  **Usage** | 
|---|---|---|
| ExtendedClass (Text): Optional  |  Add custom style classes to the block. |


## Additional Notes

The Line Separator property of the ListRecords widget should be set to **None**.

![](<images/breadcrumbs-image-5.png>)

## See Also

* OutSystems UI Live Style Guide: [Gallery](https://outsystemsui.outsystems.com/WebStyleGuidePreview/Breadcrumbs.aspx)
* OutSystems UI Pattern Page: [Gallery](https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternDetail?PatternId=10)
