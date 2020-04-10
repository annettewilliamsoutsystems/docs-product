---
tags: runtime-traditionalweb; 
summary: LightBoxImage displays an image thumbnail that is clicked to open a fullscreen image.
---

# Lightbox Image

You can use the Lightbox Image UI Pattern to open smaller thumbnail images in full screen mode. This UI pattern is often used when creating an image gallery, allowing you to navigate through each of the images and view them in more detail.  

![](<images/lightboxweb-image-11.png>)

**How to use the Lighbox UI Pattern**

1. In Service Studio, in the Toolbox, search for `Lightbox Image`. 

    The Lightbox Image widget is displayed.

    ![](<images/lightboximage-image-12.png>)    

1. From the Toolbox, drag the Lightbox Image widget into the Main Content area of your application's screen.
   
    ![](<images/lightboximage-image-13.png>)

1. . Select the Image widget, and on the **Properties** tab, set the **Type** property for the Image.

    Note: In this example, the property type is set to **Local Image**. You can also choose **External URL** or **Binary Data**.

      ![](<images/lightboximage-image-8.png>)
        
5. From the **Image** property drop-down, select or import an image.

      ![](<images/lightboximage-image-9.png>)

6.  Select the Lightbox Image widget, and on the **Properties** tab, set the relevant Lightbox Image properties, for example, the title of the image that is displayed.

     ![](<images/lightboximage-image-10.png>)

After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| **Property** |  **Description** |
|---|---|
| Title (Text): Optional  |Image title that is displayed. <p>Examples<ul><li>_"Squirrel"_ - Displays *Squirrel* as the image title. </li><li>_"Dog"_ - Displays *Dog* as the image title. </li></ul></p>|
| Group (Text): Optional | Images in the same group that are displayed in a gallery format.<p>Examples<ul><li> </li><li> </li></ul></p> |
| ImageURL (Text): Optional | URL for an image that can be a replacement for the Image Placeholder image.<p>Examples<ul><li> </li><li> </li></ul></p> |
| ImageZoom (Decimal): Optional  |  Defines the size of the image that opens in full screen mode (based on the thumbnail size).<p>To avoid rendering problems, try to use images with the same ratio.<p>Examples</p><ul><li>_2_ - A thumbnail with 100x100, and zoom 2 opens with 200x200.</li><li> _0.5_ - A thumbnail with 500x500, and zoom 0.5 opens with 250x250.</li></ul></p> |
| ExtendedClass (Text): Optional |  Add custom style classes to the Lightbox Image UI Pattern. You define your [custom style classes](../../../../../develop/ui/look-feel/css.md) in your application using CSS. <p>Examples <ul><li>_Blank_ - No custom styles are added (default value)</li><li>_''myclass''_ - adds the myclass style to the Lightbox Image UI styles being applied.<li>_''myclass1'' ''myclass2''_ - adds the _myclass1_ and _myclass2_ styles to the Lightbox Image UI styles being applied.</li></ul></p> |


<!--- ## See also
* OutSystems UI Live Style Guide: [Lightbox Image](https://outsystemsui.outsystems.com/WebStyleGuidePreview/LightboxImage.aspx)
* OutSystems UI Pattern Page: [Lightbox Image](https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternDetail?PatternId=46)
