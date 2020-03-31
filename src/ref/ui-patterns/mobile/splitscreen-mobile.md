---
tags:
summary: 
---

# SplitScreen UI Pattern Reference

## Events

**Event Name** |  **Description** |  **Mandatory**  
---|---|---  
![](images/Event.png)  DetailClose  |  Triggered when the detail (or right side of the splitscreen) is closed.  |  False 
  
## Layout and Classes

![](images/split_screen_layout_classes.png)

## CSS Selectors

**Element** |  **CSS Class** |  **Description**  
---|---|---  
![](images/css_selector.png) |  MasterDetail Wrapper  |  .split-screen-wrapper  |  Container that wraps elements in left and right container.  
![](images/css_selector.png) |  Left Content  |  .split-left  |  Add content for the Left side.  
![](images/css_selector.png) |  Right Content  |  .split-right  |  Add content for the Right side. In phone view, this Element is off canvas.  
![](images/css_selector.png) |  Close Right Content  |  .split-right-close  |  
  

 ## See Also

* OutSystems UI Pattern Documentation: [SplitScreen](https://success.outsystems.com/Documentation/11/Developing_an_Application/Design_UI/Patterns/Using_Mobile_Patterns/SplitScreen_Pattern)
