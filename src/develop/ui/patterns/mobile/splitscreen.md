---
tags: runtime-mobileandreactiveweb;  
summary: 
---

# SplitScreen 

You can use the Splitscreen UI Pattern to split a tablet screen into two independent vertical panels. It allows you display, for example, a selected item in one panel, and the details of that selected item in the other panel.
 
The Splitscreen UI pattern also adapts to a phone layout by showing only one panel at a time. 

![](images/Service_Studio_Split_Screen.png)

## How to Use the SplitScreen UI Pattern

Define the percentage of the screen that the left side will occupy and bind a variable to handle the state of the right area on mobile phones (open and close). You can also bind your own logic to the **DetailClose** event.

1. Create a local boolean variable and set it on the **OpenedOnPhone** property.

    ![](images/adaptive_split_screen.png)

1. To open the detail of the clicked element, use a link for an action and set your local variable to **True**. Add logic to open the correct detail.

    ![](images/split_screen_list_open.png)

1. To close the detail, create an action and set your local variable to _False_ , and use this action in the event **DetailClose**. Add logic in this process.

    ![](images/close_detail.png)

### Phone Landscape with the Same Behavior as Tablet

In **Service Studio**, open the **Style Sheet Editor**, and add the following code:

    
    
    .phone.landscape .split-left {
             width: **x; /* Enter the width value for the left side */**
    }
    
    
    
    .phone.landscape .split-right {
             -webkit-transform: translateX(0) translateZ(0);
                    transform: translateX(0) translateZ(0);
            width: **x; /* Enter the width value for the right side */**
             left: auto;
            right: 0;
            border-left: 1px solid #d3d3d3;
    }
    
    
    .phone.landscape .detail-open .split-right-close {
            opacity: 0;
            pointer-events: none;
    }
    
    
    .phone.landscape .detail-open .app-menu-icon {
            opacity: 1;
            pointer-events: auto;
    }
    

## Properties

**Property** |  **Description** |  **Default Value** | 
|---|---|---| 
![](images/input.png) |  LeftPercentage |  Percentage given to the left side of the split screen.  |
![](images/input.png) |  OpenedOnPhone |  Used to open and close the right side of the split screen (detail). | 
  

## Compatibility with other Patterns

You can use this pattern on its own inside the screen content as it adapts to the height of the parent element. Avoid using it inside patterns with swipe events, such as Tabs or Carousel.

## Samples

The following sample uses the SplitScreen pattern:

![](images/SplitScreen-Sample-1.PNG)
