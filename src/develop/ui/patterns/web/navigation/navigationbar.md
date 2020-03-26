---
tags: runtime-traditionalweb; 
summary: 
---

# Navigation Bar

**_Note:_**  _Applicable to Traditional Web Apps Only_.

You can use the Navigation BAr UI pattern to organize the content and enable quick navigation through an application with vertically stacked links. These stacked links can be displayed with different hierarchy levels. The NavigationBar pattern uses the Navigation Bar Item and Navigation Bar SubItem to create the necessary structure.

Use it when the end user needs to navigate through an application's main sections while maintaining the ability to browse to another subsection quickly. 

**How to Use the Navigation Bar UI Pattern**

1. In Service Studio, select the **Interface** tab.

2. On the left side of the screen, in the **Search** field, enter **Navigation Bar**. 
    
    The Navigation Bar block is displayed. 

3. From the Toolbox, drag the Navigation Bar block onto your application's screen. 

    ![](images/navigationbar-image-1.png?width=500)

4. Drag the required number of Navigation Bar Item blocks into the Content placeholder.

5. Drag the required number of Navigation Bar Sub Item blocks into the Navigation Bar Item Content placeholder.

    ![](images/navigationbar-image-2.png)

6. On the **Properties** tab, set the required values.

    ![](images/navigationbar-image-3.png)

After following these steps and publishing the module, you can test the pattern in your app.

## Properties
#### Navigation Bar
| **Property** |  **Description** |  **Usage** | 
|---|---|---|---|---|
| IsFixed (Boolean): Optional |  If set to True, the navigation bar will allways be in the same position on the screen. If set to False, it scrolls with the page content. |  
| TopPosition (Integer): Optional  |  Set the top position when the navigation bar is fixed. (Insert a number - the pixels unit is automatically added.) |  
| MultipleItems (Boolean): Optional |  Allows multiple Navigation Bar Items to be opened having an accordian effect. | 
| ExtendedClass (Text): Optional |  Add custom style classes to the block. | T|

#### Navigation Bar Item
| **Property** |  **Description** |  **Usage** | 
|---|---|---|---|---|
| IsActive  |  Set IsActive to true, to define as the selected element. |  Boolean | False | False |
| IsOpen  |  If true, when rendering the NavigationBarItem is open. |  Boolean | False | False |
| ExtendedClass  |  Add custom style classes to this Block. | Text | False | none |

#### Navigation Bar Sub Item
| **Property** |  **Description** |  **Usage** | 
|---|---|---|---|---|
| IsActive  |  Set IsActive to true, to define as the selected element. |  Boolean | False | False |
  
## Layout and Classes


## Device Compatibility

In Internet Explorer, `position: fixed` is used instead of `position: sticky` as the latter is not supported.


## See Also

* OutSystems UI Live Style Guide: [Navigation Bar](https://outsystemsui.outsystems.com/WebStyleGuidePreview/NavigationBar.aspx)

