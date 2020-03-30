---
tags: runtime-traditionalweb; 
summary: LightBoxImage displays an image thumbnail that is clicked to open a fullscreen image.
---

# Lightbox Image

You can use the Lighbox Image UI pattern to open smaller images in full screen mode. This UI pattern is often used when creating an image gallery, allowing you to navigate through each of the images and view them in more detail.  


**How to Use the Lighbox UI Pattern**

1. In Service Studio, select the **Interface** tab.

2. On the left side of the screen, in the **Search** field, enter **Lightbox Image**.

    The Lightbox Image block is displayed.

    ![](<images/lightboximage-image-7.png?width=600>)
     
  3. From the Toolbox, drag the Lightbox Image block onto your application's screen.
  4. On the **Properties** tab, set the **Type** property for the Image.

        Note: In this example, the property type is set to **Local Image**. You can also choose **External URL** or **Binary Data**.

      ![](<images/lightboximage-image-8.png>)
        
5. Select or import an image into the **Image** property.
      ![](<images/lightboximage-image-9.png>)

6.  On the **Properties** tab, Set the relevant Lightbox Image properties. 

     ![](<images/lightboximage-image-10.png>)

After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| **Property** |  **Description** |  **Usage** | 
|---|---|---|
| Title (Text): Optional  |Image title that is displayed. |
| Group (Text): Optional | Images in the same group that are displayed in a gallery format. |
| ImageURL (Text): Optional | URL for an image that can be a replacement for the Image Placeholder image. |
| ImageZoom (Decimal): Optional  |  Defines the size of the image that opens in full screen mode based on the thumbnail size. <p> To avoid rendering problems, try to use images with the same ratio: <ul> - A thumbnail with 100x100, and zoom 2 opens with 200x200.</ul><ul> - A thumbnail with 500x500, and zoom 0.5 opens with 250x250.</ul></p> |
| ExtendedClass (Text): Optional |  Add custom style classes to the block. |





## See Also
* OutSystems UI Live Style Guide: [Lightbox Image](https://outsystemsui.outsystems.com/WebStyleGuidePreview/LightboxImage.aspx)
* OutSystems UI Pattern Page: [Lightbox Image](https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternDetail?PatternId=46)
