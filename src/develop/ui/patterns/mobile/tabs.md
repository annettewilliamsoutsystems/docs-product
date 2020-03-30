---
tags: runtime-mobileandreactiveweb;  
summary: 
---

# Tabs Pattern

You can use the Tabs UI pattern to display large sets of information, which can be split into different areas, while always remaining a click away. 

## How to Use the Tabs UI Pattern

1. In Service Studio, select the **Interface** tab.

2. On the left side of the screen, in the **Search** field, enter **Tabs**. 
    
    The Tabs block is displayed. 

     ![](<images/tabs-image-1.png>)

3. From the Toolbox, drag the Tabs block onto your application's screen. 

    ![](images/Tabs_pattern.png)

4. Add your content to the Content placeholders.

     The **Tab 1** - **Tab 5** placeholders represent the header tabs.

     The **Tab Content 1** - **Tab Content 5** placeholders represent the content of each tab.   


5. On the **Properties** tab, set the **StartingTab** property to display the tabs when rendering.

After following these steps and publishing the module, you can test the pattern in your app.

### Add Styles to Tabs and Content

The following CSS code is an example of how to change the style of selected items in the tabs:

    
    
    .tabs-header-tab {
         background-color: #ebebeb;
    }
    
    
    .tabs-header-tab.active {
        border-bottom: 3px solid #000;
        background-color: #ebebeb;
        color: #0097eb;
    }
    
    
    .tabs-content-tab {
        background-color: #ccc;
        padding: 20px;
        font-size: 18px;
        font-stretch: condensed;
    }

### Hide Tabs with No Content

All Silk patterns hide _divs_ with no content. If you only need 2 or 3 tabs, and you want to hide the others, you don’t need to do anything.

## Properties

**Property** |  **Description** |  **Default Value**  
---|---|---  
![](images/input.png) StartingTab  |  Index of the currently active tab.  |  0  
  
## Events

**Event Name** |  **Description** |  **Mandatory**  
---|---|---  
![](images/Event.png) OnTabChange  |  Triggered when switching tabs.  |  _False_  
  
### Layout and Classes

 
  
## Device and Patterns Compatibility

Incompatibility with RTL on Android devices with 4.4.2 OS version.

Avoid using Tabs inside patterns with swipe events, like Stacked Cards or Carousel.

## Samples

The following samples use the Tabs pattern:

![](images/Tabs-sample-1.PNG)

![](images/Tabs-sample-2.PNG)

