---
tags: runtime-mobileandreactiveweb;  
summary: 
---

# Carousel Pattern

You can use the Carousel UI Pattern to display multiple items in a horizontal slide. This pattern is ideal for creating horizontal slides in smaller screens. You can also use this pattern for dynamic content, by placing a List directly inside the placeholder. 

![](images/Carousel_studio_preview.png)

## How to use the Carousel UI Pattern

1. In Service Studio, in the Toolbox, search for `Carousel`.
  
     The Carousel widget is displayed.

    ![](images/carousel-widget.png)
  

1. From the Toolbox, drag the Carousel widget into the Main Content area of your application's screen.

    ![](images/carousel-image-widget.png)

1. Place your content into the **Carousel Items** placeholder. 

    To use a List, drag it into **Carousel Items** placeholder (disable virtualization and set **Animated items** to False .

    ![](images/Carousel_items.png)


1. All available options have default properties, but you can change them.

    ![](images/Carousel_parameters.png)

After following these steps and publishing the module, you can test the pattern in your app.

## Properties

Property |  Description |  Default Value  
---|---|--- 
 ![](images/input.png)  Navigation  |  Enable or disable buttons to navigate left and right.  |  False
 ![](images/input.png)  Dots  |  Enable or disable dots to represent items on the Carousel, which can be tapped to navigate directly to a given item.  | True
 ![](images/input.png)  Margin  |  Set the distance between each Carousel item.  |  0 
 ![](images/input.png)  Padding  |  Set the distance between the screen edges and the visible items on the screen.  |  0
 ![](images/input.png)  AutoPlay  |  Enable or disable the autoplay velocity. |  Disabled
 ![](images/input.png)  Scale  |  Use the scale option for each carousel item.  |  False
 ![](images/input.png)  Loop  |  Enable or disable continuous slide of the Carousel even after it reaches the end.  |  False
 ![](images/input.png)  Center  |  Display the active item centered horizontally.  |  False
 ![](images/input.png)  InitialPosition  |  Set the first element to show.  | 0
 ![](images/input.png)  Items  |  Number of visible Carousel items at the same time on the screen.  |  1
  
 
## Compatibility with other patterns

Avoid using the Carousel inside patterns with swipe events, such as the Tabs and Stacked Cards Patterns.

## Samples

See how the [Product Dashboard sample](https://silkui.outsystems.com/Samples_Mobile.aspx#Mobile_Content-Samples_ProductDashboard) uses the Carousel pattern:

![](images/Sample_Product_Dashboard.png)

## See also
* OutSystems UI Live Style Guide: [Carousel](https://outsystemsui.outsystems.com/WebStyleGuidePreview/Carousel.aspx)
* OutSystems UI Pattern Page: [Carousel](https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternDetail?PatternId=17)