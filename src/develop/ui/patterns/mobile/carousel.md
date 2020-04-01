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
  

1. From the Toolbox, drag the Carousel widget onto your application's screen. 

    ![](images/Carousel_drag_pattern.png)

1. Place your content into the **Carousel Items** placeholder. 

    To use a List, drag it into **Carousel Items** placeholder (disable virtualization and set **Animated items** to False .

    ![](images/Carousel_items.png)


1. All available options have default properties, but you can change them.

    ![](images/Carousel_parameters.png)

After following these steps and publishing the module, you can test the pattern in your app.

### Customizing the dots

You can use CSS to customize the look and feel of the dots.

**Example 1:**
  
    
    .carousel .carousel-dots-container .carousel-dot.active {
         opacity: 1;
        width: 16px;
        height: 2px;
        margin-top: 2px;
        transition: opacity 275ms ease-out;
    }
    
    
    .carousel .carousel-dots-container .carousel-dot {
        border-radius: 0;
        height: 1px;
        margin: 3px 3px;
        width: 8px;
        transition: opacity 275ms ease-out;
    }

![](images/Carousel_before_after_1.png)

**Example 2:**
   
    
    .carousel-dots-container .carousel-dot {
         background: #fff;
        border: 0px solid #fff;
        height: 4px;
        margin: 3px;
        opacity: .5;
        width: 4px;
    }
    
    
    .carousel-dots-container .carousel-dot.active {
        background: transparent;
        border: 1px solid #fff;
        opacity: 1;
    }

![](images/Carousel_before_after_2.png)

### Using the Carousel Pattern inside the Columns Pattern

To use the Carousel Pattern inside any Columns Pattern , you must fix the columns’ overflow, by adding the following style to the CSS:
   
    
    .col {
        overflow: hidden;
    }
    

### Getting the current position of a Carousel Item

  1. Create an **Integer** local variable (for example, Position) on the screen. 
  1. In the **OnItemChange** event of the block, create a new client action for the handler (CarouselCurrentPosition).   
    a. The action receives a variable **Index** , which is the event that
indicates the current position in the Carousel.

  1. Drag an **Assign** node and set the Position (your local variable) to Index. 

![](images/Carousel_current_position.png)

### Creating an onboarding screen using the Carousel Pattern

A typical onboarding screen has a Carousel that takes the full height of the
screen, slides for a couple of items and then displays a button to start using
the app on the last slide. Follow the steps below to create your own
onboarding screen using the Carousel.

#### Creating a carousel that occupies the screen height

1. Start with a new Screen using a Blank Layout (Common\LayoutBlank).

1. Drag the **Carousel** pattern into the **Content** placeholder
(Interaction\Carousel).

1. Add content to the Carousel, either static or dynamic items, from a List.  
**Note: If you use a List Widget, you need to disable virtualization.**

Here's what it would look like:

**![image.png](images/image.png) **

#### Displaying a Button when Viewing the Last Carousel Item

1. Create a **boolean** local variable on the screen called **ShowButton**.

1. Create an action called **OnChange** and add it to the **OnItemChange**
handler of the Carousel.

1. In this action, we will verify if the current position is equal to the
total number of elements in the OnBoarding’s Carousel.

![](images/Carousel_onboarding.png)

1. The logic is: if **“Index = 2”** the local variable is assigned to _True_
, otherwise it is assigned to _False_ .
1. The variable **showButton** shows the button to the user.

1. Drag the **FloatingContent** pattern (Content\FloatingContent) into the
screen.

1. Add a **Container** and in the **Visible** parameter, set the local
variable **showButton**.  
a. Drag the “ **Animate** ” block into the container, and set the **Animation
Type**.  
b. Add a button into the Content placeholder.  
  
1. Publish your app.

### Creating a carousel with navigation buttons

This pattern includes [public actions](<public-actions.md>) that you can use without having to use the Carousel's own
navigation (Next, Previous or GoTo). In this use case, we will only use
buttons to navigate in the Carousel:

1. Create an action and drag either one of the public actions Next, Previous
or GoTo.

1. Create a button to associate the **onClick** event with the created
action.

1. See the image below with all possible actions.

![](images/Carousel__on_click.png)

### Creating a ListRemove in Carousel

This pattern includes the **UpdateCarousel** [public actions](<public-actions.md>) to update all variables and positions in the Pattern:

1. Create an action and drag the **ListRemove** and **CarouselUpdate**
actions.

1. Create a **ListRemoveOnClick** button and associate the created action.

1. See the example in the image below.

![](images/Carousel_list_remove.png)

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