---
tags: runtime-traditionalweb; 
summary: Gallery enables the users to sequentially browse the content when there are many cards grouped into one or more collections.
---

# Gallery

You can use the Gallery UI pattern to display groups of content as scannable collections. This UI pattern allows users to sequentially browse images, with the notion of a beginning and an end. The Gallery UI pattern can be helpful when you have a large number of cards you need to group into one or more scannable collections. 

**How to Use the Gallery UI Pattern**

1. In Service Studio, select the **Interface** tab.

1. On the left side of the screen, in the **Search** field, enter **Gallery**. 
    
    The Gallery block is displayed. 
    
    ![](<images/gallery-image-5.png>)
    

1. Drag a list or static content into the Gallery block.
    
    ![](<images/gallery-image-1.png>)

1. On the **Properties** tab, set the number of items for the desktop, tablet, and phone.
    
    ![](<images/gallery-image-6.png>)

After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| **Property** |  **Description** |  **Usage** | 
|---|---|---|
| ItemsDesktop (Integer): Optional |  Number of Items per line on a desktop. | 
| ItemsTablet (Integer): Optional |  Number of Items per line on a tablet. | 
| ItemsPhone (Integer): Optional|  Number of Items per line on a phone. |
| ExtendedClass  (Text): Optional |  Adds custom style classes to the block. |  


## Additional Notes

Line Separator from ListRecords should be **None**.

![](<images/gallery-image-4.png>)

## See Also

* OutSystems UI Live Style Guide: [Gallery](https://outsystemsui.outsystems.com/WebStyleGuidePreview/Gallery.aspx)
* OutSystems UI Pattern Page: [Gallery](https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternDetail?PatternId=41)

